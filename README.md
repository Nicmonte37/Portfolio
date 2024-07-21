
![](images/clipboard-1771797031.png){width="63"}

## Vegan Package Tutorial

## Introduction to Ordianation Functions

##### The repository, Chiaramonte_Tutorial was created for an assignment given in an introductory course on rstudio. I chose to illustrate the Vegan package from CRAN. The assignment instructed the students to choose three functions from the package. I chose Ordihull, Ordiellipse, and Ordisprider. Since I did not have data of my own, I chose to use the Dune data that was assessable from the Vegan package. The Vegan package is used mainly in the ecological field of science. The package utilizes diversity analysis, ordination methods, and determines differences in data sets and produces Constrained Correspondence analysis CCA. The CCA analysis derives two scores with respect to the data: a WA score and a LC score. A WA score is the weighted average of the species, and the LC score represents the linear combination of constraining variables. These scores help to show a relationship between different variables in a data set. The three functions I mentioned previously will plot these points on graphs to help display relationships.

#### **Odihull Function**

###### Odihull graphs work well when there are many data points and samples. The graph draws hulls around groups of samples. The less overlapping, the less likely there are similarities between the variants.

#### **Ordiellipse Function**

###### Ordiellipse graphs add ellipses around the ordihulls with the argument kind=ehull. Just like a Venn diagram, this function allows similarities to be identified.

#### **Ordispider Function**

###### Ordispider graphs connect the WA score to the corresponding LC score of the data with lines. The longer the line, the less there are to be similarities between those data points. I should note that upon researching these methods, I did find that the CCA analysis isn’t the best way to determine relationships between data. However, when presented with large sampling sites with many different variables, analyzing data with the CCA method works best.

##### 

