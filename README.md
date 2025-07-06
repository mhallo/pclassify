# Visual Classifier

As part of taking the fast.ai course, I have fine tuned a model on top of `resnet18` to identify the difference between a
2020 BMW M3 and a Porsche 911.

With some of the configurations set I have achieved at least a baseline accuracy of 93%.

Further experiments with more images and more augmentations to the image may yield some other results, but this is a good baseline for learning more on PyTorch
and also how to setup CUDA with my environment for training (RTX 4090 + i9-13900k)