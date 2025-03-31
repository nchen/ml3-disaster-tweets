# ml3-disaster-tweets

Environment setup:

- OS: Windows 11
- GPU: NVIDIA GeForce RTX 3060 Laptop GPU
- CUDA 11.2.2
- cuDNN 8.1.1

Python related:

```
choco install pyenv-win
pyenv install 3.10.5

pyenv rehash
pyenv global 3.10.5

python -m venv tf
pip uninstall numpy
pip install "numpy<2"
pip install tensorflow==2.10.0
```
