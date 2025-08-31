# Smart Waste Classifier

This repository contains the code and resources for the **Smart Waste Classifier** project, developed for the **FORK THIS** competition organized by CSI-VIT.

## Overview

The Smart Waste Classifier aims to automate the process of sorting waste by leveraging machine learning and computer vision techniques. This project provides tools and models to classify different types of trash, helping improve recycling efficiency and reduce manual sorting efforts.

## Competition

This project was developed as a submission for the [FORK THIS](https://forkthis.csivit.com/) competition by CSI-VIT. The participants are to find apropriate errors in the codes and hence the .iynb file has a few errors intentionally.

## Dataset

The model is trained using the [TrashNet dataset](https://www.kaggle.com/datasets/feyzazkefe/trashnet) available on Kaggle. The dataset contains images of various types of waste, including:

- Glass
- Paper
- Cardboard
- Plastic
- Metal
- Trash

## Features

- Image classification for various waste types.
- Preprocessing and augmentation scripts.
- Training and evaluation notebooks.
- Model inference demonstration.

## Getting Started
It is recommended to carry out the execution/corrections using Google colab otherwise you may refer the steps below.

### Prerequisites

- Python 3.7+
- TensorFlow or PyTorch (depending on implementation)
- Other dependencies as listed in `requirements.txt`

### Installation

Clone the repository:

```bash
git clone https://github.com/Diptesh2006/smart-waste-classifier.git
cd smart-waste-classifier
```

Install the required packages:

```bash
pip install -r requirements.txt
```

### Dataset Setup

Download the TrashNet dataset from [Kaggle](https://www.kaggle.com/datasets/feyzazkefe/trashnet) and extract it into the `data/` directory:

```
smart-waste-classifier/
└── data/
    └── trashnet/
        ├── glass/
        ├── paper/
        ├── cardboard/
        ├── plastic/
        ├── metal/
        └── trash/
```


```

## Contributing

Feel free to fork this repository and contribute improvements or new features!

## License

This repository is for educational and competition purposes. Please check individual files for license information.

## Acknowledgements

- [CSI-VIT](https://csivit.com/) for hosting the competition.
- [Kaggle TrashNet Dataset](https://www.kaggle.com/datasets/feyzazkefe/trashnet) for providing the data.
