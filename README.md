# Tutorial_IWF-ICMEs
## "Machine Learning Pipeline for Automated Detection of ICMEs "

The work package "Machine Learning Solutions for Data Analysis and Exploitation in Planetary Science" within Europlanet 2024 Research Infrastructure will develop machine learning (ML) powered data analysis and exploitation tools optimized for planetary science. <br>
In this tutorial, we will introduce a ML pipeline for the automated detection of interplanetary coronal mass ejections (ICMEs) in solar wind time series data. We will guide the reader through the developed ML code with the help of a sample data set of solar wind time series data from different spacecraft. (WIND, STEREO-A and STEREO-B) <br>

Europlanet 2024 RI has received funding from the European Union’s Horizon 2020 research and innovation programme under grant agreement No 871149. <br><br>

We propose a pipeline using a UNet including residual blocks, squeeze and excitation blocks, Atrous Spatial Pyramidal Pooling (ASPP) and attention blocks, similar to the [ResUNet++](https://arxiv.org/pdf/1911.07067.pdf), for the automatic detection of ICMEs. The original model was used for medical image segmentation, while we are dealing with time series and therefore face a slightly different use case. <br> <br>

### Installation Guide

This pipeline runs on Python 3.6 <br> <br>

git clone https://github.com/epn-ml/Tutorial_IWF-ICMEs.git  <br>
python -m venv wsenv <br>
source wsenv/bin/activate <br>
cd Tutorial_IWF-ICMEs <br>
pip install -r requirements.txt <br>
ipython kernel install --user --name=wsenv <br>
jupyter lab <br> <br>
