# SkimCode

Code for analysis of skimming. Will NOT go online. The online version is a bit different.
Instructions:
cmsrel CMSSW_10_2_1
cd CMSSW_10_2_1/src
cmsenv
git clone https://github.com/gkaratha/SkimCode
scram b -j 8

To run:
in python folder there is ConfFile_cfg.py. Every cut in the code can be parametrized from there.
Cuts are categorized according to object we are dealing with (mu,track,pairs...).
In this version there is the possibility of evaluating MVA output from RECO.
Runs on RECO/AOD with cmsRun
