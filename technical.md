[Home](index.md) • [Technical Approach](technical.md) • [Results](results.md) • [Takeaways](takeaways.md)

# Technical Approach: Using AlexNet for Wet-Road Detection

ZeroSkid uses the AlexNet deep convolutional neural network to classify road conditions as dry or wet. AlexNet’s convolutional layers detect textures, reflections, and edges that indicate slippery pavement.

## Architecture Summary
- 5 convolutional layers  
- 3 fully connected layers  
- ReLU activation  
- Max pooling  
- Softmax output  
