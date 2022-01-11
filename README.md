# Evaluating Project Safe Neighborhoods Dallas: Effects on Violent Crime and Trauma Volume



In 2017, the City of Dallas partnered with federal and state law enforcement agencies to reduce recent increases in violent crime, especially firearm violence. The *Project Safe Neighborhoods: Dallas* (PSND) task force identified a target area for intervention based on the area’s high crime rate and vulnerable population. 

The target area largely overlaps with the authors’ institutional service area, with the trauma center located centrally in the target area. This study examined if violent crime in the target area was reduced after PSND launched in April 2018. Additionally, we examined what effect PSND had on the rate of patients presenting to the trauma center for firearm and assaultive injuries.

<br>

<img src="/Map of DPD regions and THD service area.png" alt="Figure showing trauma patient volume" width="80%"/>


<br>
<br>


## Violent crime rates

Violent crime includes robbery, aggravated assault, & murder/non-negligent homicide.  

Data on these index violent crimes were obtained from Dallas Police & from all other municipalities in Dallas County from January 2015 through December 2020.

Nonlinear models controlling for seasonality, temporal dependency, and geospatial dependency were fit to the data.  These models were then used to derive crime rates per 100,000 population.  The model predictions are plotted with 95% simultaneous confidence intervals.  Notably, the first four months of data are not shown on the figures since violent crime rates from the four prior months were used as predictors in the model to account for strong temporal dependency. 


Estimates of the first derivatives were used to find and determine periods of significant changes in violent crime. 

---

<br>
<br>

<img src="/Dallas crime rates vs county FOR POSTER.png" alt="Figure showing violent crime rates" width="50%" align="right"/>

<br>

Violent crime was consistently higher in the target area than the rest of the city of Dallas & the countywide average. 
<br>


From Nov. 2017 to July 2018, violent crime in the target area was significantly higher than in the non-target area of Dallas.

<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>

The significant difference in violent crime rates between the target and non-target regions of Dallas ended due to significant increases in the non-target area between Feb. 2018 and Feb. 2019. However, violent crime never significantly changed in the target area.

Violent crime in the target area of Dallas |  Violent crime in the non-target area of Dallas
:-------------------------:|:-------------------------:
<img src="/model-internal-change-res-PSND-3.png" alt="" width="100%"/>  |  <img src="/model-internal-change-res-non-target-3.png" alt="" width="100%"/>

<sub><sup>First derivatives >0 indicate violent crime is increasing. First derivatives <0 indicate violent crime is decreasing. When the 95% CI for the first derivatives does not contain 0, that indicates a period of significant change; these periods are shown with darker grays and bolded lines. </sup></sub>


<br>
<br>
<br>
<br>
<br>

---


<br>
<br>
<br>

## Crime-related trauma volume

To assess trauma volume, we queried the hospital’s trauma registry for monthly counts of 1) patients presenting with intentional non-self-inflicted gunshot wounds and 2) patients presenting with any intentional/assaultive injuries (e.g., aggravated assault, stab wounds, gunshot wounds).  As the hospital became a level II trauma center in 2016, these data span from January 1, 2016 through December 31, 2020.

These data were then modeled using methods analogous to those used for violent crime. These models were then used to derive injury rates per 100 trauma encounters.  The model predictions are plotted with 95% simultaneous confidence intervals.

Estimates of the first derivatives were used to find and determine periods of significant changes. 

---

<br>
<br>
<br>

<img src="/Patient volume rates for web.png" alt="Figure showing trauma patient volume" width="50%" align="right"/>

<br>
<br>

After long-running decreases, firearm & assaultive injuries began to rise after PSND.  

<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>





Assaultive Injuries |  Firearm Injuries
:-------------------------:|:-------------------------:
Assaultive injuries increased significantly from June 2019 to December 2019.  |  Firearm injuries increased significantly from July 2018 through December 2020.
<img src="/assaults.png" alt="" width="100%"/>  |  <img src="/gsws.png" alt="" width="100%"/>

<sup><sub>First derivatives >0 indicate the injury rate is increasing. First derivatives <0 indicate the injury rate is decreasing. When the 95% CI for the first derivatives does not contain 0, that indicates a period of significant change; these periods are shown with darker grays and bolded lines. </sup></sub>





<br>
<br>
<br>

## Exploratory analyses

<img src="/SPPT analysis of beats for poster.png" alt="Figure showing police beats with significant changes in violent crime" width="70%" align = "right"/>

Additional exploratory analyses using spatial point pattern testing showed violent crime only significantly changed in six Dallas police beats when comparing 12 months pre/post PSND implementation.

Two beats (#216 & #254) in the target area experienced significant decreases in violent crime, but only the decrease in beat #216 remained significant after adjusting for multiple testing.

Both of these decreases were offset by increases in beats #218 and #651. 

The increase in beat #218 (in the target area) was not significant after adjusting for multiple testing.

However, the increase in beat #651 (just outside of the target areas) was significant and larger than both of the decreases in the target area (OR = 7.08; 95% CI = 2.50, 29.67; p < 0.001; p adjusted = 0.014).


<br>
  
Showing beats with significant differences *before* adjusting for multiple testing |  Showing beats with significant differences *after* adjusting for multiple testing
:-------------------------:|:-------------------------:
<img src="/SPPT analysis of beats for poster - more shown.png" alt="" width="100%"/>  |  <img src="/SPPT analysis of beats for poster.png" alt="" width="100%"/>
