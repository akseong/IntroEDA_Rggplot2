# Data Exploration and Visualization using R and ggplot2

# Description
This course is intended to help people with basic experience using R take their first steps on a data analysis. We provide a quick overview of introductory R programming, then focus on using R and ggplot2 for data exploration and visualization. 

Notes: 
1. planned topics for each session may change as time constraints dictate.
2. slides/exercises still in progress at this time

Please follow the [Pre-Workshop Instructions](#Instructions) prior to coming to the workshop.


# Syllabus
## Session 1: 10am-noon
[**Part 1: R and RStudio basics:**](https://akseong.github.io/IntroEDA_Rggplot2/slides/Session_1_Rbasics.html)
- data types
- subsetting
- reading/writing data
- constrol structures
- functions

[**Part 2: Basic data exploration and plotting in base R:**](https://akseong.github.io/IntroEDA_Rggplot2/slides/Session_1_introEDA.html)
- summaries
- tables
- plotting different types of data


## Break: noon-1pm
[**Exercise 1**](https://akseong.github.io/IntroEDA_Rggplot2/exercises/Session_1_Rbasics---Exercises.html)


## Session 2: 1pm-3pm
[**Part 1: Introduction to ggplot2 and the "grammar of graphics"**](https://akseong.github.io/IntroEDA_Rggplot2/slides/Session_2_Part1_ggplot2_intro.html)
- understanding the logic and basic syntax of ggplot2
- overlaying geoms
- visualizing strata for comparison

**Part 2: ggplot2: beyond basics with an example**
- data manipulation and preparation
- changing default options


## Break: 3pm-4pm
**Exercise 2**


## Session3: 4pm-5pm
**Worked example: making a choropleth map in ggplot2**



<!-- # Schedule

| 	   Time	    |           				|							|
| ------------- | :-----------------------:	| :-----------------------: |   
| 	8:30-9:00  	| Registration & Breakfast	|							|
| 	9:00-10:15	| [Session 1: Fundamentals of R](http://ucidatascienceinitiative.github.io//IDA-with-R/slides/session_1/slides.html)			| [Shell Code](http://ucidatascienceinitiative.github.io//IDA-with-R/slides/session_1/shell_code.R), [Complete Code](http://ucidatascienceinitiative.github.io//IDA-with-R/slides/session_1/complete_code.R) |
| 	10:15-10:45	| [Exercise 1](http://ucidatascienceinitiative.github.io//IDA-with-R/exercises/ex_1.html)					| |
| 	10:45-11:00	| Break						| |
| 	11:00-11:15	| [Discuss Exercise 1 Solutions](http://ucidatascienceinitiative.github.io//IDA-with-R/solutions/ex_1_soln.html) | [Chris' Solution Code](http://ucidatascienceinitiative.github.io//IDA-with-R/solutions/ex_1.R)   |
|   11:15-12:15 | [Session 2: Exploratory Data Analysis](http://ucidatascienceinitiative.github.io//IDA-with-R/slides/session_2/slides.html) 	| [Shell Code](http://ucidatascienceinitiative.github.io//IDA-with-R/slides/session_2/shell_code.R), [Complete Code](http://ucidatascienceinitiative.github.io//IDA-with-R/slides/session_2/complete_code.R) |
| 	12:15-12:30	| [Exercise 2](http://ucidatascienceinitiative.github.io//IDA-with-R/exercises/ex_2.html)					| |
| 	12:30-1:00 	| Lunch						| |
| 	1:00-1:15 	|  [Discuss Exercise 2 Solutions](http://ucidatascienceinitiative.github.io//IDA-with-R/solutions/ex_2_soln.html) | [Chris' Solution Code](http://ucidatascienceinitiative.github.io//IDA-with-R/solutions/ex_2.R)   |
| 	1:15-2:30	| [Session 3: Linear Regression](http://ucidatascienceinitiative.github.io//IDA-with-R/slides/session_3/slides.html)			| [Shell Code](http://ucidatascienceinitiative.github.io//IDA-with-R/slides/session_3/shell_code.R), [Complete Code](http://ucidatascienceinitiative.github.io//IDA-with-R/slides/session_3/complete_code.R) |
| 	2:30-3:15	| [Exercise 3](http://ucidatascienceinitiative.github.io//IDA-with-R/exercises/ex_3.html)					| |
| 	3:15-3:30	| Break						| |
| 	3:30-4:00	| [Discuss Exercise 3 Solutions](http://ucidatascienceinitiative.github.io//IDA-with-R/solutions/ex_3_soln.html) | [Chris' Solution Code](http://ucidatascienceinitiative.github.io//IDA-with-R/solutions/ex_3.R)	|
| 	4:00-4:50	| [Session 4: Logistic Regression](http://ucidatascienceinitiative.github.io//IDA-with-R/slides/session_4/slides.html)			| [Shell Code](http://ucidatascienceinitiative.github.io//IDA-with-R/slides/session_4/shell_code.R), [Complete Code](http://ucidatascienceinitiative.github.io//IDA-with-R/slides/session_4/complete_code.R) |
| 	4:50-5:00	| [Course Evaluation Survey](https://docs.google.com/forms/d/e/1FAIpQLSdGC3RVoEzulw9STMBAWvXTahUetxc-PrGhNRW5AmtQ1ZMwMw/viewform)		| |
 -->

# <a name="Instructions"></a>Pre-Workshop Instructions
### Step 1: Download and install R
First, visit [The R Project for Statistical Computing](https://www.r-project.org/). Click on `CRAN` under the Download section on the left-hand side of the page. Then, click on any of the nearby websites under the USA section near the bottom of the page.  Download R for your platform (Linux, Mac, or Windows), open the downloaded file and follow the instructions.

### Step 2: Download and install RStudio
RStudio is a set of integrated tools designed to help you be more productive with R. Also, it is far more user-friendly than base R. You will be doing essentially all of your programming in RStudio. To download RStudio, visit the [download page](https://www.rstudio.com/products/rstudio/download/), scroll down to "Installers for Supported Platforms," and click on the appropriate installer for your platform. Finally, open the downloaded file and follow the instructions.

### Step 3: Install required R packages
In R, packages are used to share code. A package bundles together code, data, documentation, and tests. As of May 2020, there were >15,000 packages available on the Comprehensive R Archive Network, or CRAN. This huge variety of packages is one of the reasons that R is so successful: the chances are that someone has already solved a problem that you’re working on, and you can benefit from their work by downloading their package and using their code.

In this workshop, we will be using a number of packages-- `ggplot2`, `dplyr`, `maps`. I suggest installing them before our sessions begin. There are a few ways to do this (which we will discuss more during the workshop). For now, open up RStudio and try to run the following lines of code

```r
install.packages("ggplot2", dependencies = TRUE)
install.packages("dplyr", dependencies = TRUE)
install.packages("maps", dependencies = TRUE)
```
Additional "dependencies," or other packages necessary to run the three above, will also be installed. This make take a few minutes.

### Step 4: Download the data
We will be working with a few datasets throughout the day.  Downloading these datasets beforehand may make things a bit easier / faster for you.  Make a folder for this class, then make a sub-folder in that named "data", and save these in there.  
[nytimes data]("https://raw.githubusercontent.com/nytimes/covid-19-data/master/us-counties.csv")
[election data]("https://raw.githubusercontent.com/tonmcg/US_County_Level_Election_Results_08-16/master/2016_US_County_Level_Presidential_Results.csv")
[census data]("https://www2.census.gov/programs-surveys/popest/datasets/2010-2019/counties/totals/co-est2019-alldata.csv")