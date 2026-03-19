# 🧠 GAN Lab - Image Generation using Generator & Discriminator

## 📌 Overview

This project demonstrates the implementation of a **Generative Adversarial Network (GAN)** to generate images from random noise.

The lab covers:

* Generator model
* Discriminator model
* GAN training process
* Latent space interpolation
* Pretrained GAN (PGAN)

---

## ⚙️ Technologies Used

* Python
* TensorFlow / PyTorch
* NumPy
* Matplotlib

---

## 🔄 Workflow

1. Load and preprocess CIFAR-10 dataset
2. Build Generator (noise → image)
3. Build Discriminator (image → real/fake)
4. Train GAN (adversarial learning)
5. Generate fake images
6. Perform latent space interpolation
7. Use pretrained GAN for high-quality images

---

## 🧪 Key Concepts

* Adversarial Training
* Latent Space Representation
* Image Generation using Noise
* ConvTranspose2D (Upsampling)

---

## 📊 Results

* Successfully generated images from random noise
* Observed smooth transitions using interpolation
* Compared basic GAN vs pretrained GAN outputs

---

## 🚀 How to Run

```bash
pip install -r requirements.txt
jupyter notebook
```

---

## 📌 Conclusion

This lab demonstrates how GANs learn through competition between Generator and Discriminator, leading to realistic image generation.

---

## 👤 Author

Aditya Singh
