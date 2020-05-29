---
layout: page
title: Research
permalink: /research/
---
 <hr size="6" noshade> 

My research interests lie primarily in the area of geophysical inverse problems, applied mathematics and computational science. I am particularly interested in numerical weather prediction and tsunami science to understand natural hazards and to improve the knowledge of their dynamics. In my research, I am trying to answer two fundamental questions: 1) how can we reduce forecast error significantly and 2) how can we reconstruct initial conditions more quickly and accurately? I am keen to develop new algorithms based on data assimilation with artificial intelligence in order to reduce forecast error in both the fields. 

I have implemented the data assimilation method in numerical weather prediction to find optimal locations for adaptive observations for reducing forecast error. Recently, I have successfully applied data assimilation method with ship-borne GPS data to examine the possibility of using the ship data in tsunami forecasting in the Cascadia subduction zone. Currently, I am developing a methodology using an adjoint sensitivity method with Green’s function based Time Reverse Imaging (GFTRI) to identify the optimal sites for deploying new sea-floor sensors in the Cascadia subduction zone offshore Washington and Oregon.

<!--During my PhD, I developed three different source inversion techniques to estimate initial tsunami source in order to understand source mechanism of large tsunami triggered by megathrust and tsunami earthquake as well as submarine landslide. I developed the first time reverse imaging that has potential to be used in tsunami forecasting at far-field. At Earthquake Research Institute, University of Tokyo, Japan, I introduced an adjoint sensitivity (AS) method to identify the optimal set of stations that improves the performance of the source inversion method. The AS method has the ability to identify erroneous tide gauges that degrade the inversion result. -->

{% include image.html url="/images/ship_fig.png" caption="Data assimilation: Comparison of tsunami height from referenced model and the model by assimilating ship data at fixed locations. Left column shows the result with elevation data, middle one with velocity and right one shows the combination of elevation and velocity data at 55 ship locations." width=900 align="left" %}


<h4> Scientific Softwares:</h4>

<sc> GFTRI method </sc>
<hr size="1">
GFTRI is a tsunami source inversion method based on time reverse imaging. It stands for "Green's Function based Time Reverse Imaging". This method is defferent than the traditional least squares method. Instead of solving the evolved linear system by least squares method, it uses Green's functions (GFs) to estimate unit source amplitude by convolving them with observed waveforms in reversed time order. For details, see the following articles. The current version of the code has been used for estimating sea surface displacement due to the 2018 Kodiak earthquake tsunami. The code can be found in the [<span style="color:blue"> Github repository</span>](https://github.com/mjhossen/GFTRI). It requires fault parameters, GFs and observation stored in .h5 file. The data files are put in the Input folder except GFs file. The GFs file cannot be uploaded to the repository due to it's large size. If you want to run the code with our data set, please contact me through the email: md.hossen@colorado.edu or mjhossen55@gmail.com.

**M. J. Hossen**,  Sheehan, A.F. and Satake, K (2020). [<span style="color:black">A Multi-fault Model Estimation from Tsunami Data: An Application to the 2018 M7.9 Kodiak Earthquake</span>](https://link.springer.com/article/10.1007/s00024-020-02433-z). Pure Appl. Geophys. 177, 1335--1346. https://doi.org/10.1007/s00024-020-02433-z.

**M. J. Hossen**, P. R. Cummins, J. Dettmer, and T. Baba (2015). [<span style="color:black">Time reverse imaging for far-field tsunami forecasting: 2011 Tohoku earthquake case study</span>](https://doi.org/10.1002/2015GL065868). Geophys. Res. Lett., 42, 9906--9915.

<sc>Adjoint sensitivity method</sc>
<hr size="1">

An adjoint sensitivity method has been developed to find an optimal set of stations for tsunami source inversion. The method is able to identify the erroneous stations that contribute largest error in model space. The method has been applied to the 2009 Samoa earthquake tsunami. The inversion result improves significantly due to the use of the optimal set. The details of the method can be found in the following paper. If you are interested, please contact me to get the code through the email: md.hossen@colorado.edu or mjhossen55@gmail.com. 

**M. J. Hossen**, Gusman, A. R., Satake, K., and Cummins, P. R. (2018). [<span style="color:black">An adjoint sensitivity method applied to time reverse imaging of tsunami source for the 2009 Samoa earthquake</span>]( https://doi.org/10.1002/2017GL076031). Geophysical Research Letters, 45, 627-636. 



<!--My research has to date focused on two broad sets of question. The first and most active part of my research agenda focuses on the effect of external threat, especially to the territorial integrity of the state, on the political attitudes of citizens. Here, I have a keen interest in what happens to citizen attitudes toward the government and what type of authority the government should have. The second part of my research agenda is rooted in the peace science approach to the study of international conflict. Here, my research has explored either the conditions of militarized interstate dispute (MID) onset and escalation or how we should understand code these events. In addition, I have also published various items on political topics of interest to me in light of current events. I offer [a three-page research statement](/docs/svm-research-statement.pdf) that summarizes and contextualizes my different research agendas. [My CV](http://svmiller.com/cv/) contains some more information about works in progress and where some of these works in progress are in the peer review process.

I also provide titles for some working papers and works in progress below. I provide full links for these papers when I believe they are ready for peer review. Feel free to contact me if you are interested in some of these projects. [My CV](http://svmiller.com/cv/) contains more information about where some of these projects are in the peer review process.

I also offer [a three-page research statement](/docs/svm-research-statement.pdf) that summarizes and contextualizes my different research agendas. -->
 



