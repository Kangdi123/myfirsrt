# SBEN

## Requirements
The main requirements are:
- python 3.9
- torch 1.4.0 
- tqdm
- transformers == 4.1.0

## Usage
1. **Train and select the model**

python run.py --dataset=WebNLG  --train=train  --batch_size=6

python run.py --dataset=WebNLG_star  --train=train  --batch_size=6

python run.py --dataset=NYT   --train=train  --batch_size=18

python run.py --dataset=NYT_star   --train=train  --batch_size=18

2. **Evaluate on the test set**

python run.py --dataset=WebNLG --train=test

python run.py --dataset=WebNLG_star --train=test

python run.py --dataset=NYT --train=test

python run.py --dataset=NYT_star --train=test
