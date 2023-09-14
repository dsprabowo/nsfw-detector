# nsfw-detector
Computer Vision project to detect NSFW Images built with Tensorflow in Python

# Install libraries
* run ```pip install -r requirements.txt```

# Training dataset
* dataset url list in [raw data](https://github.com/dsprabowo/nsfw-detector/tree/main/raw_data) folder obtained from [here](https://github.com/alex000kim/nsfw_data_scraper)
* sample scraper script in [this notebook](https://github.com/dsprabowo/nsfw-detector/blob/main/nsfw_python_scraper.ipynb)

# Models preview
1. Base custom model
![confusion matrix](https://github.com/dsprabowo/nsfw-detector/blob/main/assets/cm_custom_base.png)
2. Custom model + dropout layer + data augmentation
![confusion matrix](https://github.com/dsprabowo/nsfw-detector/blob/main/assets/cm_custom_dropout_augmented.png)
3. Transfer learning
![confusion matrix](https://github.com/dsprabowo/nsfw-detector/blob/main/assets/cm_mobilenet.png)
4. Transfer learning + fine tuning
![confusion matrix](https://github.com/dsprabowo/nsfw-detector/blob/main/assets/cm_mobilenet_fine_tuned.png)