<!--
*** README Template
***
-->

<!--
*** Markdown "reference style" links are used for readability.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->

<!-- BANNER / LOGO -->
<br />
<p align="center">
  <a href="https://github.com/raj-vijay/da">
    <img src="images/GoogleAI.png" alt="Logo" width="334" height="81">
  </a>

  <h3 align="center">Google OR Tools </h3>

  <p align="center">
    Repository for Decision Analytics
    <br />
    <a href="https://developers.google.com/optimization"><strong>Explore OR Tools »</strong></a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
## Table of Contents

* [Decision Analytics](#DecisionAnalytics)
* [Repositories](#Repositories)
  * [Prerequisites](#prerequisites)
* [References](#References)



<!-- ABOUT -->
## Decision Analytics

Decision analytics is a collection of methodologies and tools to facilitate optimal decision making based on data. Many real-world problems require the optimization of an objective function while satisfying underlying constraints. 
Real world problems are formulated by identifying variables and their mutual constraints. The objective function is often formulated to quantify “how good” a solution is and an algorithmic approach is taken to find the “best” solution for the given problem. 

The most challenging task is typically creating a suitable model for a real-world application. This include:
* Identifying relevant decision variables
* Identifying necessary auxiliary variables
* Identifying application specific constraints linking variables with data
* Identifying internal constraints representing implicit assumptions and linking variables with each other
* Identify an objective function to characterise the optimisation goal
* Choose the most suitable tools and algorithms to solve the problem

<!-- REPO -->
### Repositories

The repository for Decision Analytics is like a folder or storage space that contains all the files such as code, documentation, images, and is more related to my personal endeavours on the Decision Analytics problems using Google OR tools.

<!-- PREREQUISITES -->
### Prerequisites

For datasets involving Kaggle, the following approach is used for integration.

Steps for Integration
1. Installing Kaggle Package for Google Colab Integration


```sh
# Install kaggle package for data integration
!pip install kaggle
```

2. Intergating security and authentication using the kaggle.json API token for authentication
```sh
# Create folder on the Google Colab file system
!mkdir ~/.kaggle
!cp /content/kaggle.json ~/.kaggle/kaggle.json

# Protect Kaggle JSON file for security reasons
!chmod 600 /root/.kaggle/kaggle.json
```

<!-- REFERENCES -->
## References

* [Google OR Tools]( https://developers.google.com/optimization)
* [Google Colaboratory]( https://colab.research.google.com/notebooks/intro.ipynb)
* []()



