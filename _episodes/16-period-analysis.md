---
title: "Methods of period analysis"
teaching: 60
exercises: 0
questions:
- ""
- ""
- ""
objectives:
- ""
- ""
- ""
keypoints:
- ""
- ""
- ""
---

Period analysis and rhythmicity tests are techniques used in the analysis of circadian time
series data, which are measurements taken over time that reflect the cyclical nature of 
biological processes occurring roughly every 24 hours.

**Period Analysis**: This involves identifying the dominant periodic components within a time 
series dataset. It aims to determine the length of the repeating cycle (period) and the 
amplitude of the oscillations. 

**Rhythmicity Tests**: Rhythmicity tests assess whether a time series dataset exhibits 
statistically significant rhythmic patterns. These tests evaluate whether the observed 
fluctuations in the data are likely to occur due to chance or if they represent true circadian 
rhythms. Various statistical tests can be used for this purpose, these tests assess the 
presence of rhythmicity by comparing the observed data to the expected pattern under the null 
hypothesis of no rhythmicity.


Both period analysis and rhythmicity tests are essential tools in chronobiology for 
understanding the circadian rhythms of biological systems, including sleep-wake cycles, 
hormone secretion, and gene expression patterns. They provide insights into the underlying 
temporal dynamics of these processes and help researchers characterize their rhythmic 
properties. 

## Period

The function `F(x)` exhibits periodic behavior with a period `T` if, for any value of `x`, the value of the function repeats itself after adding `T` to `x`. In other words, the function repeats its values every `T` units along the xx-axis.

~~~
F(x) = F(x) + T
~~~

![Figure 1. Periodic function](../fig/16-period_1.png)

Real biological data are rarely perfectly represented by mathematical curves. Time series data, which are measurements taken over time to depict cyclical biological processes such as circadian rhythms, often contain noise, damping effects, or underlying trends (Figure 2). 

![Figure 1. The real biological data typically contains noise as well as trends](../fig/16-period_2.png)

In the context of time series data and circadian rhythms, a period refers 
to the length of time it takes for a repeating pattern or cycle to occur. Specifically, it 
represents the duration of one complete oscillation or cycle in a cyclical phenomenon. For 
circadian rhythms, which have a roughly 24-hour period, the period refers to the time it takes 
for the rhythm to complete one full cycle, typically from one peak (or trough) to the next 
peak (or trough).



## I am a section

With a text.

![Figure 1. I am some figure](../fig/figure_file.jpg)

*After [Figure source](https://www.figure.link/)*


> ## I am a yellow info
>
> And my text.
{: .callout}


~~~
I am code
~~~
{: .source}


> ## I am a problem
>
> Defined here.
>
>> ## Solution
>>
>> *   I am an answer.
>> *   So am I.
> {: .solution}
{: .challenge}


> ## Attribution
> Content of this episode was adopted after XXX et al.
> [YYY](https://biodare2.ed.ac.uk).
{: .callout}


{% include links.md %}
