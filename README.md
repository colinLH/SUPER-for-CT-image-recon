# SUPER-for-CT-recon
## Install MIRT toolbox ############
get the IRT https://web.eecs.umich.edu/~fessler/code/ unzip in to ./irt (the root folder of this project).
## Install MatConvNet #############
http://www.vlfeat.org/matconvnet/install/#compiling and http://www.vlfeat.org/matconvnet/install/, install to the root folder of this project.
## trained models 
Trained models are included in the root folder "trained_model".
## Code: SUPER with WavResNet #############
folder "super_wavresnet":
1. SUPER-WRN-EP:
- train: main_train_wrsEP_l2normReg_6pat_nufft.m
- test: test_mytrain_mayo_wavEP_l2normReg_nufft.m
2. SUPER-WRN-ULTRA:
- train: main_train_wrsULTRA_6pat_nufft.m
- test: test_mytrain_mayo_wavULTRA_l2normReg_nufft.m
3. standalone WavResNet and Sequential Supervised Networks:
- train: main_train_wrs_6pat_nufft.m
- test: test_mytrain_rnn_mayo_nufft.m 


## Code: SUPER with FBPConvNet ##########
folder "super_fbpconvnet":
1. SUPER-FCN-EP:
- train: main_train_fbpconvnetep.m
- test:  evaluation_fbpconvnetep.m
2. SUPER-FCN-ULTRA:
- train: main_train_fbpconvnetultra.m
- test:  evaluation_fbpconvnetultra.m
3. Sequential fbpconvnet:
- train: main_train_successivefcn.m
- test:  evaluation_successivefcn.m
4. SUPER-FCN-DataTermOnly:
- train: main_train_fbpconvnetnoreg.m
- test:  evaluation_fbpconvnet_dataterm.m


 
