# Machine Learning Archive  
The below is an simple introduction of useful books for statistical modeling and proeprocessing/feature engineering.

## ML Overview
### 1. Applied Machine Learning
Applied ML workshop by Max Kuhn from useR2018 Conference
Max Kuhn has talked about Applied Machine Learning in RStudio::Conf 2017. The material is stored in [this repository](https://github.com/kojimizu/rstudio-conf-2018). The latest repository is [here](https://github.com/topepo/rstudio-conf-2019).  

### 📚 Hands on Machine Learning with R
Hands-on Machine Learning with R: An applied book covering the fundamentals of machine learning with R.  
This book covers multiple models 1) gm, 2) regularized glm, 3) random forest and 4) gradient boosting methods.  
From 2018 to 2019 January  
📚 Book: http://bit.ly/HOML_with_R  
📦 Repo: https://github.com/bradleyboehmke/hands-on-machine-learning-with-r   

### 📚 UC Business analyrics by R
This material from the below page covers basic R techniques, descrptive analytics, and predictive analytics.  
📚 Book: University of Cincinatti - http://uc-r.github.io  

- Predictive analyitics: 
    - Supervised learning: Linear, Naive Bayes, Regularized Regression, MARS, Regression Tree, Random Forests, GBM, Discriminant Analysis, SVM
    - Unsupervised learning: PCA
    - Time series analysis: Exponential smoothing, MA/AR
    - DL: Regression DNN, Classification DNN

## Modeling Resources
### 📦 Caret
__Caret package introduction by Max Kuhn (Bookdown)__
A package for ML modeling with pre-processing techniques 
📚 Book: http://topepo.github.io/caret/
📦 Repo:   https://github.com/topepo/caret
```{R}
# Avaiable from CRAN
install.packages("caret")
```
### 📦 Tidymodels  
Tidymodels is a multi-package containing modern tidyverse-based packages. I understand no text covers tidymodels as of now, and I have prepared a material covering each package's vignettes.  

📦 Repo: https://github.com/tidymodels/tidymodels
```{R}
# Avaiable from CRAN
install.packages("tidymodels")
```
- broom:  tidy, augment, glance for model interpretation support
- rsample:  data resampling 
- recipes:  pre-processing functions (similar to caret)
- parsnip:  modeling functions 

Useful blog posts
recipes: http://www.rebeccabarter.com/blog/2019-06-06_pre_processing/  
tidymodels: https://rviews.rstudio.com/2019/06/19/a-gentle-intro-to-tidymodels/  

## Feature Engineering Resouces 
### 📚 Feature Engineering and Selection (FES)  
A Bookdown page prepared by Max Kuhn  
📚 Book: http://www.feat.engineering/  
📦 Repo: https://github.com/kojimizu/FES  

### 📚 Feature Engineering Book
by Alice Zheng  

=========================================
# Modern R 
## Modern commands
### 📚 R for Data Science
Basic commands with tidyverse is summarised.
📚 Book: https://r4ds.had.co.nz/  
The excercise solution can be found on Bookdown as well.

### 📚 Modern R with Tidyverse  
Bookdown material is available [here](https://b-rodrigues.github.io/modern_R/), covering:

1. Hello R and RStudio
2. object, types
3. Load data (Reading and Writing)
4. Descriptive statistics and data management
5. Graphs
6. Statistical models
7. Defining your own functions
8. _Functional programming__
9. Package development
10. Further topics

Datacamp:
- 🎥 [Machine Learning in the Tidyverse](https://www.datacamp.com/courses/machine-learning-in-the-tidyverse).

## Purrr material 
### RStudio 
https://purrr.tidyverse.org/  

### Happy Purrrr 
- 🎥 [A tutorial video](https://resources.rstudio.com/wistia-rstudio-conf-2017/happy-r-users-purrr-tutorial-charlotte-wickham) by Charotte Wickhkm. THe DataCamp courses are useful for code practice.

Datacamp
 - 🎥 [Functional progamming with purrr](https://www.datacamp.com/courses/foundations-of-functional-programming-with-purrr)
 
### Case study of Purrr
Lessons and Examples by Jenny Brian: 
📚 Web: https://jennybc.github.io/purrr-tutorial/  
- Background basics
- Core purrr lessons
- Worked examples 

=========================================
## Visualization
### 📚 Data visualition - A practical introduction  
by Kieran Healy.   
📚 Book: http://socviz.co/index.html.

### 📚 R Graphics cookbook
by Winston Chang
📚 Book: https://r-graphics.org/  
Another useful website is Cookbook for R: covering other topics online: http://www.cookbook-r.com/

=========================================
## Uni class
### CS229
Machine learning course by Andrew Ng from Stanford University  
🎥Video and 📚Material : http://cs229.stanford.edu/syllabus.html  

