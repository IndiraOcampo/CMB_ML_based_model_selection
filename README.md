# CMB Machine Learning based model selection and interpretability

![License Badge](https://img.shields.io/badge/license-MIT-brightgreen.svg)
[![arXiv](https://img.shields.io/badge/arXiv-2410.05209-b31b1b.svg)](https://arxiv.org/abs/2410.05209)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.13828966.svg)](https://doi.org/10.5281/zenodo.13828966)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.13829665.svg)](https://doi.org/10.5281/zenodo.13829665)



## Table of Contents

- [Overview](#overview)
- [Description](#Description)
- [Installation](#installation)
- [Usage](#usage)
- [Acknowledgements](#acknowledgements)

---

## Overview

Repository showing how to use Neural Networks (NN) to test beyond ΛCDM models against Cosmic Microwave Background (CMB) data, at the level of the angular power spectra. All the analysis is found within the corresponding jupyter notebooks.

## Description 

The repository is structured as follows. Within the `neural_networks` folder, you can find the folders:

- `modified_gravity`
- `feature`

Each folder contain the corresponding `jupyter` notebooks 

## Installation

### Prerequisites

- Required software: `python`
- Dependencies: `numpy`, `matplotlib`, `tensorflow`, `shap`
- It is recommended to run the notebooks to train the Neural Networks in a cluster with GPUs
- The data to train the Neural Networks are found at these Zenodo repositories: [modified gravity](https://zenodo.org/records/13828966) and [primordial feature](https://zenodo.org/records/13829665).

### How to get started

```bash
# Example to get it running
pip install numpy matplotlib tensorflow
git clone https://github.com/IndiraOcampo/CMB_ML_based_model_selection.git
cd neural_networks
```

## Usage

If you are using the content provided in this repository to do your own analysis, please cite this repository and the manuscript:

```bash
@misc{CMB_ML_based_model_selection,
  author = {Ocampo, I},
  title = {CMB ML based model selection},
  year = {2024},
  publisher = {GitHub},
  journal = {GitHub repository},
  howpublished = {\url{https://github.com/IndiraOcampo/CMB_ML_based_model_selection.git}},
}
```


```bash
@misc{ocampo2024neuralnetworkscosmologicalmodel,
      title={Neural Networks for cosmological model selection and feature importance using Cosmic Microwave Background data}, 
      author={I. Ocampo and G. Cañas-Herrera and S. Nesseris},
      year={2024},
      eprint={2410.05209},
      archivePrefix={arXiv},
      primaryClass={astro-ph.CO},
      url={https://arxiv.org/abs/2410.05209}, 
}
```

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/IndiraOcampo/CMB_ML_based_model_selection/blob/main/LICENSE) file for details.

## Acknowledgements

This reaseach acknowledges support from the [ESA Archival Research Visitor Programme](https://www.cosmos.esa.int/web/esdc/visitor-programme): a programme to increase the scientific return from ESA space science missions by supporting scientists interested in pursuing research based on publicly available data in the ESA Space Science Archives.  This work is also supported by
the fellowship LCF/BQ/DI22/11940033 from “la Caixa” Foundation (ID 100010434). This research uses ESA Planck Legacy archives. 



