# Artificial Neural Networks: The Perceptron

A hands-on Jupyter Notebook exploring the Perceptron, one of the foundational building blocks of artificial neural networks. This lab implements a perceptron from scratch, trains it on logical gates, visualizes linear decision boundaries, investigates the XOR limitation, and compares a custom implementation with Scikit-learn using Iris and synthetic datasets.

## Learning objectives

- Understand a threshold logic unit (TLU), weights, bias, weighted sum, and step activation.
- Implement prediction and the Perceptron learning rule using NumPy.
- Track classification mistakes across epochs and understand convergence on linearly separable data.
- Visualize decision boundaries and compare models with and without a bias term.
- Explain why a single-layer perceptron cannot solve XOR, and demonstrate a two-layer threshold network that can.
- Evaluate binary and three-class Iris classification with accuracy and macro F1.
- Compare a hand-built perceptron with `sklearn.linear_model.Perceptron` on synthetic data.

## Repository contents

| File | Description |
| --- | --- |
| `Perceptron_Lab.ipynb` | Complete lab notebook with explanations, code, tables, and visualizations. |
| `requirements.txt` | Python dependencies needed to run the notebook. |

## Getting started

1. Clone the repository:

   ```bash
   git clone https://github.com/waseemshareefjamro/Artificial-Neural-Networks-The-Perceptron.git
   cd Artificial-Neural-Networks-The-Perceptron
   ```

2. (Recommended) Create and activate a virtual environment:

   ```bash
   python -m venv .venv
   # Windows PowerShell
   .venv\\Scripts\\Activate.ps1
   # macOS/Linux
   source .venv/bin/activate
   ```

3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Launch Jupyter:

   ```bash
   jupyter notebook
   ```

5. Open `Perceptron_Lab.ipynb` and run all cells from top to bottom (`Kernel/Runtime → Restart and Run All`).

## Experiments included

- **Neuron from scratch:** weighted sum, threshold step function, and prediction.
- **Learning rule:** a worked AND-gate epoch and a trainable OR-gate perceptron.
- **Training behavior:** mistakes per epoch and convergence.
- **Decision boundaries:** linear separators and the effect of bias.
- **Logical gates:** AND, OR, and XOR; the XOR section demonstrates a hidden-layer solution.
- **Iris dataset:** binary Setosa-vs-rest and three-class experiments, including feature comparisons.
- **Synthetic dataset:** hand-built perceptron vs. Scikit-learn, with Logistic Regression as a reference model.

## Technologies

Python · Jupyter Notebook · NumPy · Pandas · Matplotlib · Scikit-learn

## Reproducibility

The notebook uses a fixed seed (`random_state = 42`) for its primary experiments. Some Iris experiments also evaluate multiple train/test splits to show variation across random seeds.

## Author

**Waseem Shareef Jamro**

---

Created for learning and academic practice in machine learning and artificial neural networks.
