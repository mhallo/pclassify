# Visual Classifier

As part of taking the fast.ai course, I have fine tuned a model on top of `resnet18` to identify the difference between a
2020 BMW M3 and a 2020 Porsche 911.

With some of the configurations set I have achieved at least a baseline accuracy of 93%.

Later on I'll add a nice Gradio interface to deploy the model such that it's easier to interface with the model.

Further experiments with more images and more augmentations to the image may yield some other results, but this is a good baseline for learning more on PyTorch
and also how to setup CUDA with my environment for training (RTX 4090 + i9-13900k)

I'm pleased with how it came out so far and I plan to continue my studies and projects on RNN's (now that my CUDA environment is setup :) ) 