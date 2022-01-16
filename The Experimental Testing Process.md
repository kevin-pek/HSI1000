# Experimental Testing
###### Found in
[[HSI1000]], [[The Scientific Method]]
## Experimental Process
![[Screenshot 2021-09-02 at 10.31.27 PM.png]]
**False Confirmation** - Wrongly accepting a hypothesis
**False Rejection** - Wrongly rejecting a hypothesis
## Contemporary Scientific Process
The contemporary scientific process builds on top of testing explanations, by including areas such as literature search on existing scientific research, and also includes reporting conclusions and acquiring funding for experiments.
Scientific Research follows a typical process of:
 1. *Observation* - Find something that we want to find out more about
 2. *Research* - Reading up on the existing scientific literature and explanations
 3.  *Hypothesis* - A speculative statement that is falsifiable/testable
4. *Test with experiment* - Not as simple as testing the explanation based on hypothesis. May need to figure out something that should happen/shouldn't happen, if the explanation is true.
5. *Analyse Data*
6. *Report Conclusions*
## Terminology
### Accuracy
#### Common Definition (Trueness)
The closeness of the measured values to their true value. 
>Accurate instruments require a **low systematic error**, but can have a **large random error (high uncertainty)**.
#### ISO (Internation Organisation of Standards) Definition
Mix of both **Trueness** (Common Definition) and **Precision**. 
>By this definition, accurate instruments require both **low random error** and **low systematic error**
### Trueness
How close a measurement is to the true value using the average of the measurements. Reflects systematic error eg. zero-error.
### Precision
How close measurements made are to each other. High precision measurements have a small grouping. It makes it easier to figure out what value another measurement would be with high precision. Reflects random error.
### Uncertainty
A value indicated after the reading. A small uncertainty means that a reading has high precision.
## Determining if something is Statistically Significant
#### 3 Rules of Thumb:
1. Whether there is an **overlap in the CIs**. If no overlap, difference is statistically significant at 95% confidence level. 
2. The greater the overlap between the 2 CIs, the less confident we are that the difference is real.
3. If **overlap is more than 1/3 of the range covered by the 2 CIs**, difference is not statistically significant.
### Margin of error
Provides a range of possible values for the result of our experiment, instead of just one value
### Confidence of error
The confidence that the experiment done contains the true value in the range given by the margin of error.
### Statistically Significant
If something is statiscally significant, it means something done in the experimental group caused a change in observed phenomena.
### Effect Size
The effect observed when there is a statistically significant difference may not be practically different. ie. when the measured value is very small
<hr>

#### Example calculations for Statistical Significance
##### Example 1 (from Block Test 1)
>53 pregnant women claimed they had strong intuition regarding the gender of their baby. Of these 53 women, 33 predicted their baby’s gender correctly. The margin of error for this experiment is ±13% at the 95% confidence level. Can we conclude with 95% confidence that these women indeed possess intuition about the gender of their baby and why?

$\frac{33}{52}=62\%$ correctly predicted the gender. Therefore $62\%\pm 13\%$ of mothers correctly predict their baby's gender.
We assume that if mothers can predict the baby's gender more than 50% of the time, and that 50% is not within in the confidence interval, as we have to factor in luck. 
Since $62\%-13\%=49\%$, 50% lies within the confidence interval, and we cannot be 95% confident that the mothers possess intuition about the gender of their child.
##### Example 2 (from Block Test 1)
>The experimental group were given water with the “special” tasteless additive. There was 50 people in each group. 20 in the control group said they felt much happier, whereas 26 in the experimental group said they felt much happier. Does this experiment demonstrate, at the 95% confidence level, that the “special” tasteless additive makes people feel happier?

Margin of error for a sample size of 50 is $\pm 14\%$.
Control Group has $\frac{20}{50}=40\%$ success.
Experimental Group has $\frac{26}{50}=52\%$ success.
This means the Confidence Interval for the control group is $26\%- 54\%$, and $38\%-66\%$ for the experimental group.
We can immediately see there is significant overlap between the CIs, which is $\frac{54\%-38\%}{40\%}=40\%$ overlap to be exact. This is more than $\frac{1}{3}$ overlap of the CIs, which means the difference is not statistically significant. 
<hr>

## Experimental and Control Groups
Experimental and control groups are used to establish a causal link by comparing if there is a difference between observed phenomena given only a change in relevant conditions. 
>Randomised controlled trials are used to remove any possible bias in the results from fallacies like the placebo effect.
### Randomised Controlled Double-Blind
In such experiments, subjects are:
- Don't know if they are in the experimental or control group
- Are randomly picked to go into either the control or experimental group
>Note that "Randomised" in this context **refers to the subjects being randomly assigned to either the experimental or control group**. The subjects being randomly picked is a given.
- Those working with subjects are also unaware of which group the subjects belong to.