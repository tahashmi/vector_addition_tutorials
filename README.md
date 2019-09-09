Vector Additon
==============

The vector addition sample adds two vectors A and B to produce C, where C<sub>i</sub> = A<sub>i</sub> + B<sub>i</sub>. In this particular case the vectors A and B are filled with trigonometric data and summed. Both C and Fortran versions are presented where applicable.

Compiling OpenCL (the other way) =>
apt-get install ocl-icd-* opencl-headers -y
cc vecAdd.c -o vecAdd.out -lOpenCL -lm
