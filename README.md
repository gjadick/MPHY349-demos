# MPHY349-demos

A collection of interactive Jupyter notebooks to demonstrate concepts for the course MPHY34900 "Mathematics for Medical Physics."

![Backprojection animation](backprojection-demo/examples/fbp_animation.gif)


## image-filter-demo

Demo of 2D convolution utility with a few example images and filters. For example uniform kernels create blur (reducing noise), or a Sobel filter detects edges along a given orientation.

![Blur convolution](image-filter-demo/examples/ones_7.png)

![Sobel convolution](image-filter-demo/examples/sobel_v.png)


## radon-transform-demo

Demo of the 2D Radon Transform, starting with single line integrals then full 2D sinograms with line integral pixel values.

![Line profile example](radon-transform-demo/examples/line_profile.png)

![2D Radon Transform example](radon-transform-demo/examples/sino.png)


## backprojection-demo

Demo of 2D backprojection, inverting the output sinograms from radon-transform-demo. Compares backprojection result for raw data and filtered data.

![Sinogram row comparison](backprojection-demo/examples/row_compare.png)

![Reconstruction comparison](backprojection-demo/examples/fbp_536.png)


## noise-demo

Demonstration of signal vs. background for different signal-to-noise ratios.

![SNR comparison](noise-demo/examples/snr.png)

