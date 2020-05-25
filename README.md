
### Comment on Pan A, Liu L, Wang C, et al. Association of Public Health Interventions With the Epidemiology of the COVID-19 Outbreak in Wuhan, China. JAMA. Published online April 10, 2020. <doi:10.1001/jama.2020.6130>

#### Marc Lipsitch <sup>1, 2</sup>, Keya D. Joshi <sup>1</sup>, Sarah E. Cobey <sup>3</sup>

<sup>1</sup> Center for Communicable Disease Dynamics, Department of Epidemiology, Harvard T.H. Chan School of Public Health, Boston, MA <sup>2</sup> Department of Immunology and Infectious Diseases, Harvard T.H. Chan School of Public Health, Boston, MA <sup>3</sup> Department of Ecology and Evolution, University of Chicago, Chicago, IL

In a recent paper in JAMA, Pan et al. analyze Covid-19 transmission in Wuhan, China during progressive imposition of control measures <sup>1</sup>. They find that the daily reproduction number R(t) remained above 1 throughout the first 3 periods of control (through Feb. 2) and fell below 1 only during the fourth period (on Feb. 6), during which involuntary centralized quarantine and isolation were imposed. They argue that control measures short of involuntary quarantine were inadequate: “However, despite these interventions, the confirmed case rate continued to increase in the third period.” This finding is questionable on its face (confirmed cases trended smoothly downward from onset date January 26 onward apart from an unexplained spike on Feb. 1, eFig. 1 of <sup>1</sup>) and is questioned by the accompanying editorial: “it is difficult to assert that additional interventions in periods 4 and 5 were necessary in driving Rt below 1.0” <sup>2</sup>. Nonetheless, leading voices have cited the findings as strong support for a policy even in the United States of involuntary family separation to enforce such quarantine and isolation <sup>3/<sup>.

The inference that infection rates continued to grow in period three (R(t)&gt;1) and shrink only in period four (R(t)&lt;1) depends strongly on Pan et al.’s use of an estimator for R(t) that was not designed for this purpose. The approach of Cori et al. <sup>4</sup> is by design backward-looking: it uses only data from up to the date on which the estimate is centered to calculate a reproduction number. Thus the estimates of R(t) during the third period are completely determined by the past trend, and if (as an extreme example), case numbers had abruptly dropped to zero on February 2, indicating that control measures prior to February 2 were completely effective, the estimates of R(t) up to February 2 would have been unaffected. An alternative approach, sometimes referred to as the “case reproduction number,” estimates instantaneous reproduction numbers for each day <sup>5</sup> based on past, present, and future cases.

We requested the raw counts from eFigure 1 from a corresponding author (X Lin) but were told they were not available. We therefore digitized the figure using WebPlotDigitizer version 4.2 (<https://automeris.io/WebPlotDigitizer>), replicated the paper’s analysis using the method of Cori et al. <sup>4</sup>, and compared the results against those from the alternative method of <sup>5</sup>. Using the Cori method as Pan et al. did, our curve closely follows Fig. 4 of 1 when using the same method. As anticipated, the alternative approach, taking into account the evident decline of the epidemic curve that began during Period 3, finds that Rt dropped below 1 during Period 3, specifically on 28-29 Jan. (Fig. 1)

There is no ideal method for estimating Rt during a period when it is changing on a time scale equal to or faster than the serial interval of the infection. In this particular case, a few days’ difference in the timing of when Rt dropped below 1 leads to divergent policy interpretations. We believe that a purely backward-looking method like that used by the authors inevitably finds too late a date in such a situation because it cannot account for drops in future case numbers, while the method of <sup>5</sup> may be influenced to some degree by future changes in transmission. We are currently studying the performance of these different approaches to detect timing of Rt&lt;1. Meanwhile, caution in interpretation is warranted. In particular it is not clear, as Hartley and Perencevich note <sup>2</sup>, that the extreme and invasive measures begun after February 2 were necessary to control transmission in Wuhan, or how this would generalize to other settings.

### Update:

In the original analysis, Pan et al. did not lag Cori et al by the mean incubation period. We have updated the figure to include a shifted version of the R(t) of Cori/Pan et al., lagged by the mean incubation period since the Cori method is designed for time of infection and this curve is symptom onset.

![](figures/fig1_panfig4_recreate_2.png)Figure 1 (A) Digitized data from eFigure 1 of <sup>1</sup>. (B) Recreation of Fig. 1 R(t) analysis of 1 from the digitized data using the same method (looking backward in time) as the authors <sup>4</sup> , comparison with an analysis using the (forward-looking) method of <sup>5</sup>, and shifted estimate of <sup>4</sup>, by the mean incubation period since the Cori method is designed for time of infections and this curve is symptom onset. Vertical dashed lines show the first day in which each method estimated R(t) &lt;1.

### REFERENCES

1.  Pan A, Liu L, Wang C, et al. Association of Public Health Interventions With the Epidemiology of the COVID-19 Outbreak in Wuhan, China. JAMA. April 2020. <doi:10.1001/jama.2020.6130>

2.  Hartley DM, Perencevich EN. Public Health Interventions for COVID-19: Emerging Evidence and Implications for an Evolving Public Health Crisis. JAMA. April 2020. <doi:10.1001/jama.2020.5910>

3.  Fineberg, H V, Kim JY , Shlain J. The United States Needs a “Smart Quarantine” to Stop the Virus Spread Within Families. New York Times <https://www.nytimes.com/2020/04/07/opinion/coronavirus-smart-quarantine.html>. April 7, 2020.

4.  Cori A, Ferguson NM, Fraser C, Cauchemez S. A new framework and software to estimate time-varying reproduction numbers during epidemics. Am J Epidemiol. 2013;178(9):1505-1512.

5.  Wallinga J, Teunis P. Different epidemic curves for severe acute respiratory syndrome reveal similar impacts of control measures. Am J Epidemiol. 2004;160(6):509-516.
