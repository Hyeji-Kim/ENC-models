# Compressed networks from ENC (Caffe model)

Fine-tuned network models by ["Efficient Neural Network Compression"](https://arxiv.org/abs/1811.12781), CVPR 2019.

For the source-code of paper, please refer to [[ENC]](https://github.com/Hyeji-Kim/ENC)

* This repository contains the prototxt files
* Trained models: [[driver]](https://www.amazon.com/clouddrive/share/hZpteJRlZbUGF12csmF304mka3pDAUYu6eVFRUyrEIS)



## AlexNet with ImageNet

* Table 1

|  Method | FLOPs | Weights |Top-1 Acc.| Top-5 Acc.|
|---------|-----------|------------|-----------|----------|
|[[ENC-Inf]](https://www.amazon.com/clouddrive/share/hZpteJRlZbUGF12csmF304mka3pDAUYu6eVFRUyrEIS/folder/FCDYCZdaSq2VbJTKYqcnDg?_encoding=UTF8&*Version*=1&*entries*=0&mgh=1)| 37.5% | 18.0% | 56.74%|80.14%|
|[[ENC-Model]](https://www.amazon.com/clouddrive/share/hZpteJRlZbUGF12csmF304mka3pDAUYu6eVFRUyrEIS/folder/_AcsXPoSTBuYP7Tnk0MNhQ?_encoding=UTF8&*Version*=1&*entries*=0&mgh=1)| 37.5% | 18.0% |56.71%|80.13%|

* Table 3

|  Method |  FLOPs |Top-1 Acc.| Top-5 Acc.|
|-----------|----------|-----------|-----------|
|[[ENC-Inf]](https://www.amazon.com/clouddrive/share/hZpteJRlZbUGF12csmF304mka3pDAUYu6eVFRUyrEIS/folder/LqzT61Z2Rn2b_VjqAkuM3w?_encoding=UTF8&*Version*=1&*entries*=0&mgh=1)| 31%  |56.66%|79.74%|



* Fig.7(a) - prototxt

|  Method | FLOPs | Top-1 Acc.| Top-5 Acc.|
|-----------|----------|-----------|-----------|
|[[ENC-Inf]](https://github.com/Hyeji-Kim/ENC-models/tree/master/models/table3/alex_flop_0.31)| 31% |56.66%|79.74%|
|[[ENC-Inf]](https://github.com/Hyeji-Kim/ENC-models/blob/master/models/fig7_a/alex_c_0.5.prototxt)| 50% | 57.33%|80.33%|
|[[ENC-Inf]](https://github.com/Hyeji-Kim/ENC-models/blob/master/models/fig7_a/alex_c_0.75.prototxt)| 75% | 57.67%|80.50%|
|[[ENC-Inf]](https://github.com/Hyeji-Kim/ENC-models/blob/master/models/fig7_a/alex_c_0.95.prototxt)| 95% | 57.74%|80.57%|

* Fig.7(b) - prototxt

|  Method | FLOPs | Weights | Top-1 Acc.| Top-5 Acc.|
|-----------|----------|-----------|-----------|-----------|
|[[ENC-Model]](https://github.com/Hyeji-Kim/ENC-models/blob/master/models/fig7_b/alex_c_0.228_w_0.18.prototxt)| 23% | 18% |54.48%|78.58%|
|[[ENC-Model]](https://github.com/Hyeji-Kim/ENC-models/blob/master/models/fig7_b/alex_c_0.25_w_0.18.prototxt)| 25% | 18% | 55.08%|78.99%|
|[[ENC-Model]](https://github.com/Hyeji-Kim/ENC-models/blob/master/models/fig7_b/alex_c_0.3_w_0.18.prototxt)| 30% | 18% | 56.12%|79.59%|



## VGG-16 with ImageNet

* Table 1

|  Method | FLOPs  |Top-1 Acc.| Top-5 Acc.|
|-----------|----------|-----------|-----------|
|[[ENC-Inf]](https://www.amazon.com/clouddrive/share/hZpteJRlZbUGF12csmF304mka3pDAUYu6eVFRUyrEIS/folder/UVJCn_F1TcKzIKxn5aPpmQ?_encoding=UTF8&*Version*=1&*entries*=0&mgh=1)| 25%|71.29%|90.12%|
|[[ENC-Model]](https://www.amazon.com/clouddrive/share/hZpteJRlZbUGF12csmF304mka3pDAUYu6eVFRUyrEIS/folder/sprWpFirTBS3BqzTaukjFw?_encoding=UTF8&*Version*=1&*entries*=0&mgh=1)| 25%|71.25%|90.12%|
|[[ENC-Map]](https://www.amazon.com/clouddrive/share/hZpteJRlZbUGF12csmF304mka3pDAUYu6eVFRUyrEIS/folder/Ue4mMSyqQsWYdrdnZu7PUQ?_encoding=UTF8&*Version*=1&*entries*=0&mgh=1)| 25%|70.90%|89.97%|

* Table 2

| Method |  FLOPs |Top-1 Acc.| Top-5 Acc.|
|-----------|----------|-----------|-----------|
|[[ENC-Model]](https://www.amazon.com/clouddrive/share/hZpteJRlZbUGF12csmF304mka3pDAUYu6eVFRUyrEIS/folder/bhesTAc6QQ2xEQiikM3eSw?_encoding=UTF8&*Version*=1&*entries*=0&mgh=1)|  20%|71.06%|89.95%|


* Table 3

|  Method | FLOPs  |Top-1 Acc.| Top-5 Acc.|
|-----------|----------|-----------|-----------|
|[[ENC-Model]](https://www.amazon.com/clouddrive/share/hZpteJRlZbUGF12csmF304mka3pDAUYu6eVFRUyrEIS/folder/uXmvkY9hR0-MeP3bbjSu_w?_encoding=UTF8&*Version*=1&*entries*=0&mgh=1)| 24%|70.95%|89.95%|


## ResNet-56 with Cifar10

* Table 1

|  Method | FLOPs  |Top-1 Acc. w/o FT |Top-1 Acc. w/ FT | 
|-----------|----------|-----------|-----------|
|[[ENC-Inf]](https://www.amazon.com/clouddrive/share/hZpteJRlZbUGF12csmF304mka3pDAUYu6eVFRUyrEIS/folder/aFJ2DjTUQPKAyGGM1K4BIg?_encoding=UTF8&*Version*=1&*entries*=0&mgh=1)| 50%|90.22%|93.0%|
|[[ENC-Model]](https://www.amazon.com/clouddrive/share/hZpteJRlZbUGF12csmF304mka3pDAUYu6eVFRUyrEIS/folder/355OtWHGTHapgxbOx7dR8w?_encoding=UTF8&*Version*=1&*entries*=0&mgh=1)| 50%|89.55%|93.0%|
|[[ENC-Map]](https://www.amazon.com/clouddrive/share/hZpteJRlZbUGF12csmF304mka3pDAUYu6eVFRUyrEIS/folder/T-_u2zqiS2qNHqt4SmoUDg?_encoding=UTF8&*Version*=1&*entries*=0&mgh=1)| 50%|89.80%|93.0%|


* Table 3

|  Method | FLOPs  |Top-1 Acc.|
|-----------|----------|-----------|
|[[ENC-Map]](https://www.amazon.com/clouddrive/share/hZpteJRlZbUGF12csmF304mka3pDAUYu6eVFRUyrEIS/folder/aiUUAovnRoWvJHgn84f5rw?_encoding=UTF8&*Version*=1&*entries*=0&mgh=1)| 55%|93.2%|



## Citation
```
@CONFERENCE{ENC_CVPR19,
  author={Hyeji Kim, Muhammad Umar Karim Khan, Chong-Min Kyung},
  title={Efficient Neural Network Compression},
  booktitle={CVPR},
  month = {June},
  year = {2019},
}
```
