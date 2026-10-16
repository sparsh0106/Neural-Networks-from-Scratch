# 🧠 Neural Networks from Scratch (ANN, CNN & LSTM)

Pure **NumPy** and **SciPy** implementations of core deep learning architectures built from the ground up without high-level deep learning frameworks (no PyTorch or TensorFlow for the core layers).

---

## 📂 Repository Structure

| Notebook | Architecture | Task & Dataset | Key Concepts Implemented |
| :--- | :--- | :--- | :--- |
| `scratch_ann.ipynb` | **Artificial Neural Network (MLP)** | Multi-class classification on the **Iris Dataset** (`Iris.csv`) | Weight initialization, forward propagation, ReLU & Softmax activations, Categorical Cross-Entropy loss, analytical backpropagation, gradient descent. |
| `scratch_cnn.ipynb` | **Convolutional Neural Network (CNN)** | 2D image/matrix feature extraction | Custom 2D convolution (`convolve2d` & manual sliding-window loops), non-overlapping strided convolution, max/average pooling, and forward/backward passes. |
| `scratch_lstm.ipynb` | **Long Short-Term Memory (LSTM)** | Synthetic noisy sine-wave time-series forecasting | Forget, Input, Candidate, and Output gates ($\sigma$ and $	anh$), cell state ($c_t$) and hidden state ($h_t$) recurrence, and Backpropagation Through Time (BPTT). |

---

## 🔬 Highlights

- **Zero Black-Box Layers**: Every matrix multiplication, activation derivative, gate update, and weight step is written explicitly in NumPy.
- **Step-by-Step Mathematical Clarity**: Ideal for understanding how gradients flow through dense layers, spatial filters, and recurrent memory cells.
- **Visual Diagnostics**: Includes loss curves and time-series prediction plots using `matplotlib`.

---

## 🚀 Getting Started

1. **Clone the repository**:
   ```bash
   git clone https://github.com/sparsh0106/Neural-Networks-from-Scratch.git
   cd Neural-Networks-from-Scratch
   ```

2. **Install dependencies**:
   ```bash
   pip install numpy pandas scipy scikit-learn matplotlib jupyter
   ```

3. **Launch Jupyter Notebook**:
   ```bash
   jupyter notebook
   ```

---

## 👤 Author

**Sparsh Agarwal** — [GitHub](https://github.com/sparsh0106) · [LinkedIn](https://www.linkedin.com/in/sparsh-agarwal-4b443b304/)
