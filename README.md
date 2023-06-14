# testMarkdown

## CNN Layer Architecture

Below is an example architecture for a TensorFlow CNN model:

### Input Layer

- Input Shape: (batch_size, height, width, channels)
- Number of Parameters: 0 (no learnable parameters in the input layer)

### Convolutional Layer 1

- Filter Size: (3, 3)
- Number of Filters: 32
- Stride: (1, 1)
- Padding: 'same'
- Activation: ReLU
- Output Shape: (batch_size, height, width, 32)

### Max Pooling Layer 1

- Pool Size: (2, 2)
- Stride: (2, 2)
- Output Shape: (batch_size, height/2, width/2, 32)

### Convolutional Layer 2

- Filter Size: (3, 3)
- Number of Filters: 64
- Stride: (1, 1)
- Padding: 'same'
- Activation: ReLU
- Output Shape: (batch_size, height/2, width/2, 64)

### Max Pooling Layer 2

- Pool Size: (2, 2)
- Stride: (2, 2)
- Output Shape: (batch_size, height/4, width/4, 64)

### Flatten Layer

- Output Shape: (batch_size, height/4 * width/4 * 64)

### Fully Connected Layer 1

- Number of Neurons: 128
- Activation: ReLU
- Output Shape: (batch_size, 128)

### Fully Connected Layer 2 (Output Layer)

- Number of Neurons: num_classes (depends on the classification task)
- Activation: Softmax (for multi-class classification)
- Output Shape: (batch_size, num_classes)

Note: This is just an example architecture and the actual architecture may vary depending on the specific problem and requirements.
