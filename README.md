# Deep Learning CNN

**Portfolio Project: Deep Learning & CNNs**

This repository showcases my hands-on work for a university homework assignment focused on Deep Learning and Convolutional Neural Networks (CNNs). It is designed as a portfolio-ready project to demonstrate my practical skills and understanding of core deep learning concepts, suitable for sharing with recruiters and potential employers.

---

## About the Homework

The main deliverable is the Jupyter notebook [`CNN_ImageRecognition_Homework.ipynb`](CNN_ImageRecognition_Homework.ipynb), which walks through a series of deep learning experiments and visualizations. This notebook highlights my ability to:

- **Build and experiment with neural networks**: Including single-layer and multi-layer models, using different activation functions (Sigmoid, ReLU) on synthetic datasets (concentric classes, XOR, spiral data, regression).
- **Work with image data**: Loading, normalizing, and batching sample images for processing.
- **Implement and visualize convolutional filters**: Creating custom filters, applying them to images, and visualizing both the filters and their resulting feature maps.
- **Use industry-standard libraries**: TensorFlow, Keras, NumPy, Matplotlib, and scikit-learn.
- **Explain and visualize deep learning concepts**: Using markdown and code to clearly communicate what convolutions are, how filters work, and how CNNs extract features from images.

### Key Sections of the Notebook

1. **Neural Network Fundamentals**: Introduction to neural nets, activation functions, and solving classic problems (e.g., XOR).
2. **Convolutional Neural Networks (CNNs)**: Explanation of convolutions, building and visualizing filters, and applying them to real image data.
3. **Practical Implementation**: Step-by-step code for data preparation, filter creation, application, and result visualization.
4. **Conceptual Understanding**: Rich markdown explanations and visual aids throughout the notebook.

### Skills Demonstrated

- Understanding of neural networks and CNN architectures
- Data preprocessing and visualization
- Implementation of custom filters and convolution operations
- Use of Python deep learning ecosystem
- Clear technical communication and documentation

---

This project is ideal for demonstrating my readiness for roles involving deep learning, computer vision, or machine learning engineering. Please explore the notebook for a detailed look at my technical approach and results.

## Python Environment

This project is tested and recommended to run with **Python 3.8**. Using other Python versions may cause incompatibilities with the deep learning libraries specified.

### Setting up the Conda Environment

1. Ensure you have [Anaconda](https://www.anaconda.com/products/distribution) or [Miniconda](https://docs.conda.io/en/latest/miniconda.html) installed.
2. Create the environment from the provided `environment.yml` file:
   ```bash
   conda env create -f environment.yml
   ```
3. Activate the environment:
   ```bash
   conda activate deep-learning-cnn
   ```
4. (Optional) If you add new dependencies, update the environment with:
   ```bash
   conda env update -f environment.yml --prune
   ```
