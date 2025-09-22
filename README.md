# PyTorch Models - Fashion MNIST

This repository contains a PyTorch implementation of a simple fully connected neural network for the **Fashion MNIST** dataset. The notebook demonstrates loading data, preprocessing, creating custom datasets, and training a neural network.

## Files

* `PyTorch models.ipynb` - Main Jupyter notebook containing all tasks and implementations.
* `PyTorch models.ipynb_` - Backup/temporary notebook.
* `PyTorch models/` - Folder containing auxiliary code and data (e.g., `mnist_reader.py`).

## How to Use

1. Clone the repository:

```bash
git clone <repository_url>
cd <repository_folder>
```

2. Open `PyTorch models.ipynb` in **Jupyter Notebook** or **Google Colab**.
3. Recommended: Use **GPU** for faster training in Colab:

   * Runtime > Change runtime type > Hardware accelerator > GPU
4. Run the notebook step by step.

## Dataset

* **Fashion MNIST**: 70,000 grayscale images of 10 fashion categories.
* Images are 28x28 pixels.
* Dataset is loaded from [Zalando Research GitHub](https://github.com/zalandoresearch/fashion-mnist).

## Tasks Covered

* TASK 1: Stratified train-validation split using `sklearn`.
* TASK 2: Dynamic dataset loading with `torch.utils.data.Dataset`.
* Creating `DataLoader` for batching and shuffling.
* Building a simple fully connected neural network with PyTorch.
* Visualizing and summarizing the model.

## Requirements

```bash
pip install numpy torch matplotlib scikit-learn torchsummary
```

## Author

**Prashant Singh**

* AI/ML Enthusiast


## License

MIT License
