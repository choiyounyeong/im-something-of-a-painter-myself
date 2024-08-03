#### CSCA 5642 Introduction to Deep Learning
# I’m Something of a Painter Myself

***

## Brief Description of the Problem and Data (5 pts)

The challenge is to **generate paintings using Generative Adversarial Networks (GANs)**. This task is crucial for advancing AI in creative domains, allowing for the synthesis of realistic artwork. A GAN model will be employed due to its effectiveness in generating high-quality images.

The data is sourced from the [I’m Something of a Painter Myself Dataset](https://www.kaggle.com/competitions/gan-getting-started/data). The dataset(385.87 MB) contains four directories: monet_tfrec, photo_tfrec, monet_jpg, and photo_jpg. The monet_tfrec and monet_jpg directories contain the same painting images, and the photo_tfrec and photo_jpg directories contain the same photos. The monet directories contain Monet paintings and those will be used to train our model. The photo directories contain photos.

- monet_jpg - 300 Monet paintings sized 256x256 in JPEG format
- monet_tfrec - 300 Monet paintings sized 256x256 in TFRecord format
- photo_jpg - 7028 photos sized 256x256 in JPEG format
- photo_tfrec - 7028 photos sized 256x256 in TFRecord format

For more details, please refer to the notebook in this repository.