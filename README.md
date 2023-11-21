# Image-Caption-Generator

This repository contains code for an image captioning model that combines Convolutional Neural Networks (CNN) and Recurrent Neural Networks (RNN) to generate descriptive captions for images. The model is trained on the Flickr8k dataset.

## Getting Started

### Prerequisites

Make sure you have the following dependencies installed:

- TensorFlow
- PIL
- tqdm
- numpy

### Installation

Clone the repository to your local machine:

```bash
git clone https://github.com/amanparasher/image-caption-generator.git
```

### Dataset

Download the Flickr8k dataset from [here](https://forms.illinois.edu/sec/1713398) and extract the contents into the `data` folder.

### Usage

1. Open and run the Jupyter notebook (`image_captioning.ipynb`) to preprocess the data, train the model, and save it.

2. To test the trained model on a new image, use the provided script:

```bash
python3 testing_caption_generator.py -i /path/to/your/image.jpg
```

## Code Structure

- `image_captioning.ipynb`: Jupyter notebook containing the code for data preprocessing, model training, and saving the model.
- `testing_caption_generator.py`: Python script for testing the trained model on new images.
- `utils.py`: Utility functions for data loading and processing.
- `data/`: Folder to store the Flickr8k dataset.

