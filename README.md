## Realtime_R0
### Dynamic Effective Reproduction number for COVID-19
<br>
As a pandemic evolves, increasing restrictions (or potential releasing of restrictions) change $R_t$. Knowing the current $R_t$ is essential. When $R&gt;1$, the pandemic will spread through the entire population. If $R_t&lt;1$, the pandemic will grow to some fixed number less than the population. The lower $R_t$, the more manageable the situation. The value of $R_t$ helps us (1) understand how effective our measures have been controlling an outbreak and (2) gives us vital information about whether we should increase or reduce restrictions based on our competing goals of economic prosperity and human safety. [Well-respected epidemiologists](https://www.nytimes.com/2020/04/06/opinion/coronavirus-end-social-distancing.html) argue that tracking $R_t$ is the only way to manage through this crisis.

Based on the implementation of [Bettencourt & Ribeiro 2008](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0002185) by [Kevin Systrom](http://systrom.com/blog/the-metric-we-need-to-manage-covid-19/) and applied to data retrieved from https://bit.ly/patientdb.
<br>

#### Rt Graphs
(Using 10 day smoothing in gaussian filter)<br>
![alt text](https://github.com/ahsanabbas123/Realtime_R0/blob/master/Images/India_10.png "India")
![alt text](https://github.com/ahsanabbas123/Realtime_R0/blob/master/Images/MH_10.png "Maharashtra")
![alt text](https://github.com/ahsanabbas123/Realtime_R0/blob/master/Images/RJ_10.png "Rajasthan")
(Using 7 day smoothing in gaussian filter for Delhi)<br>
![alt text](https://github.com/ahsanabbas123/Realtime_R0/blob/master/Images/DL.png "Delhi")


