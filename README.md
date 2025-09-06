# Pet Classification with CNNs 🐶 🐱

This project was developed as part of the *Image Processing and Computer Vision* exam using **PyTorch**.  
The task was to classify pets from the [Oxford-IIIT Pet Dataset](https://www.robots.ox.ac.uk/~vgg/data/pets/) with two different approaches:  

---

## 📌 Project Overview  

1. **CNN from Scratch (PyTorch)**  
   - Designed and implemented a deep convolutional neural network inspired by **ResNet-v2**.  
   - Conducted an **ablation study** by testing different architectural choices (e.g., skip connections, depth, number of filters) to analyze their impact on performance.  
   - Training from scratch provided useful insights into how each component contributed to model accuracy and generalization.  


2. **Transfer Learning with ResNet (PyTorch)**  
   - Fine-tuned a pretrained **ResNet (ImageNet weights)**.  
   - Pretrained layers already extracted strong general features (edges, textures, shapes).  
   - Adapted the top layers to classify pet breeds.  
   - Achieved **~90% accuracy**, showing how pretrained weights were already highly effective and that fine-tuning outperformed training from scratch.  

---

