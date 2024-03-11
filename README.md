# QuantumCoinGame
Coin game in two forms for the techaways talk at BBD

# Getting started
Clone the repo and setup a python venv in the root folder

```python -m venv venv```

Once the venv is activated (on windows ```./venv/Scripts/activate``` install:

```
pip install setuptools
pip install qiskit
pip install qiskit-ibm-runtime
pip install ipywidgets
pip install qiskit_aer
pip install qiskit[visualization]
```

Then create an account on the IBM quatum computing platform: 

```https://quantum.ibm.com/```

Then replace the token in the jupyter notebooks with yours to connect to the QiskitRuntime.

Happy quantum computing


# Troubleshooting
Modules not being found error: 
- When running the jupyter notebooks in vscode, I found that I need to close and reopen the notebook when I install new dependencies.
