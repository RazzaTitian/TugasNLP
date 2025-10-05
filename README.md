# Tugas NLP

## 🚀 Cara Menjalankan Menggunakan Notebook Google Colab

Buka file, jalankan:

* **Cell 1–2** → komponen utama
* **Cell 3 (opsional)** → visualisasi *attention*


## 🧩 Komponen yang Diimplementasikan

* Token Embedding
* Positional Encoding (default: sinusoidal; bonus: RoPE)
* Scaled Dot-Product Attention
* Multi-Head Attention
* Feed-Forward Network (2-layer MLP + GELU)
* Residual Connection + LayerNorm (pre-norm)
* Causal Masking (decoder-only)
* Output Projection + Next-Token Softmax
* (**Bonus**) Weight Tying & Attention Visualization
