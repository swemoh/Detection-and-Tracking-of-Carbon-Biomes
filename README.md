# Detection and Tracking of Carbon Biomes via Integrated Machine Learning

## What is it about?

In the framework of a changing climate, it is useful to devise methods capable of effectively assessing and monitoring the changing landscape of air-sea CO2 fluxes. In this study, we developed an unsupervised machine learning tool to classify and track marine carbon biomes objectively under seasonally and interannually changing environmental conditions. Carbon biomes are defined as regions having consistent relations between surface CO2 fugacity (fCO2) and its main drivers (temperature, dissolved inorganic carbon, and alkalinity). The detection of carbon biomes was performed by using an agglomeration hierarchical clustering (HC) methodology applied to spatial target-driver relationships, whereby a novel adaptive approach to cut the HC dendrogram based on the compactness and similarity of the clusters was developed. A deep learning model was constructed to track the seasonal and interannual evolution of the carbon biomes, wherein a feed-forward neural network was trained to assign labels to detected biomes. This methodology enabled us to detect well-defined carbon biomes (representative of subtropical, upwelling, subpolar, and sea ice-covered regimes) and to track them in time. We find that the area covered by the carbon biomes responds meaningfully to seasonal and interannually varying environmental conditions. A seasonal competition between the thermally-driven subtropical biomes and non-thermally-driven subpolar biomes is detected over the middle latitudes. The climate-driven trends in biome coverage over the North Atlantic and Southern Ocean are suggestive of long-term shifts in the coverage of subpolar and subtropical biomes over these basins. Our approach thus provides a framework that can facilitate the monitoring of the impacts of climate change on the ocean carbon cycle and the evaluation of carbon cycle projections across Earth System Models.

### Authors:
Sweety Mohanty, GEOMAR Helmholtz Centre for Ocean Research Kiel, Kiel, Germany (smohanty@geomar.de)  
Lavinia Patara, GEOMAR Helmholtz Centre for Ocean Research Kiel, Kiel, Germany  
Daniyal Kazempour, University of Kiel, Germany  
Peer Kröger, University of Kiel, Germany  

## Running the Jupyter Notebooks
Install Anaconda: https://docs.anaconda.com/free/anaconda/install/index.html  
or, Install Miniconda: https://docs.anaconda.com/free/miniconda/miniconda-install/  

In a terminal, run the below commands.  

1) Build and activate the Conda environments:   
   i) Detection of carbon biomes: `conda create -n carbon_biomes_detection python=3.8.13`  
   ii) Tracking the biomes: `conda create -n carbon_biomes_tracking python=3.8.13`

3) Activate the new environment to run the code   
`conda activate carbon_biomes_detection`  
`conda activate carbon_biomes_tracking`

4) Install the dependencies: \
`pip install requirements_detection.txt`  
`pip install requirements_tracking.txt`  

5) Update the requirements.txt file if you install additional packages: \
`pip freeze > requirements.txt`

6) Run Notebooks \
   Run the .ipynb file. : `jupyter notebook`

### Detection of Biomes


### Tracking the biomes



