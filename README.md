# Deep Convolutional GAN (DCGAN)

This is a modification of [original DCGAN code](https://github.com/Newmu/dcgan_code) by [Alec Radford]((https://github.com/newmu)). proposed in the paper : [http://arxiv.org/abs/1511.06434](http://arxiv.org/abs/1511.06434)

![](images/lsun_bedrooms_generator.png)

Other implementations of DCGAN
* [Lua-Torch](https://github.com/soumith/dcgan.torch)
* [Chainer](https://github.com/mattya/chainer-DCGAN)
* [TensorFlow](https://github.com/carpedm20/DCGAN-tensorflow)

This modification is intented to work with latest version of Theano (version 1.0 and later)

Requirements :
- Python 3.5
- Theano 1.0 (recommended to use bleeding-edge version)
- CUDA drivers and CuDNN library
- Scipy
- Numpy
- Matplotlib
- Tqdm
- fuel/h5py (for CelebA faces)

## Training DCGAN
1. Install all requirements
2. Modify `data-dir` in lib/config.py to point to directories containing data
3. For MNIST, run