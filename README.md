# Forked FishMIP Input Explorer for Regional Ecosystem Models
This is a forked version of the Fisheries and Marine Ecosystem Model Intercomparison Project ([FishMIP](https://fishmip.org/)) created for Ocean Hack Week 2024. We are focusing on extending the shiny app functionality, and doing some beautifying 😍

The main goal of FishMIP is to better understand and project the long-term impacts of climate change on fisheries and marine ecosystems. It is expected the findings of this group will inform the design of policies to conserve or sustainably manage marine resources.  
  
To achieve this objective, FishMIP has designed model evaluation protocols, including [Protocol 3a](https://github.com/Fish-MIP/FishMIP2.0_TrackA_ISIMIP3a), which aims to understand and reduce uncertainty associated with ecosystem models through model evaluation under historical climate and fishing effort forcings. Protocol 3a was originally developed for global ecosystem models. However, due to the increasing number of regional models, Protocol 3a bas been adapted to meet the unique needs of regional modelers. The publication describing the regional adaption is being led by [Kelly Ortega-Cisneros](https://orcid.org/0000-0003-2511-5448) and its title is **An Integrated Global-to-Regional Scale Workflow for Simulating Climate Change Impacts on Marine Ecosystems**. This work is being reviewed and it is available as a [pre-print](http://dx.doi.org/10.22541/essoar.171587234.44707846/v1).  

This repository contains all code developed to produce the shiny app supporting this publication. The shiny app is designed to allow regional modelers to explore all environmental outputs available in the GFDL-MOM6-COBALT2 model used to forced ecosystem models under Protocol 3a. 

The [FishMIP Input Explorer Shiny app](https://rstudio.global-ecosystem-model.cloud.edu.au/shiny/FishMIP_Input_Explorer/) is still in developing. Currently, it allows users to select a FishMIP ecosystem model and an environmental variable of interest. Users will see a map of the climatological mean (1961-2010) for the selected variable within the boundaries of the region of interest. It will also a line plot showing the monthly weighted mean (by grid cell area) for the variable of interest. There is also a **Download** button that allows user to download the data used to create these plots.  
  