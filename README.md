# DarkMachines
Code used for tests on DarkMachines samples:
* Test parsing.ipynb: code to parse DarkMachine format and save events corresponding to a given selection
* TestAutoEncoder_pytorch-hack_chan1.ipynb: run simple AutoEncoder on samples extracted from chan1 data
* Significance.ipynb: calculate significance increase vs cut on AE output

## About DarkMachines

Samples
* LHC simulated datasets from the https://darkmachines.org/ website: https://zenodo.org/record/3685861#.YLSWIBE6_mF
(local disk: /AtlasDisk/user/donini/ATLAS/DarkMachines)

* Hackathon dataset from https://www.phenomldata.org/: https://zenodo.org/record/3961917#.YLSR1RE6_mE

* Secret dataset: https://zenodo.org/record/4443151#.YLSSHRE6_mE

The description of the samples:
* original description is given section 23 (p194+) of the Les Houches 2019 paper: https://arxiv.org/abs/2002.12220
* Hackathon dataset: https://zenodo.org/record/3961917#.YLSR1RE6_mE

Details about the generation:
* generation cards (see Delphes for object selection): https://github.com/melli1992/unsupervised_darkmachines
* generated processes: https://docs.google.com/document/d/1N1yetfbXXnAqNb1CIT-ajIKh1EQW2GB8N4Z9HrMAREQ/edit

Symbol ids: j, b, e-, e+, m-, m+, g

Data format: event ID; process ID; event weight; MET; METphi; obj1, E1, pt1, eta1,phi1; obj2, E2, pt2, eta2, phi2;...

Energies are in MeV

Paper:
* https://arxiv.org/abs/2105.14027

Results:
* https://github.com/bostdiek/DarkMachines-UnsupervisedChallenge

