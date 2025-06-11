# Variational-Auto-Encoder
This project builds a Variational Autoencoder (VAE) using PyTorch to learn and generate handwritten digit pairs by combining two MNIST digits side-by-side. The model captures the joint representation of digit pairs in a latent space and reconstructs them accurately.
## Dataset

- Base: [MNIST handwritten digits dataset](http://yann.lecun.com/exdb/mnist/)
- Customization:
  - Two images are combined horizontally into one 28x56 image.
  - Labels are encoded as two-digit integers (e.g., 3 and 7 → 37).
 
