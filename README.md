# Tutorials for Computational Analysis of Visual Social Media [![DOI](https://zenodo.org/badge/573008138.svg)](https://zenodo.org/badge/latestdoi/573008138)


![A robot conducting visual social media analysis](https://user-images.githubusercontent.com/8556092/229534426-846f4b4d-61b6-499b-8465-65e93b278c35.png)

This repository contains Jupyter notebooks for performing visual social media analysis. The notebooks provide step-by-step instructions for collecting, processing, and analyzing visual media data from social media platforms such as Instagram. They are part of [Medium stories](https://achmann.dev) on computational social media published by  [Michael Achmann](https://go.ur.de/michael-achmann) as part of his Ph.D. research and teaching at the Chair for Media Informatics, University of Regensburg.

There are more notebooks available in the [social media lab repository.](https://github.com/michaelachmann/social-media-lab) 

## Table of Contents

- [Articles](#articles)
- [Notebooks](#notebooks)
- [Contributing](#contributing)
- [License](#license)

## Articles

- ["Getting Started with Instagram Analysis: Instaloader"](https://medium.com/@michael.achmann/getting-started-with-instagram-analysis-instaloader-bbf686cb6e3b) - An introduction to data collection using ["Instaloader"](https://instaloader.github.io/)
- ["CrowdTangle for Instagram Analysis: A Step-by-Step Guide for Beginners"](https://achmann.dev/crowdtangle-for-instagram-analysis-a-step-by-step-guide-for-beginners-6d4f1f8cb0a3) - How to use [CrowdTangle](https://www.crowdtangle.com/) for retrospective data collection.
- ["How to Accelerate your Annotation Process for Visual Social Media Analysis with Label Studio"](https://achmann.dev/how-to-accelerate-your-annotation-process-for-visual-social-media-analysis-with-label-studio-24c980a909f6) - A step-by-step guide to create a LabelStudio project for image annotation. 

## Notebooks

- `01_DataCollection.ipynb` - A notebook demonstrating how to download posts from Instagram using Instaloader.
- `02_CrowdTanlgeDownload.ipynb` - A notebook demonstrating how to download Instagram post images from a CrowdTangle dataframe.
- `03_AutomatedExportLabelStudio.ipynb` - Automates the creation of a LabelStudio project. Through several stept we first upload image files to a Google Cloud Bucket, then create a labelling interface, and finally create the project. 

## Getting Started

To use the notebooks in this repository, you have two options:

### 1. Local Installation (Jupyter Notebook)

You can run the Jupyter notebooks locally on your computer. To do this, you will need to have [Jupyter Notebook](https://jupyter.org/) installed. If you don't have it installed, you can follow the installation instructions on the Jupyter website. Once you have Jupyter Notebook installed, you can clone this repository using the following command:

```bash
git clone https://github.com/michaelachmann/social-media-lab.git
```

Then, navigate to the repository directory:

```bash
cd social-media-lab
```

Start the Jupyter Notebook server:

```bash
jupyter notebook
```

Open any notebook file (e.g., `example_notebook.ipynb`) to begin exploring social media analysis techniques.

### 2. Google Colab

If you prefer to use Google Colab, you can run the notebooks directly from your web browser. Google Colab is a free cloud-based platform that provides access to Jupyter notebooks with integrated GPU support. It allows you to run code, including Python and TensorFlow, on Google's servers without any local installation.

To run a notebook in Google Colab, simply click on the "Open in Colab" badge ![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg) inside the notebook. This will open the notebook in Google Colab, where you can execute the code and analyze social media data directly in the cloud.

Please note that while Google Colab is convenient for quick experimentation, you might need to sign in with your Google account and save a copy of the notebook to your Google Drive for long-term storage.

## Citation

I'd appreciate a citation if you're using the tutorials and notebooks in your research.

```
Michael Achmann. (2023). michaelachmann/ig-tutorial: First Release (v1.0.0). Zenodo. https://doi.org/10.5281/zenodo.8199595
```

```bibtex
@software{michael_achmann_2023_8199595,
  author       = {Michael Achmann},
  title        = {michaelachmann/ig-tutorial: First Release},
  month        = jul,
  year         = 2023,
  publisher    = {Zenodo},
  version      = {v1.0.0},
  doi          = {10.5281/zenodo.8199595},
  url          = {https://doi.org/10.5281/zenodo.8199595}
}
```

## License

This repository is licensed under the [GNU General Public License v3.0](https://opensource.org/licenses/GPL-3.0). You are free to use, copy, modify, merge, publish, distribute, and/or sell copies of the repository, subject to the conditions of the license.

## Contributing

We welcome contributions to the project. If you have ideas, improvements, or would like to add new notebooks, please open an issue or submit a pull request. 
