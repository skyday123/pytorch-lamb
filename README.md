# Implementation of LAMB optimizer in pytorch
I implement the v5 version(2020 ICLR).
Paper: https://arxiv.org/abs/1904.00962v5 
## Install
```bash
git clone https://github.com/skyday123/pytorch-lamb
cd pytorch-lamb
pip install -e .
```
## Usage
```python
from pytorch_lamb import Lamb
optimizer = Lamb(model.parameters(), lr=1e-3, weight_decay=1e-5)
```
## Reference offically implementation in Tensorflow
```
https://github.com/tensorflow/addons/blob/master/tensorflow_addons/optimizers/lamb.py
```


