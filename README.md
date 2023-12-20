[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/3d-lfm-lifting-foundation-model/3d-human-pose-estimation-on-h3wb)](https://paperswithcode.com/sota/3d-human-pose-estimation-on-h3wb?p=3d-lfm-lifting-foundation-model)


# 3D Lifting Foundation Model (3D-LFM) 🌐

Welcome to the official repository for the **3D Lifting Foundation Model (3D-LFM)**, a model designed to lift 2D landmarks into high-fidelity 3D structures across diverse object categories. 🚀

**Current Status:** This repository currently supports **demo visualization of the model's performance**. The comprehensive codebase, including actual training and evaluation functionalities, will be **released soon**.


## Features 🌟

- **Versatile 3D Reconstruction**: Capable of lifting single-view 2D landmarks into 3D structures for a wide range of objects.
- **OOD Handling**: State-of-the-art performance on object-specific as well as object-agnostic Out-of-Distribution (OOD) validation data.
- **Interactive Visualization**: Explore and visualize 3D predictions against ground truth data interactively.

## Getting Started 🚀

### Prerequisites

- Make sure you have Python installed on your system. You can download it from [here](https://www.python.org/downloads/).

### Installation

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/mosamdabhi/3dlfm.git
    cd 3dlfm
    ```

2. **Set up a Virtual Environment** (Optional but recommended):
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

### Running the Demo

Launch the `demo_vis.ipynb` notebook using Jupyter:
```bash
    jupyter notebook demo_vis.ipynb
```
Follow the instructions in the notebook for an interactive experience.

## Usage 📘

After launching the notebook:

- **Choose a Category**: Select from predefined categories for visualization (option to choose between standard validation and OOD validation).
- **Visualize Results**: View the 3D reconstructed models and compare them with ground truth data (including actual RGB images).
- **Explore Different Objects**: Experiment with various object categories, both standard and OOD.

## Contributing 🤝

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License 📜

Distributed under the BSD-3-Clause license. See LICENSE for more information.

## Contact 📫

- **Mosam Dabhi**: [@mosamdabhi](https://twitter.com/mosamdabhi) | [mosam@cmu.edu](mosam@cmu.edu)
- **Project Link**: [3dlfm.github.io](https://3dlfm.github.io)
