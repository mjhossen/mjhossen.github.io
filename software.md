---
layout: page
title: Software Development
permalink: /software/
---
 <hr size="10" noshade> 

## GFTRI method
<hr size="1">
GFTRI is a tsunami source inversion method based on time reverse imaging. It stands for "Green's Function based time Reverse Imaging". This method is defferent than the traditional least squares method. Instead of solving the evolved linear system by least squares method, it uses Green's functions (GFs) to estimate source amplitude by convolving them with observed waveforms in reversed time order. For details, see the following articles. The current version of the code has been used for estimating sea surface displacement due to the 2018 Kodiak earthquake tsunami. The code can be found in the [<span style="color:blue"> github repository</span>](https://github.com/mjhossen/GFTRI). It requires fault parameters, GFs and observation data stored in .h5 file. The data files are put in the Input folder except GFs file. GFs file cannot be uploaded to the repository due to it's large size. If you want to run the code with our data set, please contact me through the email: md.hossen@colorado.edu or mjhossen55@gmail.com.

**M. J. Hossen**,  Sheehan, A.F. and Satake, K (2020). [<span style="color:black">A Multi-fault Model Estimation from Tsunami Data: An Application to the 2018 M7.9 Kodiak Earthquake</span>](https://link.springer.com/article/10.1007/s00024-020-02433-z). Pure Appl. Geophys. 177, 1335--1346. https://doi.org/10.1007/s00024-020-02433-z.

**M. J. Hossen**, P. R. Cummins, J. Dettmer, and T. Baba (2015). [<span style="color:black">Time reverse imaging for far-field tsunami forecasting: 2011 Tohoku earthquake case study</span>](https://doi.org/10.1002/2015GL065868). Geophys. Res. Lett., 42, 9906--9915.

## Adjoint sensitivity method
<hr size="1">

An adjoint sensitivity method has been developed to find optimal set of stations for tsunami source inversion. The method is able to identify the erroneous stations that contribute largest error in model space. The method has been applied to the 2009 Samoa earthquake tsunami. The inversion result improves significantly due to the use of the optimal set. The details of the method can be found in the paper:

**M. J. Hossen**, Gusman, A. R., Satake, K., and Cummins, P. R. (2018). [<span style="color:black">An adjoint sensitivity method applied to time reverse imaging of tsunami source for the 2009 Samoa earthquake</span>]( https://doi.org/10.1002/2017GL076031). Geophysical Research Letters, 45, 627-636. 


