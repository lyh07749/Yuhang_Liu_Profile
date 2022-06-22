### Thesis Topic: Estimating the Effectiveness of Non-Pharmaceutical Interventions (NPIs) During COVID-19

Worldwide, governments imposed a wide range of non-pharmaceutical interventions (NPIs) in the wake of the COVID-19 pandemic. Three years later today, pandemic fatigue has set in among the world’s population as the virus attack continues in waves. To help governments contain the pandemic more effectively and to ease the burden on the population, we examined the effectiveness of individual NPI among the 42 states in the US where death count exceeded 100 during the first wave of the COVID-19 pandemic (February 1 to June 15, 2020). Two types of analyses were performed. Firstly, a prototypical Bayesian hierarchical model is employed to estimate the effectiveness of 5 commonly imposed NPIs in the US, including *gathering restriction*, *restaurant capacity restriction*, *business closure*, *school closure*, and *stay-at-home*. Secondly, the effectiveness of *facemask mandate*, the most controversial policy among states, is studied through counterfactual modeling, a variant of the prototypical Bayesian hierarchical model.

![US Map](https://github.com/lyh07749/Yuhang_Liu_Profile/blob/c0f67f1369d68041646307c7da7e9b691d295475/images/NPI/US_States.png)
The colored states are the 42 states whose death count had exceeded 100 by the end of the study period where the grey states were the ones excluded from the analysis due to low death count.The 14 green states implemented facemask mandate policy during the study period where the 28 pink states did not implement facemask mandate policy during the study period.

Result Visulizations (generated using ggplot in R):
* [The effectiveness of 5 commonly imposed NPIs](https://github.com/lyh07749/Yuhang_Liu_Profile/blob/main/images/NPI/NPI_Rt_Reduction.png) (represented by the percentage reduction on Rt)
* [The estimated Rt trajectory for Massachusets](https://github.com/lyh07749/Yuhang_Liu_Profile/blob/main/images/NPI/Massachusetts_Rt.png) (all 42 states are available but only present one for illustration purpose)
* [The estimated (orange) and observed (brown) infections and deaths for Massachusets](https://github.com/lyh07749/Yuhang_Liu_Profile/blob/main/images/NPI/Massachusetts_Infection_Death.png) 
* [Median time-varying reproduction number estimates for states with and without facemask mandate](https://github.com/lyh07749/Yuhang_Liu_Profile/blob/main/images/NPI/Mask_Rt_Estimates.png)
* [Daily infection estimates for states with and without facemask mandate](https://github.com/lyh07749/Yuhang_Liu_Profile/blob/main/images/NPI/Mask_Infection_Estimates.png)
* [Daily death estimates for states with and without facemask mandate](https://github.com/lyh07749/Yuhang_Liu_Profile/blob/main/images/NPI/Mask_Death_Estimates.png)

