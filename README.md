Download Link: https://assignmentchef.com/product/solved-stat-292-assignment-5
<br>
<ol>

 <li>Table 1 presents a subset of data collected by V¨aisa¨nen and Ja¨rvinen (1977) on birdspecies in the Krunnit Islands archipelago of Finland. In particular, they reported on the bird species found on each of the islands in 1949 and how many of those bird species were extinct by 1970. It is of interest to understand whether the area of the island (in km<sup>2</sup>) is associated with species’ survival. The data corresponding to Table 1 are available in the Excel file xlsx.</li>

</ol>

<table width="276">

 <tbody>

  <tr>

   <td width="129"> </td>

   <td width="80"> </td>

   <td colspan="2" width="67">Extinct?</td>

  </tr>

  <tr>

   <td width="129">Island</td>

   <td width="80">Area (<em>X</em>)</td>

   <td width="39">Yes</td>

   <td width="27">No</td>

  </tr>

  <tr>

   <td width="129">Ulkokrunni</td>

   <td width="80">185.80</td>

   <td width="39">5</td>

   <td width="27">70</td>

  </tr>

  <tr>

   <td width="129">Maakrunni</td>

   <td width="80">105.80</td>

   <td width="39">3</td>

   <td width="27">64</td>

  </tr>

  <tr>

   <td width="129">Ristikari</td>

   <td width="80">30.70</td>

   <td width="39">10</td>

   <td width="27">56</td>

  </tr>

  <tr>

   <td width="129">Isonkivenletto</td>

   <td width="80">8.50</td>

   <td width="39">6</td>

   <td width="27">45</td>

  </tr>

  <tr>

   <td width="129">Hietakraasukka</td>

   <td width="80">4.80</td>

   <td width="39">3</td>

   <td width="27">25</td>

  </tr>

  <tr>

   <td width="129">Kraasukka</td>

   <td width="80">4.50</td>

   <td width="39">4</td>

   <td width="27">16</td>

  </tr>

  <tr>

   <td width="129">La¨nsiletto</td>

   <td width="80">4.30</td>

   <td width="39">8</td>

   <td width="27">35</td>

  </tr>

 </tbody>

</table>

Table 1: Extinction of bird species from 1949 to 1970 on seven islands in the Krunnit Islands archipelago, Finland. Fit the logistic regression model

where <em>X </em>denotes island area and <em>p</em>(<em>X</em>) denotes the probability of extinction.

Figure 1 shows relevant SAS output for the logistic regression model.

<ul>

 <li>Carry out an appropriate goodness-of-fit test to determine whether the modelprovides a good fit to the data. State the hypotheses, and give the test statistic and the <em>p</em>-value of the test. What do you conclude at the <em>α </em>= 0<em>.</em>05 significance level?</li>

 <li>Give estimates of <em>β</em><sub>0 </sub>and <em>β</em><sub>1 </sub>(up to 5dp).</li>

 <li>Interpret the association between island area and extinction using the odds ratio. Demonstrate how the odds ratio is calculated from Figure 1. Additionally, provide a 95% confidence interval for the odds ratio.</li>

</ul>

Figure 1: Summary output for the logistic regression model log. (d) Find the predicted probability of extinction for an island with an area of 50 km<sup>2 </sup>(to 4dp).

<ul>

 <li>Find the fitted count of extinct bird species on the island of <u>Ulkokrunni </u>(to 2dp). Also find the fitted count of non-extinct bird species on <u>Ulkokrunni </u>(to 2dp).</li>

 <li>Test</li>

</ul>

H<sub>0 </sub>: <em>β</em><sub>1 </sub>= 0

H<sub>1 </sub>: <em>β</em><sub>1 </sub>6= 0

using the Wald statistic. Give the test statistic and the <em>p</em>-value of the test. What do you conclude at the <em>α </em>= 0<em>.</em>05 significance level?

<ol start="2">

 <li>Consider data reported by Gilbert (1981) on the relationship between pre-maritalsex (<em>e.</em>, sexual intercourse before marriage), extra-marital sex (<em>i.e.</em>, sexual intercourse with someone other than a spouse whilst married), and whether the person had been divorced for a random sample of heterosexual men and women who had been married at least once. These data are presented in Table 2 and are available in the Excel file Divorce.xlsx.</li>

</ol>

Gender    Pre-marital    Extra-marital     Divorced? (<em>Z</em>)

(<em>W</em>)           Sex (<em>X</em>)             Sex (<em>Y </em>)          No         Yes

Table 2: Data on reported pre-marital sex, extra-marital sex, and divorce for a random sample of heterosexual men and women.

First, use the backward model selection method to find the simplest model that provides a good fit to the data. Start from the following model, which we will denote by <em>M</em><sub>2</sub>,

<em>,</em>

where <em>p<sub>ijk </sub></em>is the probability of divorce when the gender (<em>W</em>) is at level <em>i</em>, pre-marital sex status (<em>X</em>) is at level <em>j</em>, and extra-marital sex status (<em>Y </em>) is at level <em>k</em>.

Figure 2 shows relevant summary output from SAS.

<ul>

 <li>Is model <em>M</em><sub>2 </sub>a saturated model? Why or why not?</li>

 <li>What information does <strong>Step 1 </strong>provide in the SAS output? Write down the test hypotheses. What do you conclude?</li>

</ul>

Figure 2: Summary output for the backward selection method applied to the logit model

.

<ul>

 <li>What is the final model?</li>

</ul>

Now consider the logit model, which we will denote by <em>M</em><sub>1</sub>,

<em>.</em>

which uses a reference level parametrisation for all factors.

Figure 3 shows relevant summary output from SAS.

<ul>

 <li>Carry out an appropriate goodness-of-fit test to determine whether model <em>M</em><sub>1 </sub>provides a good fit to the data. State the hypotheses, and give the test statistic and the <em>p</em>-value of the test. What do you conclude at the <em>α </em>= 0<em>.</em>05 significance level?</li>

 <li>Compare the odds of divorce for men with the odds of divorce for women usingan odds ratio, and interpret this odds ratio. Give a 95% confidence interval for the odds ratio.</li>

</ul>

Figure 3: Summary output for the logit model log.