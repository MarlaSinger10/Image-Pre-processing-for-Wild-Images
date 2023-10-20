# Image-Pre-Processing-for-Wild-Images
Camera Traps (or Wild Cams) enable the automatic collection of large quantities of image data. Biologists all over the world use camera traps to monitor biodiversity and population density of animal species. We have recently been making strides towards automating the species classification challenge in camera traps, but as we try to expand the scope of these models from specific regions where we have collected training data to nearby areas we are faced with an interesting probem: how do you classify a species in a new region that you may not have seen in previous training data?
In order to tackle this problem, we have prepared a challenge where the training data and test data are from different regions, namely The American Southwest and the American Northwest. The species seen in each region overlap, but are not identical, and the challenge is to classify the test species correctly. To this end, we will allow training on our American Southwest data (from CaltechCameraTraps), on iNaturalist 2017/2018 data, and on simulated data generated from Microsoft AirSim. We have provided a taxonomy file mapping our classes into the iNat taxonomy.
This is an FGVCx competition as part of the FGVC6 workshop at CVPR 2019, and is sponsored by Microsoft AI for Earth. There is a github page for the competition here. Please open an issue if you have questions or problems with the dataset.
If you use this dataset in publication, please cite:

@article{beery2019iwildcam,
 title={The iWildCam 2019 Challenge Dataset},
 author={Beery, Sara and Morris, Dan and Perona, Pietro},
 journal={arXiv preprint arXiv:1907.07617},
 year={2019}
}
Kaggle is excited to partner with research groups to push forward the frontier of machine learning. Research competitions make use of Kaggle's platform and experience, but are largely organized by the research group's data science team. Any questions or concerns regarding the competition data, quality, or topic will be addressed by them.
