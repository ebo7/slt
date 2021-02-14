# Sign Language Transformers
Forked from neccam.
The pipeline was modified to include OpenPose Features instead of CNN+LSTM+CNN setup used in the original repo.

## Requirements
* Download the feature files using the `data/download.sh` script.
* Install required packages using the `requirements.txt` file.

    `pip install -r requirements.txt`

## Usage
  `python -m signjoey train configs/sign.yaml` 
