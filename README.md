# HumorLens

Uses CNN and transformers to explains the humor in The New Yorker comics. Intended to run in a Google Colab notebook or cloud instance.

## Setup

1. Clone this repository
2. Install the required packages
3. install the MS COCO dataset from https://cocodataset.org/#download (2014 train images, 2014 Val Images, 2014 Train/Val annotations)

## Usage

1. Run the notebook

## Potential Issues

1. If the Flicker8 dataset is already downloaded, the code will stall. Either delete the Flicker8 dataset or remove the code that downloads it.
2. If the MS COCO dataset is not downloaded, or if the MS COCO dataset is not in the correct directory, the code will generate an error. Either delete the MS COCO dataset or remove the code that downloads it.
