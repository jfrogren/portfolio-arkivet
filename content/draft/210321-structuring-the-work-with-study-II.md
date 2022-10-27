---
title: "Structuring the Work with Study II"
date: 2021-03-21T13:44:48+01:00
draft: false
categories: ["Research process", "Publication"]
---

In order to try to structure the remaining work with my Study II - which at the moment feels a bit overwhelming to be honest considering that I during the last weeks have been focusing so hard on the ethical application for Study III - I decided to try to create an action list of the tasks that needs to be done.

## Submission guidelines

I have also had a look at the [submission guidelines for PLOS One](https://archive.ph/Eo8uf), which is the journal that we have discussed that we will try to publish in.

## Action list for manuscript editing
Anyway, here is the action list of what needs to be done related to the manuscript for Study II:

1. **Include nationality as an independent variable** :white_check_mark: <br> Since it according to RL is an aspect mentioned in the literature as being related to willingness to be involved in research. 

2. **Clearer description of how regression follow on uni- & bivariate analyses** :white_check_mark: <br> Not sufficiently clear for the reader how and why I went from one analysis to the next.

3. **Dig more into the health status variable** :white_check_mark: 

  + There seems to be a negative correlation between self-rated health and willingness, but what does that mean? Explain.
  + The current manuscript suggests that the result indicates a conflict with previous research, but in that case this is something that needs to be developed further. 
  + Add and analyze frailty as well. <br> Bring in frailty as an additional variable here, motivating this decision by stating that they were both initially considered relevant to include. To check how to frame frailty in this context, SI recommended me to - rather than contact Synneve, as MK had suggested - go to her papers and see for myself how frailty is been defined, brought up and framed there.
  
  *After doing a bit of searching and reading about frailty, I found out in the following [article](/pdfs/berglund2019.pdf#page=3) on p. 1099 that there seems to be an instrument for measuring frailty consisting of seven indicators, where some indicators seems to be based on som sort of clinicians judgement while other indicators are self-reported. Why a frailty index was included in the panel study is not so clearly explained in [the study protocol](/pdfs/kylen2020.pdf#page=4). However, I get the feeling that the self-reported indicators were included and since it was not possible to include something else, the other indicators were simply excluded. In the article here by Berglund et al. (2019), the authors write: "We deemed the older people to be frail if they fulfilled three or more frailty indicators". I decided to follow the following logic.*
  
  + There might be a correlation between frailty and self-rated health and then I will just move a long with the one with strongest correlation.

4. **Municipality of residence - no significance, no mentioning.** :white_check_mark: <br>
I pointed out that the results indicated 10% higher awareness of the possibility to be actively involved in research among people living in large cities compared to people living in rural municipalities, even though the p-value was not sufficiently low to indicate any significant difference. However, SI asked me not to speak of any correlation in the results if it was not significant.

5. **Edit Table 6.** :white_check_mark:

  + Use OR instead of p-value in the willingness table. Thus, make a series of bivariate (univariable) logistic regressions instead of Chi square tests.
  + For the descriptive bivariate analyses of *Awareness* and *Previous active involvement*, use Mann-Whitney or Wilcoxsons non-parametric tests for ordinal and nominal scale with more answer options than two (or three?). For *age* and *sex*, use Chi square.
  + Decide for a cut-of value of .1 or .2. (Usually at .1 or .2, but here I was asked to, based on previous similar studies, suggest which p-value I considered appropriate to take the variable further to that analysis. However, this p-value should not be presented in any table, but the only table reported for willingness is the one based on the next multivariable logistic regression, and OR should be included instead of the p-value.)
  + For multivariate analysis I should choose the group that is big enough as = 0, because the confidence interval in the subsequent groups will follow from that. SU explained that one can in principle choose any of the categories, but one should also be able to argue theoretically why a certain category was chosen. 
  + Conduct the analysis so that anything with a p-value higher than the one chosen will not be included. (However, you can still include variables that can be strongly motivated theoretically and the standard procedure is to include sex even if it is not significant simply because that is the standard procedure.)
  + Do a “correlation matrix” to see the correlation betwen the independent variables. <br> (When it comes to checking the interdependence between the independent variables, SU recommended VIF as a suitable alternative to the conventional correlation matrix. The VIF value should be above .70 or .80 in order to be a problem correlation-wise.)

*I found some information about VIF [here](https://archive.fo/8bIim). It seems that the .70 or .80 thresholds are questionable.*  

6. **Edit Table 7.** :white_check_mark: <br> Enter all independent variables except previous active involvement in block 1 and 'Previous active involvement' as block 2 rather than the other way around. However, when I describe what I have done, I should not employ the term ‘block,’ but rather write: “In the first model we used age , sex etc as the independent level.. then there was a second model were we included previous active involvmenet as a confounder.”

7. **Edit Table 2 and 3.** :x: <br> An alternative to the current presentation of data in Tables 2 and 3 would instead be to present, for example, level of education in a way that describes that “Among those who are willing, how many have elementary school as their highest education level, high school,etc.?” The way in which it is best to present the result in this case is connected with how I intend to conduct the discussion and which result then best illustrates the arguments I wish to present.

*As for now, I decided to wait with this and keep it as it it.*

8. **Edit Table 4.** :white_check_mark: <br> Table 4 was considered redundant and I was asked to remove it. 

9. **Replace Table 5 with figure.** :white_check_mark: <br> Figure 1 was considered good as it was, but I was asked to create a similar figure for the contents of Table 5 and thus replace that table with a figure.

*Unfortunately, I only found an image of figure 1, and not the original data set upon which it was based. I decided to create [the following table](https://lu.app.box.com/file/790579468430) in Excel, did print screen (Cmd-Shift-4) and created the following [image](https://lu.app.box.com/file/790578709278). Not perfect, but it will have to do for now.*

10. **Transform Level of education variable** :white_check_mark: <br>  When it came to Level of education, SU thought that the number of respondents who had ‘Research education’ was so small that that group could advantageously be incorporated into the category ‘College 3 years or more.

11. **Make sure response options are correct for Self-rated health & Self-rated economy.** :white_check_mark: <br> Regarding self-rated health, SI and SS pointed out that it was unclear whether the current response options really corresponded to the actual instrument. Here I was asked to ensure that this was the case and to use these response options and no others. These options were also used for self-rated economy, so even there I needed to ensure they were correctly formulated.

*I found the answer in the following [article](/pdfs/ware-jr1992.pdf#page=2), referred to in [this article](/pdfs/tomsone2013.pdf#page=3) namely: Poor; Fair; Good; Very good; Excellent*. 

12. **Transform Self-rated health and Self-rated economy variable** :white_check_mark: <br> Transform the five categories related to self-rated health and self-rated economy into three. this would also make the table for the next multivariate logistic regression less extensive and easier to interpret. Thus, keeping the middle category intact but merge the first and second, as well as the fourth and fifth was decided as a good way forward. SU also emphasized that I need to have the same groups for univariable and multivariable analysis. However, for the analysis of awareness and previous active involvement, which will be kept on a descriptive level, I can keep the five categories.
