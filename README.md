# Python ML inference acceleration on Windows using commodity GPUs

A Jupyter notebook testing DirectML support of ONNX on Windows using an Intel GPU.

## Getting Started

Initialize the virtual environment and start Jupyter Lab. Open an Anaconda prompt ([Miniconda](https://docs.conda.io/en/latest/miniconda.html) is sufficient):
```
conda env create -f conda.yaml
conda activate onnx-directml
python -m ipykernel install --user --name=onnx-directml
jupyter lab
```

> Note: if Jupyter does not load on Chrome, open chrome://net-internals/#hsts and use `Delete domain security policies` to delete `localhost`, then try again.
