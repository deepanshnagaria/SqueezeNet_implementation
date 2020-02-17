# SqueezeNet_implementation
Recent research on deep convolutional neural networks (CNNs) has focused primarily on improving accuracy. For a given accuracy level, it is typically possible to identify multiple CNN architectures that achieve that accuracy level. With
equivalent accuracy, smaller CNN architectures offer at least three advantages: 
(1) Smaller CNNs require less communication across servers during distributed training. 
(2) Smaller CNNs require less bandwidth to export a new model from the cloud to an autonomous car. 
(3) Smaller CNNs are more feasible to deploy on FPGAs and other hardware with limited memory. To provide all of these advantages, a small CNN architecture called SqueezeNet was proposed. 
SqueezeNet achieves AlexNet-level accuracy on ImageNet with 50x fewer parameters. Additionally, with model compression techniques, we are able to compress SqueezeNet to less than 0.5MB (510× smaller than AlexNet).
