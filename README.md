# Identifying Frost on Mars from High-Resolution Images using Computer Vision

### HiRISE
The High Resolution Imaging Experiment is known as HIRISE. The big and powerful HIRISE camera takes pictures that cover vast areas of Martian terrain while being able to see features as small as a kitchen table.

### Methodology

- Convolutional Neural Networks: CNNs are a deep learning architecture that use specialized layers to automatically learn features from images.
- Base CNN + MLP: Simple neural network consisting of 3 layers of convolutions + 1 layer of multi-layered perceptron
- Transfer learning using:
  - EfficientNetB0
  - RESNET50
  - VGG16
- Best f1-score: EfficientNetB0
  - Reason: SOTA
- Best efficiency: EfficientNetB0
  - Smallest size and fastest training
