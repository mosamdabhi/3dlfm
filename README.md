
<div align="center">

  # 3D Lifting Foundation Model (3D-LFM) 🌐
  
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/3d-lfm-lifting-foundation-model/3d-human-pose-estimation-on-h3wb)](https://paperswithcode.com/sota/3d-human-pose-estimation-on-h3wb?p=3d-lfm-lifting-foundation-model) [![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/3d-lfm-lifting-foundation-model/3d-facial-landmark-localization-on-h3wb)](https://paperswithcode.com/sota/3d-facial-landmark-localization-on-h3wb?p=3d-lfm-lifting-foundation-model) [![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/3d-lfm-lifting-foundation-model/3d-hand-pose-estimation-on-h3wb)](https://paperswithcode.com/sota/3d-hand-pose-estimation-on-h3wb?p=3d-lfm-lifting-foundation-model)


<div>
<a target="_blank" href="https://arxiv.org/abs/2312.11894">
  <img src="https://img.shields.io/badge/arXiv-2312.11894-b31b1b.svg" alt="arXiv Paper"/>
</a>   

  [![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fmosamdabhi%2F3dlfm&count_bg=%2379C83D&title_bg=%23453535&icon=github.svg&icon_color=%23E7E7E7&title=hits&edge_flat=false)](https://hits.seeyoufarm.com)    
</div>



</div>

Welcome to the official repository for the **3D Lifting Foundation Model (3D-LFM)**, a model designed to take 2D landmarks and generate high-fidelity 3D poses across diverse object categories. 🚀

<div align="center">
  
  ## 3D Pose for anything!
  
<img src="https://3dlfm.github.io/assets/teaser.gif" alt="" style="zoom: 60%;" />
</div>

**Current Status:** This repository currently supports **demo visualization of the model's performance**. The comprehensive codebase, which includes actual training and evaluation functionalities, is planned for release as soon as the licensing information becomes available. COMING SOON! STAY TUNED!!








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
