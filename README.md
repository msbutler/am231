## Large Scale Computer Vision for Flood Disaster Management

Contributors: Michael Butler, Preston Ching, M. Elaine Cunha

To run the full model, type `python run.py` into your command line. This assumes you're running the pipeline in an environment with tensorflow v1. Detailed Replication instructions to run on AWS in Replication.md. 

Directory
 - Train/: folder with subdirectories for labeled and unlabeled training data
 - Figures/: folder containing results from performance tests
 - Old/: folder containing out-of-date versions of files
 - architecture.py: defines CNN architecture
 - config.py: configures data parameters (i.e., image resize dimensions)
 - run.py: trains one instance of the supervised or semisupervised model
 - utils.py: contains functions for image analysis and developing training/testing sets
 - semisupervised.py: specifies training methodology for the semisupervised model
 - supervised.py: specifies training methodology for the fully supervised model