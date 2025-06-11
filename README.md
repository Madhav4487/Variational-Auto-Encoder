# Variational-Auto-Encoder
This project builds a Variational Autoencoder (VAE) using PyTorch to learn and generate handwritten digit pairs by combining two MNIST digits side-by-side. The model captures the joint representation of digit pairs in a latent space and reconstructs them accurately.
## Dataset

- Base: [MNIST handwritten digits dataset](http://yann.lecun.com/exdb/mnist/)
- Customization:
  - Two images are combined horizontally into one 28x56 image.
  - Labels are encoded as two-digit integers (e.g., 3 and 7 → 37).
 
## Model Architecture

The VAE model consists of:
- **Encoder**: Flattens the 28x56 input and projects it into a 10-dimensional latent space (via mean and log variance).
- **Reparameterization Trick**: Samples a latent vector z from the learned distribution.
- **Decoder**: Reconstructs the original image from z using fully connected layers.
- **Loss**:Binary Cross-Entropy (reconstruction) + KL Divergence (regularization)

## What I Learned
- How to customize and preprocess datasets for generative models
- Implementing a VAE with encoder-decoder architecture in PyTorch
- Visualizing latent space samples and understanding learned distributions
  
## 📌 To Do / Future Work

- Use convolutional layers for better image quality
- Extend to more complex datasets like Fashion MNIST
- Explore conditional VAE to generate specific digit combinations


## 📬 Contact

**Madhav Dahal**  
📧 madhavdahal16@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/madhav-dahal-ms-9a1147b0)  
🔗 [GitHub](https://github.com/Madhav4487)
