# TomoREU2021: Point-of-care Tomographic Imaging
Code written to solve tomographic imaging problems during an REU/RET at Emory University during the summer of 2021.

The research team, led by Dr. James Nagy from Emory's Mathematics Department, consists of 4 student fellows:
1.  Mai Phuong Pham Huynh
2. Manuel Santana
3. Ana Castillo

In this project, we aim to use computational method to develop a numerical method to jointly estimate the geometry parameters of the portable CT scan device and to reconstruct the image.

For full functionality the following matlab packages and toolboxes should be installed.
* [Matlab Parallel Computing Toolbox](https://www.mathworks.com/products/parallel-computing.html)
* [Matlab Optmization Toolbox](https://www.mathworks.com/products/optimization.html)
* [IRtools](https://github.com/jnagy1/IRtools)
* [Imfill](https://ctk.math.ncsu.edu/imfil.html)

The GITHUB repository consists of 2 main folders:
1. [Refactor](Refactor) : Contains all the needed code beyond the above toolboxes and packages. It includes a script [Refactored_Example1.m](Refactor/Refactored_Example1.m) which gives a detailed example of how to run the code.
2. [test_image](test_image) : Additional test images. Matlab image processing toolbox will be needed to use these.

The poster of the project can be found [here](https://github.com/phuongmaihuynhpham/TomoREU2021/blob/main/REU_RETPoster.pptx.pdf).
