# Paper rater uncertainty
This repository contains configuration used with ivadomed `automate_training`. Documentation available [here](https://ivadomed.org/en/latest/scripts.html#ivadomed.scripts.automate_training.automate_training). `config*.json` contain all static parameters for training and evaluation of models, whereas `params*.json` contain parameters over which `automate_training` will iterate (i.e. to train a model for each rater/consensus)

Example command :

`python3 ivadomed/scripts/automate_training.py -c ivadomed/config/config_ms_brain_auto.json --run-test -p params_ms_brain.json`
