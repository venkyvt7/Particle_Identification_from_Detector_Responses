<h1> Particle Classifier Using Machine Learning.</h1>

## Table of Contents

* [About the Project](#about-the-project)
  * [Introduction](#Introduction)
  * [Built With](#Built-With)
  * [Algorithms/Classification Models Used](#Algorithms/Classification-Models-Used)
  * [Data Set](#Data-Set)
* [Implemention](#Implemention)
* [Finding The Best Classification Model](#Finding-The-Best-Classification-Model)
* [Conclusion](#Conclusion)
* [Author](#Author)
## About The Project

### Introduction

<li>This Project is Based On Particle Classification.</li>
</br>
  <li> In order to analyse these data is necessary understand some basic concepts. </li>
  </br>
<ul>

 
 <li> <b> The Standard Model </b> -
The building blocks of matter are elementary particles. 
The Standard Model also studies the interaction of these particles through fundamental forces (strong, weak and electromagnetic). For every type of particle there also exists
a corresponding antiparticle.
</li>

<li>
<b> Pion</b>
In particle physics, a pion (or a pi meson, denoted with the Greek letter pi: π) is any of three subatomic particles: 
π0, π+, and π−. Each pion consists of a quark and an antiquark and is therefore a meson. 
</li>

<li>
 So in this project We are Classifying whether the particle is <b> Pion </b> or not.
</li>

</ul>

### Built With

 <li> Python </li>
 <li> Python Libraries Used</li>
  <ul> <li> MatplotLib </li> 
        <li> Pandas </li>
        <li> Numpy</li>
        <li> Seaborn </li>
        <li> Scikit-Learn</li>
        </ul>
  </ul>

### Algorithms/Classification Models Used

<li> Logistic Regression</li>
<li>  K-Nearest Neighbors </li>
<li> Decision Tree Learning</li>
<li> Random forest </li>

### Data Set
<p>
<li> This Large dataset is from <a href="https://www.kaggle.com/naharrison/particle-identification-from-detector-responses/home"> Kaggle </a> ,a simulation
of electron-proton inelastic scattering measured by a particle detector system. </li>
</p>


## Implementation 
<p>
This Project is Implementated on Python Notebook Jupyter  <a href="https://github.com/venkyvt7/Particle_Identification_from_Detector_Responses/blob/main/ParticleClassifier.ipynb" > Link </a>
</p>


## Finding The Best Classification Model

<p>
So for Model With Best Accuracy Score will be the best classification model
</p>

<table>
  <tr>
    <th>Classification Model Name</th>
    <th>Accuracy Score (in %)</th>
  </tr>
  <tr>
    <td> Logistic Regression</td>
    <td>94.98</td>
  </tr>
 <tr>
    <td> K-Nearest Neighbors </td>
    <td>94.01</td>
  </tr>
  <tr>
    <td> Decision Tree </td>
    <td>96.31</td>
  </tr>
  
   <tr>
    <td> Random Forest</td>
    <td>97.43</td>
  </tr>
  
  
</table>

## Conclusion 
  <p>
  So,We conclude that Random Forest Classification with Accuracy of 97.43% is Best model that can be used for Classification.
  </p>

## Author
<li> Venkatesh Tripathi </li>

