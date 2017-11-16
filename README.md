# Cutout
Code to replicate experiments from https://arxiv.org/abs/1708.04552

To train WideResNet 28-10 on CIFAR10 with data augmentation and cutout:    
`python train.py --dataset cifar10 --model wideresnet --data_augmentation --cutout --length 16`

To train WideResNet 28-10 on CIFAR100 with data augmentation and cutout:  
`python train.py --dataset cifar100 --model wideresnet --data_augmentation --cutout --length 8`

To train WideResNet 16-8 on SVHN with cutout:  
`python train.py --dataset svhn --model wideresnet --learning_rate 0.01 --epochs 160 --cutout --length 20`
