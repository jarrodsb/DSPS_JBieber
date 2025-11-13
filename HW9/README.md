# PHYS 461 - Homework 9 - Jarrod Bieber

---

## Visualization Examples from the Literature:

**Good Plot:**

![alt text](https://github.com/jarrodsb/DSPS_JBieber/blob/main/HW9/Good_Plot.png "Good Plot")

A histogram of Cepheid variables identified in the Gaia DR3 dataset over G -band magnitudes, compared with those previously identified in literature. From this paper: https://arxiv.org/abs/2206.06207

Reasons why this is a good plot include that it has a Lie Factor (aka Effect Size) of 1, it is clearly labeled, and it has no Chart Junk. It is also representing a managable (less than 7) number of pieces of information. Specifically, there are only 4 elements depicted in the plot legend.



**Bad Plot:**

![alt text](https://github.com/jarrodsb/DSPS_JBieber/blob/main/HW9/Bad_Plot.png "Bad Plot")

A time series plot of school completion rates of Malaysian students. From this paper: https://arxiv.org/abs/2501.18868

This is quite a bad visualization, for several reasons. The information is not sufficiently labeled with units of measurement, and the plot is lacking any sort of legend. The density of time series lines creates ambiguity, particularly in the region around 95-100 (presumably a percentage?). The time series density also creates a distraction that makes it difficult to read the plot.

There are multiple ways in which I would improve this plot. First, I would specify what the unit of measurement is supposed to be on the y-axis, and I would rename the x-axis label to "Year" rather than "Date". Probably the single most effective solution to address the line density issue is to utilize the ***alpha channel*** feature. This would reveal much more of the trajectories of individual lines, and address the issue of ambiguity significantly. If applying an alpha channel transparency isn't enough (which it might not be), I may also attempt to use smaller multiples of data, or utilize a heat map to emphasize a high concentration of paths within a particular percentage range. Finally, this plot really ought to have a caption included with it, to better explain the intended purpose of the plot, what the individual lines mean, and which elements of the plot should readers be drawing their attention to.


---

## Remade Plot from the Homework Assignments:

**Original Plot (HW5)**
![alt text](https://github.com/jarrodsb/DSPS_JBieber/blob/main/HW9/HW5_Original_Plot.png "Original Plot")

**Improved Version**
![alt text](https://github.com/jarrodsb/DSPS_JBieber/blob/main/HW9/HW5_Improved_Plot.png "Improved Plot")

This is a plot originally from HW5 and HW6, depicting Gamma Ray Burst photometry as a function of time elapsed since the triggering event. I changed a few things for improved clarity. First, I changed the colors of the data points for each photometry class. Previously the colors were randomly assigned by MatPlotLib. Now they are more realistic to the actual colors on the spectrum that the photometric bands correspond to. These colors should be more intuitive for an astronomical scientist.

Second, I added alpha channel transparency to the points, to better show the density of points, and remove some of the ambiguity around grounded areas, particularly the points in the V band in the top left of the plot.
