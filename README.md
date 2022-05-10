# ZTF Summer School 2022 Application Assignment

## The Assignment

The demo data set for this part is the Wesenheit index of the OGLE-III fundamental-mode and first overtone classical Cepheids. 

These stars are awesome because you can use them to measure distances. Here's a nice [youtube video](https://www.youtube.com/watch?v=iyisAjHdhas) on these stars.

You'll try to estimate their period-luminosity relationship. 

The Wesenheit index is defined as `W = I - 1.55(V - I)`, and its main advantage over using simply the I or V photometry is that it is insensitive to extinction. It is denoted by 'W' among the data columns. 

Other columns are 'name', the identifier of the star; 'RA0' (in decimal hours) and 'Decl0' (in decimal degrees), celestial coordinates; 'Mode', the mode of the Cepheid ('F' indicates fundamental-mode, '1' indicates first overtone star); 'Cloud', indicating which Magellanic Cloud the star belongs to; 'logP1', the base-10 logarithm of the period in days; 'VI', the colour V-I.

We split the data into LMC and SMC, and then again by mode F and 1 (for you) below:


## Part 1: plot the `W` on the y-axis vs `log(P1)` on x.


<p align="center">
  <img width="600" src="plots\W_vs_logP1.png">
</p>

## Part 2: Fit or estimate straight lines to each of the four samples

<p align="center">
  <img width="600" src="plots\W_vs_logP1_line.png">
</p>

## Part 3: Compute the residuals of each sample to its respective line.

<table border="0">
 <tr>
    <td><b style="font-size:15px">Residuals</b></td>
    <td><b style="font-size:15px">Absolute Residuals</b></td>
 </tr>
 <tr>
    <td>
      <p align="center">
        <img width="400" src="plots\Residual_.png">
      </p>
    </td>
    <td>
      <p align="center">
        <img width="400" src="plots\Residual_Absolute.png">
      </p>
    </td>
 </tr>
 <tr>
    <td><b style="font-size:15px">Square Residuals</b></td>
 </tr>
 <tr>
 <td>      
        <p align="center">
        <img width="400" src="plots\Residual_Square.png">
        </p>
 </td>
 </tr>
</table>

## Part 4: Scatter plot of the residuals as RA (x-axis) vs Dec (y-axis) color-coded by whether they are positive or negative.


<table border="0">
 <tr>
    <td><b style="font-size:15px">Residuals</b></td>
    <td><b style="font-size:15px">Absolute Residuals</b></td>
 </tr>
 <tr>
    <td>
      <p align="center">
        <img width="400" src="plots\Residual_color_.png">
      </p>
    </td>
    <td>
      <p align="center">
        <img width="400" src="plots\Residual_color_Absolute.png">
      </p>
    </td>
 </tr>
 <tr>
    <td><b style="font-size:15px">Square Residuals</b></td>
 </tr>
 <tr>
 <td>      
        <p align="center">
        <img width="400" src="plots\Residual_color_Square.png">
        </p>
 </td>
 </tr>
</table>
