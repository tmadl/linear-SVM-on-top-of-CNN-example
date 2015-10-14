Training a custom classifier on top of CNN features
=========

Simple example for how to train a classifier recognizing objects in images based on Convolutional Neural Network features (from layer fc8).

You can just click on *CNNexp.ipynb*, and take a look at the code

In order to actually run it, you will need to install/download
* [Python 2.7](https://www.python.org/downloads/)
* [Jupyter / IPython notebook](http://ipython.org/notebook.html)
* Python libraries: [sklearn, matplotlib](http://scikit-learn.org/stable/install.html), [PIL (Python imaging library)](http://pillow.readthedocs.org/en/3.0.x/installation.html)
* The [Caffe deep learning framework](http://caffe.berkeleyvision.org/)
* bvlc_googlenet (or bvlc_reference_caffenet) from [Caffe ModelZoo](https://github.com/BVLC/caffe/wiki/Model-Zoo)

After installing/downloading these, download this project, uncompress all zip files, and then start "ipython notebook" within the folder you downloaded this project to. Then open *CNNexp.ipynb*, and follow the instructions there.

Tested with Ubuntu 12.04 (caffe doesn't work well with Windows)

For more information and more detailed tutorials, please see
* [caffe examples](https://github.com/BVLC/caffe/tree/master/examples), especially [classification](https://github.com/BVLC/caffe/blob/master/examples/00-classification.ipynb), which visualizes what CNN features look like
* [The caffe Tutorial](http://caffe.berkeleyvision.org/tutorial/)
* [Linux, Python & caffe installation tutorial](http://www.slideshare.net/calmli/linux-python-caffelihang)
* finally, for developing intuitions on deep learning, see [Neural Networks, Manifolds, and Topology](http://colah.github.io/posts/2014-03-NN-Manifolds-Topology/)
