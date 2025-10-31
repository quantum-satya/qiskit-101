# Qiskit-101

Step-by-step notebooks to learn and experiment with **Qiskit**, IBM’s quantum SDK.

## Contents
| Notebook | Description |
|-----------|--------------|
| [01-hello-qiskit.ipynb](notebooks/01-hello-qiskit.ipynb) | Create a 1-qubit circuit, run on simulator, and view results |

## How to run locally
```bash
git clone https://github.com/quantum-satya/qiskit-101.git
cd qiskit-101
python -m venv venv && source venv/bin/activate
pip install -r requirements.txt
jupyter notebook
