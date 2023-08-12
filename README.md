# A Complete Cycle of Credit Risk Modelling 

As a Machine learning project, We aim to use data science techniques to model three important notions in Credit risk management :
Probability of Default (PD), Loss Given Default (LGD - Recovery rate) and Exposure at Default (EAD - CCF).

The data set used for this purpose, is a <b>portofolio of 466285 loans</b> open-source data (on Kaggle) and our purpose is to build models that are compliant with Basel II and Basel III Bank's regulations.

The Data set is well described in the DataPreparation file !!! And there is a link to download it. The data are from 2007 - 2014. and we use year 2015 to monotor the obtained PD model. 

At the end of this work, we compute the <b>Expected Loss (EL)</b> and the <b>Regulatory Capital (F- IRB) </b>  that will be expected by the regulations for this loans portfolio.

<b>RESULTS : </b> We obtain for this loans portfolio with a total amount of <b> 6.67 Billlions<b>  (see the file LGD-EAD EL-RegCap)
>>>>>>> The <b>Expected Loss</b> is approximatively <b>7.6 %</b> of the portfolio total amount, that is <b>511.66 Millions</b>
>>>>>>> The Regulatory capital is approximatively <b>5.3 %</b> of the portfolio total amount, that is <b>357.79 Millions</b>\

The main Data Science techniques used in this project are :

- Weight of evidence   - Information value   - Fine classing   - Coarse classing   - Linear regression - Logistic regression

- Area Under the Curve  - Receiver Operating Characteristic Curve - Gini Coefficient - Kolmogorov-Smirnov - Assessing Population Stability


The work is subdivide as it follows :

>>>> <b> I - DATA PREPARATION </b>
      
            Import, Explore, Preprocess (formatting, dealing with missing values..)
 
>>>> <b> II - PD Model </b>
           
         - Data Preparation : format Independent / Dependent variables, identification of Good (non-defaulter)/ Bad (defaulter)
         - We will use the Logistic Regression model to estimate the PD
         - A section will cover PD monitoring
    
>>>> <b> III - LGD Model </b>

         - We will use a two stage model : First stage , Logistic Regression and at the secong stage Linear Regression 

>>>> <b>  - EAD Model </b>
                    
         - We will use a Linear Regression modeling

