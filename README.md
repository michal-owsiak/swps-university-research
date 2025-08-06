<div align="center">
    <img src="public/swps_logo.png" width="1800" alt="SWPS University logotype">
</div>

## **A study of Poles' psychedelic and non-psychedelic mystical experiences in relation to fear of death, emotional empathy, and life satisfaction**



This repository contains a [Jupyter Notebook](https://github.com/michal-owsiak/research-on-psychedelic-and-non-psychedelic-mystical-experiences/blob/main/research.ipynb) that recreates the analysis from a master’s thesis conducted at SWPS University. The original study, performed using **IBM SPSS Statistics**, explores the relationship between psychedelic use and so called mystical experiences with the following variables:

- Fear of death
- Emotional empathy
- Life satisfaction

The Jupyter Notebook provides a `Python`-based approach to replicate the analysis conducted in the thesis. 

## **Project background, aims, and methods**

**Background:** Studies have consistently shown that controlled psychedelic use and mystical experiences can produce positive outcomes such as increased life satisfaction, enhanced empathy, and reduced fear of death. However, despite the extensive research, there still remain gaps in the available data. 

**Aims:** The study tested whether individuals who (H1) use psychedelics or (H2) have had a complete mystical experience exhibit (1) higher life satisfaction and (2) greater emotional empathy, along with (3) lower fear of death. It also examined if (H3) a complete mystical experience provides a better explanation for the outcomes compared to psychedelic use alone.

**Methods:** An online survey that included questions about psychedelic use and questionnaires measuring mystical experiences, fear of death, emotional empathy, and life satisfaction. A sample of 686 subjects was analyzed using two-way ANOVA and linear regression modeling. 

## **Data collection and tools used**

_Data source_: Owsiak, M. (2025). Dataset - Psychedelic and Non-Psychedelic Mystical Experiences in Polish Adults. [https://doi.org/10.17632/bhkb7zmb9v.1](https://doi.org/10.17632/bhkb7zmb9v.1)

The dataset was collected through an online survey distributed from February 17, 2023, to March 29, 2023. It includes:

- **Demographic Metrics:** Basic information such as age, gender, education, and spiritual worldview.
- **Meditation/Mindfulness Practice:** Information on participants' meditation or mindfulness practices.
- **Psychedelics Use:** Data on the types and frequencies of psychedelic substances used.
- **Mystical Experiences:** Responses to questions and questionnaires regarding mystical experiences.
- **Revised Mystical Experience Questionnaire (MEQ30):** Measures intensity of mystical experiences.
- **Perth Empathy Scale (PES):** Assesses emotional empathy.
- **Satisfaction with Life Scale (SWLS):** Measures overall life satisfaction.
- **Death Attitude Profile - Revised (DAP-R-PL):** Evaluates attitudes and fear of death.
- **Subjectively Perceived Influence:** Participants' reflections on how their mystical experiences impacted their psychological metrics.

The collected dataset was then processed and analyzed using following technologies:

**Languages, frameworks and environments:**
```
> Python
> Jupyter Notebook
> Markdown
```
**Libraries and packages:**
```
> pandas
> NumPy
> SciPy
> statsmodels
> pingouin
> Matplotlib
> seaborn
> IPython
```



## **Data analysis and visualization**

### **Data wrangling and cleaning**

Using plain `Python` along with `pandas` and `NumPy` predefined functions, the following steps were performed:

- Merging duplicated variables into consistent dataset
- Recoding questionnaires' scorings
- Calculating summed results
- Cleaning and preparing data for analysis

### **Data analysis**

- Testing parametric assumptions using `SciPy` extension: `statsmodels` package
- Conducting series of two-way ANOVA using `statsmodels`
- Performing series of one-way ANOVA using `statsmodels`
- Performing post-hoc tests using  `pingouin` package which laverages `NumPy` and `pandas` libraries
- Building linear regression heirarchical models using `statsmodels` package

### **Data visualization**

The results of the study were visualized as bar plots. For this purpose, `Matplotlib` and `seaborn` libraries were employed.

## **Results and conclusions**

**Results:** Complete mystical experiences were significantly linked with lower fear of death, higher life satisfaction, and greater overall and positive-emotional empathy. Psychedelic users exhibited fear of death lower than non-users, with no significant effects on overall emotional empathy or life satisfaction. The users group also demonstrated significantly lower negative-emotional empathy than non-users.

**Conclusions:** While causal inference cannot be drawn from this study, it suggests that mystical experiences, regardless of their trigger, may potentially mitigate death anxiety, enhance life satisfaction, and foster a greater inclination to share positive emotions with others.
