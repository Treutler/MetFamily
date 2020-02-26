# MetFamily
Understanding metabolism is fundamental in biomedical and plant research and the identification and quantification of thousands of metabolites by mass spectrometry in modern metabolomics is a prerequisite for elucidating this area. However, the identification of metabolites is a major bottleneck in traditional approaches hampering advances. Here, we present a novel approach for the untargeted discovery of metabolite families offering a bird's eye view of metabolic regulation in comparative metabolomics. We implemented the presented methodology in the easy-to-use web application MetFamily to enable the analysis of comprehensive metabolomics studies for all researchers worldwide.  MetFamily is available under http://msbi.ipb-halle.de/MetFamily/.

# Docker images
The image `sneumann/metfamily-base` contains all dependencies 
for the MetFamily web application.

Build via `docker build -t sneumann/metfamily-base -f Dockerfile-base . `

The image `sneumann/metfamily` is built on top and contains 
the actual MetFamily code and web application. 

Build via `docker build -t sneumann/metfamily . `


