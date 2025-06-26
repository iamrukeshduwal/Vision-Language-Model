# Vision-Language Model (VLM) Bootcamp 🚀

This repository explores cutting-edge Vision-Language Models (VLMs) like **Qwen 2.5-VL** and **CLIP**. Through Jupyter notebooks, we perform tasks such as embedding generation, zero-shot classification, image captioning, and object detection—all without task-specific fine-tuning.

---

## 🧠 Key Topics Covered

- 🧩 Visual Embeddings using CLIP
- 🎯 Zero-Shot Classification (CLIP)
- 🖼️ Image Captioning using Qwen 2.5-VL
- 🔎 Object Detection with Qwen-VL
- 🧪 Prompt Engineering for VLMs

---

## 📁 Notebooks

| File                                       | Description                                 |
|--------------------------------------------|---------------------------------------------|
| `m0_Setup.ipynb`                           | Environment setup and model installation    |
| `m2_Embeddings.ipynb`                      | CLIP-based image and text embedding         |
| `m3_Zero-Shot-Classification-CLIP.ipynb`   | CLIP-based zero-shot classification         |
| `m5_Image-Captioning.ipynb`                | Image captioning using Qwen 2.5-VL          |
| `m6_Object-Detection-Using-Qwen-2.5VL.ipynb`| Object detection and VQA-style interaction  |

---

## ⚙️ Installation

Make sure you have:
- Python 3.8+
- CUDA-enabled GPU
- PyTorch with CUDA support

### 📦 Install dependencies:
```bash
pip install torch torchvision transformers accelerate
pip install git+https://github.com/huggingface/transformers
pip install ipywidgets matplotlib tqdm
