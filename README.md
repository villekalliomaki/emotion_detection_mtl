# Auxiliary task assisted text emotion detection through multi-task learning and knowledge distillation

This repository contains the Python implementations for a thesis researching how auxiliary tasks could be used to increase classification performance in text emotion detection. The link to the thesis will be provided here later, when released.

## Colab notebook links

The noteboooks were developed on Google Colab, which is the easiest way to run, edit and view them. Opening the notebooks on GitHub doesn't currectly work, so the links below can be used to view them on Colab.

[The intra-dataset approach (one dataset)](https://colab.research.google.com/github/villekalliomaki/emotion_detection_mtl/blob/main/notebooks/MTL_Emotion_detection_Intra_dataset_approach.ipynb)

[The inter-dataset approach (multiple datasets)](https://colab.research.google.com/github/villekalliomaki/emotion_detection_mtl/blob/main/notebooks/MTL_Emotion_detection_Inter_dataset_approach.ipynb)

## Datasets and models

The checkpoints of the best performing model checkpoints and the dataset contaning the distillation features used in the intra-dataset approach can be found in the `models` and `datasets` directories. The most convenient way to use them is to copy a direct link to them on GitHub, and use wget for example to download them on Colab. This way there is no need to download them first and then upload them to Colab, where especially the uploading stage can be very slow. The models and datasets are compressed to zip-files, which need to be decompressed on Colab before loading them.
