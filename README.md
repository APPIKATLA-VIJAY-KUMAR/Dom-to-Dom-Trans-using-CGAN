# Domain-to-Domain Translation using Conditional Generative Adversarial Networks (CGANs)

This is a project that uses conditional generative adversarial networks (CGANs) to perform domain-to-domain translation, such as converting images from one style to another. The CGANs consist of two networks: a generator and a discriminator. The generator tries to create realistic images that belong to the target domain, while the discriminator tries to distinguish between real and fake images. The generator and the discriminator are trained together in an adversarial manner, until the generator can fool the discriminator.

## Requirements

- Python 3.6 or higher
- TensorFlow 2.0 or higher
- Keras
- Numpy
- Scipy
- Matplotlib
- PIL

## Usage

- Clone this repository or download the files.
- Run the `Dom-to-Dom-Trans-CGAN.ipynb` notebook in Google Colab or Jupyter Notebook.
- Execute all the cells.
- See the results of domain-to-domain translation.

## Acknowledgements

This project is based on the following papers:

- https://arxiv.org/abs/1411.1784
- https://arxiv.org/abs/1611.07004
## Credits
  ##### Copyright 2019 The TensorFlow Authors.

Licensed under the Apache License, Version 2.0 (the "License");<br>
<a href="https://www.tensorflow.org/tutorials/generative/pix2pix#:~:text=pix2pix%20is%20not%20application%20specific,even%20transforming%20sketches%20into%20photos.">pix2pix:Image-to-image translation</a>
