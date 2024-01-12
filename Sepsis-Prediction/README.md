### Sepsis Prediction

Sepsis is a very serious problem that happens when the body reacts badly to an infection, causing harm to tissues, organs, or even death. Around the world, about 30 million people get sepsis each year, and 6 million of them don't survive. This includes around 4.2 million babies and kids (according to WHO). It's super important to find sepsis early and treat it with antibiotics quickly because waiting even just an hour to start treatment can make the chance of survival go down by 4-8%.

Here are exploratory analysis of clinical data and developing the best model for early prediction of the sepsis among patients.

**Content of Notebook:**

1. Exploratory Data Analysis
2. Feature Engineering
3. Model Selection
4. Tunning the model's hyperparameters


### Dataset's attributes:

List all the attributes in the data. Label continuous attributes with *c* and discrete with *d*.

**Vital signs - columns 1-8**
* HR - Heart rate (beats per minute);
* O2Sat - Pulse oximetry (%);
* Temp - Temperature (Deg C)
* SBP - Systolic BP (mm Hg)
* MAP - Mean arterial pressure (mm Hg)
* DBP - Diastolic BP (mm Hg)
* Resp - Respiration rate (breaths per minute)
* EtCO2 - End tidal carbon dioxide (mm Hg)

**Laboratory values - columns 9-34**
* BaseExcess - Measure of excess bicarbonate (mmol/L)
* HCO3 - Bicarbonate (mmol/L)
* FiO2 - Fraction of inspired oxygen (%)
* pH - N/A
* PaCO2 - Partial pressure of carbon dioxide from arterial blood (mm Hg)
* SaO2 - Oxygen saturation from arterial blood (%)
* AST - Aspartate transaminase (IU/L)
* BUN - Blood urea nitrogen (mg/dL)
* Alkalinephos - Alkaline phosphatase (IU/L)
* Calcium - (mg/dL)
* Chloride - (mmol/L)
* Creatinine - (mg/dL)
* Bilirubin_direct - Bilirubin direct (mg/dL)
* Glucose - Serum glucose (mg/dL)
* Lactate - Lactic acid (mg/dL)
* Magnesium - (mmol/dL)
* Phosphate - (mg/dL)
* Potassium - (mmol/L)
* Bilirubin_total - Total bilirubin (mg/dL)
* TroponinI - Troponin I (ng/mL)
* Hct - Hematocrit (%)
* Hgb - Hemoglobin (g/dL)
* PTT - partial thromboplastin time (seconds)
* WBC - Leukocyte count (count10^3/µL)
* Fibrinogen - (mg/dL)
* Platelets - (count10^3/µL)

**Demographics - columns 35-40**
* Age - Years (100 for patients 90 or above)
* Gender - Female (0) or Male (1)
* Unit1 - Administrative identifier for ICU unit (MICU)
* Unit2 - Administrative identifier for ICU unit (SICU)
* HospAdmTime - Hours between hospital admit and ICU admit
* ICULOS - ICU length-of-stay (hours since ICU admit)


**Outcome - column 41**
* SepsisLabel - For sepsis patients, SepsisLabel is  1  if  t ≥ t sepsis−6  and  0  if  t < t sepsis−6 .
* For non-sepsis patients, SepsisLabel is  0 .
