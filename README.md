# SingleTerrainGAN
SingleTerrainGAN is a GAN that can generate terrains following two datasets fetched from studies by [Beckham and Pal (2017)](http://arxiv.org/abs/1707.03383) and [Panagiotou and Charou (2020)](http://arxiv.org/abs/2010.06411). SingleTerrainGAN is a GAN trained for the research "Improving procedural terrain generation using a single deep learning model".

## What's in this repository?
This repository includes the following files/directories:
* **Notebooks/Gan-heightmaps-recreation.ipynb** - Python notebook that contains a recreation of the GAN developed by [Beckham and Pal](http://arxiv.org/abs/1707.03383) in TensorFlow.
* **Thesis.pdf** - Full thesis of the research.
* **Survey data.csv** - Data obtained from a survey carried out for the research.
* **Survey models** - 3D models used for the survey

## How to generate your own terrains
To generate your own generates, you will first have to downloaded the trained model in [this Google Drive folder](https://drive.google.com/drive/folders/1Ezig2YLXDP_mh9vMjX4-CFvMrx9qTLGS?usp=sharing). This folder includes two different models for SingleterrainGAN: "SingleTerrainGAN_desert.pkl" and "SingleTerrainGAN_Greece.pkl". You can download a model according to the type of terrain (desert/Greece) you would like to generate. You can then use this .pkl file to generate terrains using the code in the [stylegan2-fun](https://github.com/PDillis/stylegan2-fun) repository by Diego Porres.