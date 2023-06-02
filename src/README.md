## Wavelet Scattering Transform Research

This repo is for research purposes only. It is not intended to be used as a library.

```bash
git clone https://github.com/drbh/wst.cpp
cd wst.cpp
mkdir build && cd build
cmake ..
make -j4 wavelet-scatter
# Consolidate compiler generated dependencies of target wavelet-scatter
# [100%] Built target wavelet-scatter
./wavelet-scatter
# _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _
# _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _
# _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _
# _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _
# _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _
# _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _
# _ _ _ _ _ _ _ _ _ _ _ * * _ _ _ _ _ _ _ _ _ _ _ _ _ _ _
# _ _ _ _ _ _ _ _ _ _ * _ _ _ * * _ _ _ _ _ _ _ _ _ _ _ _
# _ _ _ _ _ _ _ _ _ * _ _ _ _ _ * * _ _ _ _ _ _ _ _ _ _ _
# _ _ _ _ _ _ _ _ * _ _ _ _ _ _ _ * _ _ _ _ _ _ _ _ _ _ _
# _ _ _ _ _ _ _ _ * _ _ _ _ _ _ _ _ * * _ _ _ _ _ _ _ _ _
# _ _ _ _ _ _ _ _ * _ _ _ _ _ _ _ _ * _ _ _ _ _ _ _ _ _ _
# _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ * _ _ _ _ _ _ _ _ _ _
# _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ * _ _ _ _ _ _ _ _ _ _
# _ _ _ _ _ _ _ _ * _ _ _ _ _ _ _ _ * _ _ _ _ _ _ _ _ _ _
# _ _ _ _ _ _ _ _ _ * * _ _ _ _ _ _ * _ _ _ _ _ _ _ _ _ _
# _ _ _ _ _ _ _ _ _ _ _ * _ _ _ _ _ * * _ _ _ _ _ _ _ _ _
# _ _ _ _ _ _ _ _ _ _ _ _ * * * _ * * _ _ _ _ _ _ _ _ _ _
# _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ * _ _ _ _ _ _ _ _ _ _
# _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ * _ _ _ _ _ _ _ _ _ _
# _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _
# _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ * _ _ _ _ _ _ _ _ _ _ _
# _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ * _ _ _ _ _ _ _ _ _ _ _
# _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _
# _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ * _ _ _ _ _ _ _ _ _ _ _ _
# _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ * _ _ _ _ _ _ _ _ _ _ _ _
# _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _
# _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _

# 0: 0.00
# 1: 0.00
# 2: 0.00
# 3: 0.00
# 4: 0.01
# 5: 0.00
# 6: 0.00
# 7: 0.02
# 8: 0.00
# 9: 0.96 << 🙂

./wavelet-scatter
# _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _
# _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _
# _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _
# _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _
# _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _
# _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _
# _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _
# _ _ _ _ _ _ _ _ _ _ _ * _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _
# _ _ _ _ _ _ _ _ * * * * * * * * _ * * _ _ _ _ _ _ _ _ _
# _ _ _ _ _ _ _ _ * * * * * * * * * * * * _ _ _ _ _ _ _ _
# _ _ _ _ _ _ _ _ _ _ _ _ * _ * * * * * * _ _ _ _ _ _ _ _
# _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ * * * _ _ _ _ _ _ _ _ _
# _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ * * * _ _ _ _ _ _ _ _ _
# _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ * * * _ _ _ _ _ _ _ _ _ _
# _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ * * * _ _ _ _ _ _ _ _ _ _
# _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ * * * _ _ _ _ _ _ _ _ _ _
# _ _ _ _ _ _ _ _ _ _ _ _ _ _ * * * _ _ _ _ _ _ _ _ _ _ _
# _ _ _ _ _ _ _ _ _ _ _ _ _ * * * _ _ _ _ _ _ _ _ _ _ _ _
# _ _ _ _ _ _ _ _ _ _ _ _ * * * * _ _ _ _ _ _ _ _ _ _ _ _
# _ _ _ _ _ _ _ _ _ _ _ _ * * * _ _ _ _ _ _ _ _ _ _ _ _ _
# _ _ _ _ _ _ _ _ _ _ _ _ * * _ _ _ _ _ _ _ _ _ _ _ _ _ _
# _ _ _ _ _ _ _ _ _ _ _ _ * * _ _ _ _ _ _ _ _ _ _ _ _ _ _
# _ _ _ _ _ _ _ _ _ _ _ * * * _ _ _ _ _ _ _ _ _ _ _ _ _ _
# _ _ _ _ _ _ _ _ _ _ _ * * * _ _ _ _ _ _ _ _ _ _ _ _ _ _
# _ _ _ _ _ _ _ _ _ _ _ * * _ _ _ _ _ _ _ _ _ _ _ _ _ _ _
# _ _ _ _ _ _ _ _ _ _ _ * * _ _ _ _ _ _ _ _ _ _ _ _ _ _ _
# _ _ _ _ _ _ _ _ _ _ _ _ * _ _ _ _ _ _ _ _ _ _ _ _ _ _ _
# _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _

# 0: 0.00
# 1: 0.00
# 2: 0.00
# 3: 0.00
# 4: 0.00
# 5: 0.00
# 6: 0.00
# 7: 1.00 << 🙂
# 8: 0.00
# 9: 0.00
```

### TODOS

Functions to implement

- [x] gabor_wavelet_2d
- [x] morlet_wavelet_2d
- [x] modulus
- [x] convert_to_complex
- [x] periodize_filter_fft
- [x] dft
- [x] fft
- [x] ifft
- [x] fft2D
- [x] ifft2D
- [x] filter_bank
- [x] pad
- [x] cdgmm
- [x] subsample_fourier
- [x] unpad
- [x] softmax
- [x] predict
- [ ] upgrade to ggml tensors 
  - [ ] needs to be function by function starting with simply adding the library and serde for testing
  - [ ] specifically the fourier transform functions since they may be the bottleneck and are likely to be used in the future
  - [ ] also we should implement the masking in a much more efficient way

## How the logistic regression model trained

```bash
python3 scripts/train.py
```

## Why?

While much of the recent AI excitement is around LLM's and the transformer. There are many other promising AI architectures that are worth exploring. I'm particularly interested in the wavelet scattering transform and how it can be used to build a simple and interpretable AI model.

Wavelet scattering transforms are a type of convolutional neural network that are invariant to translation, stable to deformations, and provide a multiscale representation of the input. They are a great alternative to the convolutional neural network and have been shown to be effective in many applications. Especially when there is limited data available and the input is related to the natural world (e.g. images, audio, spectrograms, etc.).

## References

I specifically want to shout out [Kymatio](https://github.com/kymatio/kymatio) and the great work they've done with their [wavelet scattering transform](https://www.kymat.io/) library. I've learned a lot from their code and it's been a great resource for me to learn about wavelets and scattering transforms. `wst.cpp` is largely a re-implementation of their work in C++.

- [Group Invariant Scattering - Stéphane Mallat (paper)](https://www.di.ens.fr/~mallat/papiers/ScatCPAM.pdf)
- [Stéphane Mallat: "Scattering Invariant Deep Networks for Classification, Pt. 1 (video)"](https://www.youtube.com/watch?v=4eyUReyIPXg)
- [A ConvNet that works well with 20 samples: Wavelet Scattering (article)](https://towardsdatascience.com/-a-convnet-that-works-on-like-20-samples-scatter-wavelets-b2e858f8a385)
- [Wavelet Scattering (matlab docs)](https://www.mathworks.com/help/wavelet/ug/wavelet-scattering.html)
- [A better way to define and describe Morlet wavelets for time-frequency analysis (paper)](https://www.biorxiv.org/content/biorxiv/early/2018/08/21/397182.full.pdf)
- [Kymatio: Wavelet scattering in Python (site)](https://www.kymat.io/)
- [Kymatio: Scattering Transforms in Python (paper)](https://jmlr.org/papers/volume21/19-047/19-047.pdf)
