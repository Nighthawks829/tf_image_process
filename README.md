# Load and Preprocess Image

This notebook shows how to load and preprocess an image dataset in three ways
1. First, we'll use high-level Keras preprocessing utilities (such as ``tf.keras.utils.image_dataset_from_directory``) and layers (such as ``tf.keras.layers.Rescalling``) to read a directory of images on disk.
2. Next, we'll write our own input pipeline from scratcg using ``tf.data``
3. Finally, we will download dataset fron the large catalog availabel in TensorFlow Datasets
