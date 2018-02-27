# deepquant
Deep learning on company fundamental data for long-term investing

## Installation and Setup
Create a virtual environment

`virtualenv env`

Activate that virtual environment

`source activate env`

Install prerequisites:

`pip install -r requirements.txt`

or, for python3:

`pip3 install -r requirements.txt`

Please also add DEEP\_QUANT\_ROOT to your environment:

`export DEEP_QUANT_ROOT="/path/to/deep-quant/in/your/machine"`

## Running the System Test

`python scripts/deep_quant.py --config=config/system_test.conf --train=True`

or, for python3:

`python3 scripts/deep_quant.py --config=config/system_test.conf --train=True`
