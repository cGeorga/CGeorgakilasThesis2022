Vit-implementation based on [this](https://github.com/tahmid0007/VisionTransformer) repository.
Mainly Changing the training process and hyperparameters, adding early stopping and lr scheduling.

Training the model from scratch on Cifar-100 with and without data augmentation.

Best results on validation set without data augmentation:
Average test loss: 1.8837  Accuracy top 1%: 5332/10000 (53.32%)

Best results on validation set with data augmentation:
Average test loss: 1.7794 Accuracy top 1%: 5344/10000 (53.44%)