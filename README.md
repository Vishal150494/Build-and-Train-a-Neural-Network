# Build-and-Train-a-Neural-Network

I'll be using the Fashion-MNIST dataset, a drop-in replacement for the MNIST dataset. MNIST is actually quite trivial with neural networks where you can easily achieve better than 97% accuracy. Fashion-MNIST is a set of 28x28 greyscale images of clothes. It's more complex than MNIST, so it's a better representation of the actual performance of your network, and a better representation of datasets you'll use in the real world.

<img src='assets/fashion-mnist-sprite.png' width=500px>

## Requirements
- Python 3.8
- Pytorch 

## Steps 
- Load the datasets using `torchvision`. [Fashion-MNIST dataset](https://github.com/zalandoresearch/fashion-mnist)
- You can see one of the images like this
<img src='assets/Test_Image_Show.png' width=500px>
- Use the ReLU activations for the layers and to return the logits or log-softmax from the forward pass.
- Make a forward pass through the network to get the logits 
- Use the logits to calculate the loss
- Perform a backward pass through the network with `loss.backward()` to calculate the gradients
- Take a step with the optimizer to update the weights

## Result Summary

On running the code you should expect the output something like the following. 
<img src='assets/Results_Fashion_MNIST.png' width=500px>
