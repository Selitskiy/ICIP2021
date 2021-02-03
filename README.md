# ICIP2021
Code for paper 'Benchmarking State-of-the-art CNN Models Against the Makeup and Occlusions Face Data'

List of files:

 - Program files to re-train SOTA CNN models and train SNN:
Inception3Detail_bc2cp.m	
AlexNetDetail_bc2cp.m		
Vgg19Detail_bc2cp.m
GoogleNetDetail_bc2cp.m	
IResnet2Detail_bc2cp.m		
Resnet50Detail_bc2cp.m

To configure, find and modify the following fragment:
  %% CONFIGURATION PARAMETERS:
  % Download BookClub dataset from: https://data.mendeley.com/datasets/yfx9h649wz/2
  % and unarchive it into the dierctory below:
  %% Dataset root folder template and suffix
  dataFolderTmpl = '~/data/BC2_Sfx';
  dataFolderSfx = '1072x712';

 - Libraries:
   * Training and test sets building
createBCtestIDSvect6b1.m
createBCtestIDSvect6b.m
createBCbaselineIDS6b.m

   * Image size conversion:
readFunctionTrainGN_n.m
readFunctionTrainIN_n.m
readFunctionTrain_n.m
