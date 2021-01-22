# Paper rater uncertainty
This repository contains configuration files used with [ivadomed](https://github.com/ivadomed/ivadomed) `automate_training`. Documentation available [here](https://ivadomed.org/en/latest/scripts.html#ivadomed.scripts.automate_training.automate_training). 

The `config*.json` files contain all static parameters for training and evaluation of models, whereas the `params*.json` files contain parameters over which `automate_training` will iterate (i.e. to train a model for each rater/consensus). Example command to launch training/evaluation:

`python3 ivadomed/scripts/automate_training.py -c ivadomed/config/config_ms_brain_auto.json --run-test -p params_ms_brain.json`
