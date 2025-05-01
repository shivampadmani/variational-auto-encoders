# 🧠 Variational Autoencoders and Beyond — A Collection of Experiments

This repository contains a structured set of **autoencoder-based generative modeling experiments**, focusing on **Variational Autoencoders (VAEs)** and their extensions. These implementations were part of my coursework and personal exploration into **representation learning**, particularly with real-world datasets such as animal images.

> 🔍 From Vanilla VAE to Beta-VAE, Adversarial Autoencoders, and Vector Quantized VAEs — this collection serves as both an educational resource and an experimentation ground for researchers and students.

---

## 📁 Repository Contents

```bash
vae-experiments/
│
├── 1_VanilaVAE_Animals.ipynb               # Basic VAE with MSE loss on animal image dataset
├── 2_CNN_classifier.ipynb                  # CNN classifier to evaluate learned representations
├── 3_MLP_classification.ipynb              # MLP-based classification from latent space
├── 4_Beta_VAE_animals.ipynb                # β-VAE implementation with adjustable disentanglement
├── 5_interpolated_latents.ipynb            # Linear interpolation between latent representations
├── 6_adverserial_autoencoders.ipynb        # AAE with discriminator in latent space
├── 7_VQVAE_EMA_res_final.ipynb             # Vector Quantized VAE with Exponential Moving Average
├── 8_gaussian_mixture_model.ipynb          # GMM on latent embeddings to cluster classes
└── README.md                               # You’re here!
```
🌟 Highlights
🧬 Core VAE Variants
Vanilla VAE: Classic encoder-decoder architecture with KL divergence + MSE loss.

Beta-VAE: Introduces a β-weight to encourage disentangled latent representations.

Adversarial Autoencoder: Combines VAE with adversarial training for structured latent space.

VQ-VAE with EMA: Discrete latent variable model using vector quantization with EMA updates.

🧪 Auxiliary Experiments
CNN and MLP Classifiers: Evaluate the quality of learned representations by training downstream classifiers.

Latent Interpolation: Explore the semantic continuity in learned latent space.

Gaussian Mixture Modeling: Model the latent embeddings for unsupervised clustering.

🚀 Getting Started
Clone the repository
```bash
git clone https://github.com/yourusername/vae-experiments.git
cd vae-experiments
```
(Optional) Install dependencies
```bash

pip install torch torchvision matplotlib seaborn scikit-learn numpy
```
Launch notebooks
```bash
jupyter notebook
```
Or Run in Google Colab

📖 Recommended Reading
Auto-Encoding Variational Bayes (Kingma & Welling, 2013)

Beta-VAE (Higgins et al., 2017)

Adversarial Autoencoders (Makhzani et al., 2015)

VQ-VAE (Oord et al., 2017)

📬 Contact
Open an issue for questions, suggestions, or discussions.

Connect on LinkedIn for collaborations.

Let’s decode the latent dimensions of intelligence — one VAE at a time.
