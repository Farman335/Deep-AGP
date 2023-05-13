****** Steps to reproduce the results ******

1: Datasets folder contains training and testing datasets used by DU et al. in paper entitled "MsDBP: Exploring DNA-Binding Proteins by Integrating 
   Multiscale Sequence Information via Chou’s Five-Step Rule". 
   
2: The feature set of F-PSSM, Lead-BiPSSM, EDF-PSSM, PSSM-DPC, and EDF-PSSM-DWT are computed via https://possum.erc.monash.edu/server.jsp.
   
3: DWT can be formulated by code in "DWT files" folder.

4: "Features set" folder comprises feature set of each descriptor.

5: The best features can be computed by SFS algorithm.

6: "Best features set" consists of important features of each method. 

7: The code of machine learning classifiers i.e. LiXGB (Light eXtreme Gradient boosting), Adaboost, ERT (extremely randomized trees), and XGB (eXtreme gradient boosting) are  
   provided in ML classifier.py file. 

8: All python codes are implemented in python version 3.6.3 using Keras package with Tensorflow backend.

9: All matlab codes are simulated in matlab version R2018a.

NOTE: To run the codes of python and matlab, the above noted version are required to install in the systems.