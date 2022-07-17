# MNIST digit recognition from scratch using numpy

Idea from [this great video](https://www.youtube.com/watch?v=w8yWXqWQYmU)

3 Layers neural network:
1. Input layer: 784 nodes, one for each pixel of 28x28 images
2. Hidden layer: 10 nodes, [ReLU](https://en.wikipedia.org/wiki/Rectifier_(neural_networks)) activation function
3. Output layer: 10 nodes, one for each digit from 0 to 9, [Softmax](https://en.wikipedia.org/wiki/Softmax_function) activation function
    
![mnist](https://user-images.githubusercontent.com/33452668/179417056-2e210b46-5251-47f0-bc48-302628b771ec.png)
