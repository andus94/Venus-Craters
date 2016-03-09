# Venus-Craters

An analysis of the craters of Venus from data gathered by the Lunar and Planetary Institute. We are interested in the location (longitude and latitude) and the elevation levels of each crater. Using R we map the craters of Venus on a 3D model use this dataset to predict unknown elevation levels of craters across Venus. We also determine the distribution of the craters on Venus

## R

You will need the following packages installed in R:

* geosphere
* sphereplot
* knitr
* rgl
* plyr
* ggplot2

To install the packages use the following code in R:

```
install.packages("Your Package Name")
```

In order to render the html output of the 3D model of the locations of the craters you need to include the following code:
```
knit_hooks$set(webgl = hook_webgl)
```

Follow along the R markdown file for any confusion!
