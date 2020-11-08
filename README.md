# CamVid 

Data originally from http://mi.eng.cam.ac.uk/research/projects/VideoRec/CamVid/

Training-validation-test splits from https://github.com/alexgkendall/SegNet-Tutorial

There are [31+1 semantic classes](http://mi.eng.cam.ac.uk/research/projects/VideoRec/CamVid/#ClassLabels) (+1 comes from the _Void_ class).
They are usually grouped into 11+1 classes: _Sky, Buliding, Pole, Road, Sidewalk, Tree, SignSymbol, Fence, Vehicle, Pedestrian, Bicyclist, Void_.
A python class for loading the dataset with 11 classes can be found here (search for _CamVid_): https://github.com/Ivan1248/Vidlu/blob/master/vidlu/data/datasets/datasets.py
