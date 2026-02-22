# PneumoniaMNIST-challenge
Task Description: This task detects Pneumonia from chest X-ray images using a pretrained DenseNet121 model and generates an automated radiology-style report.
Dataset Information: Dataset: PneumoniaMNIST , Classes: Normal (0), Pneumonia (1), Image Size: 28×28 (resized to 224×224), Source: MedMNIST v2
We use DenseNet121 pretrained on ImageNet. The final classification layer is replaced to output 2 classes.
Installation Instructions: pip install medmnist timm torch torchvision tqdm
