---
title: "Period analysis in BioDare2"
teaching: 10
exercises: 50
questions:
- "What is BioDare2"
- "What are the benefits of a repository dedicated to circadian data"
- ""
objectives:
- "Create experiment and import timeseries data"
- "Visualise the data"
- "Perform period analysis and rhythmicity test"
keypoints:
- ""
- ""
- ""
---

## [BioDare2](https://biodare2.ed.ac.uk/) 
is a repository for circadian, biological data, providing a platform for data sharing and period analysis. The main features of BioDare2 are: fast period analysis, timeseries processing, attractive visualizations, simple data description and modern UI, all of it to assure the best user experience.

## Timeseries data

Circadian research is all about timeseries. BioDare can visualize your data and allows you to perform various timeseries processing:
- four detrending methods
- normalization
- alignment

## Rhythm analysis

Period analysis is the strongest point of BioDare. BioDare gives you access to the:
-    best analysis methods
-    attractive visualizations
-    result aggregation

Available methods:
-    FFT NLLS
-    MESA
-    MFourFit
-    Enright Periodogram
-    Lomb-Scargle periodogram
-   Spectrum resampling

## Using BioDare2

The philosophy behind BioDare as a community resource is that users utilize BioDare to visualize and analyze their data in a fast and easy way. By having the data already deposited in the repository, they can easily make it public for data sharing. Moreover, datasets that are over 3 years old can automatically become public.


> ## Using BioDare2
>
>  ##  Creating an experiment:
> * Navigate to the top menu and select "New Experiment."
> * Enter a descriptive name, e.g., "BioDare demo WT vs PRR79 at long day."
> * Specify the purpose, e.g., Testing periodic properties of the new LUC constructs in PRR79 after long day entrainment (18:6 LD).
> * Provide a description, e.g.,  
> *Seedlings were grown under 24 light/dark cycles (18h of light and 6h of darkness), corresponding to physiological summer day lengths for 7 days. The entrained seedlings were then moved into constant light conditions, and their luminescence was monitored with a high-sensitivity camera. WildType and prr79 mutant were transformed with different LUC constructs driven by a clock gene promoter: LHY, TOC1, ZTL, PRR5, PRR7. Also, include any additional comments, such as fungus contamination on the prr79 TOC1 line.*
> * Press "Accept."
>
> * In the "Biological details" section below, enter the species and data category (Expression reporter).
>
>  * In the "Measurements details" section, provide technical information: Seedlings were sprayed with luciferin on the last day of entrainment. Exposition time was 10 minutes with a 2-hour interval between pictures. Recorded pictures were analyzed using Metamorph, utilizing the standard region grid instead of manual region selection.
>
>  ##  Importing data:
>  * Obtain the data file from: https://biordm.github.io/fair-in-circadian-practice/files/biodare-demo-wt_prr.xlsx
>  * Go to "Import data" in the dashboard menu.
>  * Select the data file (demo-wt-prr.xlsx) and leave the default file format as Excel.
>  * Describe the data layout (data in columns, data labels present, no background noise records).
>  * Define the time column: Click on the first cell containing the first time point (A5). Change the unit to "image nr" and set the time interval to 2 hours.
>  * Import labels from the correct row (4th).
>  * Click on the first data column (there may be other columns between the time column and the measurements).
>  * Press "Import data."
>
>  * Explore the plotting options (Show data and Heatmap).
>
>  ## Period analysis:
>  * Navigate to "Period analysis."
>  * Define analysis parameters (data subset, detrending, analysis method, and range of periods of interest).
>  * Press "Analyze."
>  * The screen switches to display the results of period analysis, showing box plots for period values by biological replicates.
>  * If "X results need attention" is displayed, press "Select Periods" to view the results not included in the statistics and why.
>  * The phase plot offers different view settings: Phases by FIT (fitting a cosine with the main period and using its peak time), by Method (as defined in the original method), FIRST (by the time of the first peak), and Avg. (by the average times of all peaks). Parameters are described under "?" in the panel above.
>
> *  Use the download icon on top to export all the results.
>
> ##   Rhythmicity test:
> BioDare implements classic JTK and eJTK methods for rhythmicity testing of omics-like data (short, infrequently sampled measurements).
>        To simulate such data, analyze only the last two days of data.
>  * In the data window, type 120 in "from" and leave "to" as 0 (which is the end).
>  * Leave the rest of the presets and run the test.
>  * examine the results
> 
>
{: .challenge}




{% include links.md %}
