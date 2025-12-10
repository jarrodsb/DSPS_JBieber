# PHYS 461 - Homework 11
---

## Contributors:

**Jarrod Bieber** - Completed all parts of the assignments, including configuring and training the MLP and CNN autoencoder models, producing the plots, and writing the captions / analysis. I largely worked solo on this assignment, although I did have some discussions and compared results with both Katie Moses and TJ Tomaszewski.

Note - I did run into the "Invalid Notebook" rendering issue in GitHub for this assignment. I got around this issue with the solution suggested - I saved the .ipynb file as a JSON, downloaded it and and opened it in a text editor, deleted the "widgets{...}" component, resaved the file as a .ipynb, and uploaded it to my Google Drive, opened the file in Colab from my Drive, and saved a new copy to my HW11 GitHub folder. This allowed me to recover the embedded link that can take the viewer directly to Google Colab.
---

## Peer Review of Classmate Plots from HW9:

## Ally Baldelli:

![alt text](https://github.com/jarrodsb/DSPS_JBieber/blob/main/HW11/Ally_Baldelli_Plots/old_plot.png "Ally Original Plot")
![alt text](https://github.com/jarrodsb/DSPS_JBieber/blob/main/HW11/Ally_Baldelli_Plots/new_plot.png "Ally Updated Plot")
This updated plot from Ally reduces the ambiguity by changing scatter plot points to dashed lines that are more compact and overlap less. The individual curves are now easier to distinguish, rather than appearing jumbled on top of each other. The updates to the x and y-axis labels also helps lessen the ambiguity, although I think the plot could further benefit by also adding a title. The decision to make the curves follow the 'viridis' color map to convey a sense of numerical progression is a nice touch tht improves clarity and reduces ambiguity. I find that the jumbled look of the original plot with the random shapes was a little bit of a distraction, and the new plot alleviates this issue with the clean and compact dashed lines. The logarithmic scale on the x axis arguably distorts the graph, but I think that this is necessary to be able to properly see the influence of the smaller time gaps. Apart from this, there is not really any distortion to speak of in either the original or updated plots.

The new plot generally respects Tufte's 5 rules, with the possible exception of a "lie factor" from the log scale, but as mentioned, I think this can be forgiven. The data to ink ratio is about right, and the plot depicts a managable (less than 7) number of distinct curves. The original plot's usage of various colored shapes could arguably be considered chart junk, which has been eliminated in the updated version. The one drawback to this change is that the plot is likely no longer color-blind compliant. It may be difficult for a color-blind person to distinguish between the yellow and green dashed lines, for instance. Small multiples of time units (nanoseconds) are being leveraged, and the information to data dimension ratio seems about right.

![alt text](https://github.com/jarrodsb/DSPS_JBieber/blob/main/HW9/Good_Plot.png "Ally_Bad Plot")
I agree that this "bad" plot is overcrowded with information and creates a distraction. It is indeed ambiguous what is the primary information that the plot is trying to get across, and some information is covered up and nearly impossible to read. The color bar that seems to convey both flux and temperature is also ambiguous. I also agree that the inconsistent change in scale along both axis, as well as the depiction of "M/R=3" and "M/R^1.5=5" as straight dashed lines seems like an intentional distortion.

With respect to Tufte's 5 rules, the data vs ink ratio seems very much skewed towards ink. There are way more than 7 pieces of information depicted here. There are also definitely elements to the plot that can be considered chart junk, such as various unmarked dash lines and the labelled arrows, plus the inexplicable histogram along the right edge. With the smooth rainbow color gradient, I imagine that a color blind person would have an even harder time reading this plot than I do.

## Will Taranto:
![alt text](https://github.com/jarrodsb/DSPS_JBieber/blob/main/HW9/Good_Plot.png "Will Original Plot")
![alt text](https://github.com/jarrodsb/DSPS_JBieber/blob/main/HW9/Good_Plot.png "Will Updated Plot")
Will's splitting of his histogram plots into three vertically stacked sections is a good move, that definitely improves clarity and readability. Explcitly stating the mean values for each histogram alleviates a source of ambiguity. Having all three subplots share an x-axis does prevent distortions from occurring. Avoiding the multiple shades of the same color, as they occur in the original plot, eliminates a source of distraction.

The updated plot follows Tufte's 5 rules, for the most part. There is an effect size of 1, small multiples used, and there is virtually no chart junk. The plot depicts a managable (less than 7) number of distinct histograms. I do think that the data vs ink ratio is slightly off, however. There need only be one "Particle Number" label for the y-axis, as the y-axis for all three sections are capturing the same quantity. Likewise, the three uses of the phrase "scale" could probably be condensed into a single usage, with the utilization of a legend for defining the colors. One other minor issue is that the updated plot is not really color-blind compliant.

![alt text](https://github.com/jarrodsb/DSPS_JBieber/blob/main/HW9/Good_Plot.png "Will Bad Plot")
The "bad" plot has densely overlayed lines, making it difficult to see distinct colored shapes (circle, and left/right arrows). This creates ambiguity. The fact that two different quantities are apparently plotted on the same y-axis is another ambiguity. (It is ambiguous to me that the black lines represent electron number density.) The difference in the spacings of the log scales for the y-axis on either side feels like a distortion. The awkwardly formatted label on the left y-axis is a distraction.

With regard to Tufte's 5 rules, there is an effect size of 1, which may be the only redeeming quality for this plot. The data vs ink ratio is off, as the y-axis labels could probably be condensed. We are also clearly dealing with more than 7 different curves. There is chart junk in the form of random rightward pointing arrows. The plot is not using small multiples, choosing to use cubic centimeters rather than some other measure of volume that would result in smaller values along the right side y-axis. The inclusion of "N" and "O" in the bottom left of the plot is an unnecessary redundancy of information. (Unless it is meant as a way to distinguish from the black lines so as to be color-blind compliant, but the plot contains far too much abmiguity to be helpful to a color-blind person, despite the otherwise helpful distinctly shaped lines.)
