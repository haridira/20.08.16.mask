# An ML Model for Face Mask Recognition

## Model and Application

The model uses real time web camera to distinguish proper mask usage. It uses a simple binary classification (either mask worn correctly or not) based on supervised ML learning.

## Dataset Used

The Flickr-Faces-HQ Dataset (FFHQ) was used for training this model: [dataset Flickr-Faces-HQ (FFHQ)](https://github.com/NVlabs/ffhq-dataset). The dataset includes 133,783 images, all labeled, with the data composition roughly being 49% vs. 51% for correctly masked faces vs. incorrectly masked faces (respectively). We used a subset of the full data to train our model, so accuracy is expected to be slightly better if the whole dataset is used for training.

## Performance Statistics

The model is able to predict proper mask usage using live web cam with 98% accuracy rate.
