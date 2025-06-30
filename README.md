# 🌀 Swin Transformer

This project implements the **Swin Transformer** architecture for image classification, with experiments on both **CIFAR-10** and **CIFAR-100** datasets.

---

### 🚀 Key Highlights

- 🔲 **Shifted Window Attention**: Efficient local attention mechanism for better scalability  
- 🧠 **Hierarchical Feature Extraction**: Patch merging strategy captures multiscale information  
- 🎯 **Relative Positional Embedding**: Adds spatial context to patch tokens  
- 🔁 **Data Augmentation**: Applied `RandAugment` to boost generalization  
- ⚙️ **Training Pipeline**: Integrated **checkpointing** and **AMP** (automatic mixed precision) for speed and stability  
- 📊 **Comparison**: Benchmarked against Vision Transformer (ViT) and traditional CNNs

---

### 🧪 Results

Our experiments showed that Swin Transformer:
- ✅ Outperforms traditional CNNs on CIFAR-10
- ⚖️ Matches or exceeds ViT performance on CIFAR-100
- 📈 Scales well even with small datasets, maintaining accuracy

---

### 🧰 Tech Stack

- `PyTorch`
- `RandAugment`
- `AMP (torch.cuda.amp)`
- `Matplotlib`, `Seaborn` for visualization
- `Weights & Biases` or `TensorBoard` (optional for logging)

---

### 🖼 Sample Result

- `Check PPTX for the results`

