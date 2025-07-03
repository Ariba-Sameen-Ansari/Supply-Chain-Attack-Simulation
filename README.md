# Supply Chain Attack Simulation 🐍

This Jupyter notebook demonstrates a basic example of a software supply chain attack, where a seemingly safe helper function performs hidden malicious behavior.

## 🔍 What It Shows
- How an attacker can inject malicious code into an innocent-looking function
- How that code can silently execute during normal use
- How to detect such behavior via file system audits

## 🧪 Simulation Details
- Function `add(a, b)` performs addition
- But it also writes input data to a file called `stolen_data.txt` without the user's knowledge
- Audit code simulates detection by checking for unauthorized files

## 🛠 Tools Used
- Python
- Jupyter Notebook
- `os` module for detection

## 🧠 What I Learned
- Supply chain risk in software development
- Importance of code audits and package reviews
- How to simulate real-world threats in a beginner-friendly way
