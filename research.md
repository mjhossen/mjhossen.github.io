---
layout: page
title: Research
permalink: /research/
---

My research interests lie primarily in the area of geophysical inverse problems, applied mathematics and computational science. I am particularly interested in numerical weather prediction and tsunami science to understand natural hazards and to improve the knowledge of their dynamics. In my research, I try to find answer of two fundamental questions: 1) how can we reconstruct initial conditions more quickly and accurately and 2) how can we reduce forecast error significantly? Thus, I am keen to develop new algorithms based on time reverse imaging and data assimilation with machine learning in order to reduce forecast error in both the fields. 

I have implemented a data assimilation (DA) method in numerical weather prediction to find optimal locations for adaptive observations. Recently, I have successfully applied the DA method with ship-borne GPS data to examine the possibility of using the ship data in tsunami forecasting in the Cascadia subduction zone. I am also developing a methodology using an adjoint sensitivity method with Green’s function based Time Reverse Imaging (GFTRI) to identify the optimal sites for deploying new sea-floor sensors in the Cascadia subduction zone offshore Washington and Oregon.

{% include image.html url="/images/ship_fig.png" caption="Data assimilation: Comparison of tsunami height from referenced model and the model by assimilating ship data at fixed locations. Left column shows the result with elevation data, middle one with velocity and right one shows the combination of elevation and velocity data at 55 ship locations." width=900 align="left" %}


<h4> Scientific Softwares:</h4>

<sc> GFTRI method </sc>
<hr size="1">
GFTRI is a tsunami source inversion method based on time reverse imaging. It stands for "Green's Function based Time Reverse Imaging". This method is defferent from the traditional least squares method. Instead of solving the evolved linear system by least squares method, it uses Green's functions (GFs) to estimate unit source amplitude by convolving them with observed waveforms in reversed time order. For details, see the following articles. The current version of the code has been used for estimating sea surface displacement due to the 2018 Kodiak earthquake tsunami. The code can be found in the [<span style="color:blue"> Github repository</span>](https://github.com/mjhossen/GFTRI). It requires fault parameters, GFs and observation stored in .h5 file. The data files are put in the Input folder except GFs file. The GFs file cannot be uploaded to the repository due to it's large size. If you want to run the code with our data set, please contact me through the email: md.hossen@colorado.edu or mjhossen55@gmail.com.

**M. J. Hossen**,  Sheehan, A.F. and Satake, K (2020). A Multi-fault Model Estimation from Tsunami Data: An Application to the 2018 M7.9 Kodiak Earthquake. Pure Appl. Geophys. 177, 1335--1346. https://doi.org/10.1007/s00024-020-02433-z. (<a class="pdf" href="https://link.springer.com/article/10.1007/s00024-020-02433-z" target="_blank">URL</a>)

**M. J. Hossen**, P. R. Cummins, J. Dettmer, and T. Baba (2015). Time reverse imaging for far-field tsunami forecasting: 2011 Tohoku earthquake case study. Geophys. Res. Lett., 42, 9906--9915. (<a class="pdf" href="https://doi.org/10.1002/2015GL065868" target="_blank">URL</a>) 

<sc>Adjoint sensitivity method</sc>
<hr size="1">

An adjoint sensitivity method has been developed to find an optimal set of stations for tsunami source inversion. The method is able to identify the erroneous stations that contribute largest error in model space. The method has been applied to the 2009 Samoa earthquake tsunami. The inversion result improves significantly due to the use of the optimal set. The details of the method can be found in the following paper. If you are interested, please contact me to get the code through the email: md.hossen@colorado.edu or mjhossen55@gmail.com. 

**M. J. Hossen**, Gusman, A. R., Satake, K., and Cummins, P. R. (2018). An adjoint sensitivity method applied to time reverse imaging of tsunami source for the 2009 Samoa earthquake. Geophysical Research Letters, 45, 627-636. (<a class="pdf" href="https://doi.org/10.1002/2017GL076031" target="_blank">URL</a>)

