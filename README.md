# Setup
## Install Create Virtual Enviroment
```
python -m venv [Enviroment name]
```
## Install Pytorch
```
pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu118
```

## Install Other Library

```
pip install -r requirement.txt
```
# Download Imagenet1K
SignUp or Login at

[ImageNet1K](https://www.image-net.org)

Then Download DevToolkit and Image from ImageNet 2012 Dataset

place the files `ILSVRC2012_devkit_t12.tar.gz` and `ILSVRC2012_img_train.tar` `ILSVRC2012_img_val.tar` in `/imagenet`

# Run Script
```
python Hyneter_base_classification.py
```