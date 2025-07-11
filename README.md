# 🧠 Neural Body – Novel View Synthesis Using Structured Latent Codes

This project explores a deep learning approach for reconstructing 3D human bodies using limited camera views. It uses implicit neural representations and structured latent codes anchored to a deformable mesh.

## 📌 Overview
- Implemented pretrained models from the [NeuralBody GitHub Repo](https://github.com/zju3dv/NeuralBody)
- Conducted inference and visualization using ZJU-MoCap and People Snapshot datasets
- Tackled real-world issues in AI model deployment on Colab and local environments

## 🛠️ Tech Stack
- Python, PyTorch, CUDA
- Google Colab
- tqdm, spconv

## 🧪 My Contributions
- Set up environment and resolved CUDA, Torch, and spconv compatibility issues
- Worked with image conversion pipelines (JPG <--> PNG)
- Debugged visualization and inference pipelines with missing assets
- Collaborated with original repo author to obtain working pretrained models

## 🔍 Key Learnings
- Neural field representations & deformable mesh modeling
- Real-world ML reproducibility challenges
- GPU compatibility and Torch versioning issues


 Neural Body – Dynamic Human View Synthesis
Stack: Python, PyTorch, CUDA, Google Colab, spconv
Summary:
Evaluated a deep learning system for 3D human visualization from sparse camera views using structured latent codes. Debugged compatibility issues and adapted the inference and rendering pipelines.
Features:

Ran pretrained model inference on ZJU Mocap & People Snapshot datasets

Resolved environment issues (Torch/CUDA/spconv) on Colab

Rendered novel views using deformable neural mesh representations
🔗 GitHub – Neural Body
