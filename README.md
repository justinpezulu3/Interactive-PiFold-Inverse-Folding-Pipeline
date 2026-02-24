# Interactive-PiFold-Inverse-Folding-Pipeline

# 🧬 PiFold-Colab UI

An interactive, minimalist pipeline for Inverse Protein Folding using the PiFold architecture. 

### 🚀 Features
* **One-Shot Design:** Unlike autoregressive models, PiFold designs the entire sequence in a single forward pass.
* **Minimalist UI:** Built with Gradio for seamless PDB uploads and sequence generation.
* **Colab Ready:** Zero-setup implementation for researchers and students.

### 🛠️ Tech Stack
* **Model:** PiFold (PiGNN)
* **Frontend:** Gradio
* **Environment:** Google Colab / Python 3.10+

### 📖 How to Use
1. Open the notebook in [Google Colab](https://colab.research.google.com/drive/1pqUlpwh3HQTWar1jLfMitYkZBofr8Sx4?usp=sharing).
2. Run the setup cells to install PyTorch Geometric.
3. Upload your `.pdb` file and hit **Generate Sequence**.

### 📊 Metrics Tracked
* Native Sequence Recovery (NSR)
* Sequence Length
* Inference Latency
