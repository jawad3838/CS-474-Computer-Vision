# CS-474-Computer-Vision
This repository contains all the lab assignments that were completed during my Computer Vision course.

## Pre-requisites
You need to have the following libraries installed on your system in order to run the codes. Python 3 was used for all tasks.
* OpenCV
* Numpy
* Matplotlib
* Tensorflow
* Keras

### Projects

#### Noise and Template Matching
We examine the effect of different noise types on an image and which filter rectifies them the best.

<table>
  <tr>
    <td colspan="3" align="center">Original Image</td>
  </tr>
  <tr>
    <td colspan="3" align="center"><img src="https://github.com/jawad3838/CS-474-Computer-Vision/blob/master/Noise%20and%20Template%20Matching/lena.jpg"/></td>
  </tr>
  <tr>
    <td>Gaussian Noise</td>
    <td>Salt and Pepper Noise</td>
    <td>Rayleigh Noise</td>
  </tr>
  <tr>
    <td><img src="https://github.com/jawad3838/CS-474-Computer-Vision/blob/master/Noise%20and%20Template%20Matching/gaussian_noise.jpg"/></td>
    <td><img src="https://github.com/jawad3838/CS-474-Computer-Vision/blob/master/Noise%20and%20Template%20Matching/saltpepper_noise.jpg"/></td>
    <td><img src="https://github.com/jawad3838/CS-474-Computer-Vision/blob/master/Noise%20and%20Template%20Matching/rayleigh_noise_image.jpg"/></td>
  </tr>
</table>

<table>
  <tr>
    <td colspan="3" align="center"><b>Effect of Average Filter</b></td>
  </tr>
  <tr>
    <td>Gaussian Noise</td>
    <td>Salt and Pepper Noise</td>
    <td>Rayleigh Noise</td>
  </tr>
  <tr>
    <td><img src="https://github.com/jawad3838/CS-474-Computer-Vision/blob/master/Noise%20and%20Template%20Matching/AverageOnGaussian.png"/></td>
    <td><img src="https://github.com/jawad3838/CS-474-Computer-Vision/blob/master/Noise%20and%20Template%20Matching/AverageOnS%26P.png"/></td>
    <td><img src="https://github.com/jawad3838/CS-474-Computer-Vision/blob/master/Noise%20and%20Template%20Matching/AverageOnRayleigh.png"/></td>
  </tr>
</table>

<table>
  <tr>
    <td colspan="3" align="center"><b>Effect of Mean Filter</b></td>
  </tr>
  <tr>
    <td>Gaussian Noise</td>
    <td>Salt and Pepper Noise</td>
    <td>Rayleigh Noise</td>
  </tr>
  <tr>
    <td><img src="https://github.com/jawad3838/CS-474-Computer-Vision/blob/master/Noise%20and%20Template%20Matching/MeanOnGaussian.png"/></td>
    <td><img src="https://github.com/jawad3838/CS-474-Computer-Vision/blob/master/Noise%20and%20Template%20Matching/MeanOnS%26P.png"/></td>
    <td><img src="https://github.com/jawad3838/CS-474-Computer-Vision/blob/master/Noise%20and%20Template%20Matching/MeanOnRayleigh.png"/></td>
  </tr>
</table>

<table>
  <tr>
    <td colspan="3" align="center"><b>Effect of Median Filter</b></td>
  </tr>
  <tr>
    <td>Gaussian Noise</td>
    <td>Salt and Pepper Noise</td>
    <td>Rayleigh Noise</td>
  </tr>
  <tr>
    <td><img src="https://github.com/jawad3838/CS-474-Computer-Vision/blob/master/Noise%20and%20Template%20Matching/MedianOnGaussian.png"/></td>
    <td><img src="https://github.com/jawad3838/CS-474-Computer-Vision/blob/master/Noise%20and%20Template%20Matching/MedianOnS%26P.png"/></td>
    <td><img src="https://github.com/jawad3838/CS-474-Computer-Vision/blob/master/Noise%20and%20Template%20Matching/MedianOnRayleigh.png"/></td>
  </tr>
</table>

Now we examine the result of using the template matching function in OpenCV to find Waldo (the guy in a striped T-shirt) in a scene.

<table>
  <tr>
    <td>Template</td>
    <td colspan="2" align="center">Matched Result</td>
  </tr>
  <tr>
    <td><img src="https://github.com/jawad3838/CS-474-Computer-Vision/blob/master/Noise%20and%20Template%20Matching/template.png"/></td>
    <td><img src="https://github.com/jawad3838/CS-474-Computer-Vision/blob/master/Noise%20and%20Template%20Matching/matchedTemplate.png"/></td>
  </tr>
  </table>
  


