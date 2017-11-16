# Apply Cutout to Shake-Shake Regularization Networks

1. Follow Usage instruction 1 from [https://github.com/xgastaldi/shake-shake] to install fb.resnet.torch and related libraries.
2. Navigate to the fb.resnet.torch/datasets folder.
3. Copy the files from this folder (shake-shake) and paste them into the datasets folder. This should overwrite cifar10.lua, cifar100.lua, and transforms.lua.
4. Continue following remaining instructions from [https://github.com/xgastaldi/shake-shake]. CIFAR-10 should now train using cutout with a length of 16 and CIFAR-100 will train with a length of 8.