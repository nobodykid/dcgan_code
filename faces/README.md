Modify data_dir in lib/config.py to point to directory with faces hdf5.

*Currently this data file is not released due to size/data restrictions.* 

Run train_uncond_dcgan.py to train face model from paper. It will create a few folders and save training info, model parameters, and samples periodically. Should be ~ 12 hours/overnight.