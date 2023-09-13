### Can actually by the clinical trials data we can predict the confirmity of cases?

## Alternate Hypothesis - COVID Clinical Markers


### General Overview
#### Task Details
The initiative is prompted by the suggestion that there may be a link between reduced rates of infection and lower case fatality rates associated with COVID-19 in countries that recommend BCG vaccine for all as opposed to countries that recommend BCG only for specific high-risk groups. We hope that the analysis done as part of this task might help discover useful information about the BCG - COVID-19 clinical trials. For example, some insights that may come from this analysis is whether factors such as the strain of BCG, the age at which people have been vaccinated, revaccination, or how long ago people have been vaccinated are important.

### Key Questions for Consideration and what's included in this notebook?
The dependence of BCG Vaccine effects on COVID-19 Treatment is still under research and is hearing a mixed response from the community. This notebook looks over the Alternate Hypothesis for the BCG COVID-19 AI Challenge. It tends to analyze which clinical factors contribute to cases of COVID-19 getting severe and tries to build a basic ML model to address this.

- Which patients would require ICU?
- Which patients would require ventilation?
- Which patients would seek HCP Support?
  
To address these problems, this notebook deals with creating a ML Tool that can predict the cases confirmity of the basis of clinical results. If the clinical data can be used to accurately predict the cases confirmity, it can also be used to predict how worse the case gets and the person may seek ICU's / ventilations from there on.


### Stages of notebook
1. What we actually know?
2. Datasets used in notebook
3. Wrangling the data
4. Doing the Machine Learning


#### What we actually know?
The World Health Organization (WHO) characterized COVID-19, caused by SARS-CoV-2, as a pandemic on March 11, while the exponential increase in the number of cases was risking to overwhelm health systems around the world with a demand for ICU beds far above the existing capacity, with regions of Italy being prominent examples

#### The Dataset used in this notebook
This work reports results from the Kaggle challenge Diagnosis of COVID-19 and its clinical spectrum created by the Hospital Israelita Albert Einstein in São Paulo, Brazil.

The dataset contains anonymized data from patients seen at the Hospital Israelita Albert Einstein in São Paulo, Brazil, and who had samples collected to perform the SARS-CoV-2 RT-PCR and additional laboratory tests during a visit to the hospital.

All data were anonymized following the best international practices and recommendations. All clinical data were standardized to have a mean of zero and a unit standard deviation.
