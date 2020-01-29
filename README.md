# DeepLabV3_PyTorch
Inference python code for the official DeepLabV3 using PyTorch Hub

## Table of contents
1. [Development environments](#dev_env)
2. [Installation](#installation)
3. [Usages](#usage)

## Development environments <a name="dev_env"></a>
* Coding language: Python3
* PyTorch version: .1.4.0
* Torchvision version: 0.5.0 

## Installation <a name="installation"></a>
```bash
usrname@hostname:~/curr_path$ pip3 install -r requirements.txt
```

## Usages <a name="usage"></a>
```bash
usrname@hostname:~/curr_path$ python3 ./main_inference.py --path_img ./test_images/img_input.jpg --cuda True
```
