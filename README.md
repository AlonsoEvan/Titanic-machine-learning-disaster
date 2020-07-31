# Titanic-machine-learning-disaster
Kaggle project

Version 2.0 of a project made a while ago.

Competition sites like Kaggle define the problem to solve or questions to ask while providing the datasets for training your data science model and testing the model results against a test dataset. The question or problem definition for Titanic Survival competition is described at Kaggle.

Knowing from a training set of samples listing passengers who survived or did not survive the Titanic disaster, can our model determine based on a given test dataset not containing the survival information, if these passengers in the test dataset survived or not.

We may also want to develop some early understanding about the domain of our problem. This is described on the Kaggle competition description page.

Here are the highlights to note.

On April 15, 1912, during her maiden voyage, the Titanic sank after colliding with an iceberg, killing 1502 out of 2224 passengers and crew. Translated 32% survival rate. One of the reasons that the shipwreck led to such loss of life was that there were not enough lifeboats for the passengers and crew. Although there was some element of luck involved in surviving the sinking, some groups of people were more likely to survive than others, such as women, children, and the upper-class.


## Table of Contents
<details open>
<summary>Show/Hide</summary>
<br>

1. [ File Descriptions ](#File_Description)
2. [ Technologies Used ](#Technologies_Used)    
3. [ Structure ](#Structure)
4. [ Future Development ](#Executive_Summary)
</details>

## File Descriptions
<details>
<a name="File_Description"></a>
<summary>Show/Hide</summary>
<br>
  
* train.csv  - the training set
* test.csv - the test set
* sample_submission.csv - a sample submission file in the correct format

*Columns*
survival	
pclass	
sex		
Age		
sibsp	
parch	
ticket	
fare		
cabin		
embarked
</details>

## Technologies Used:
<details>
<a name="Technologies_Used"></a>
<summary>Show/Hide</summary>
<br>
    
* <strong>Python</strong>
* <strong>Pandas</strong>
* <strong>Numpy</strong>
* <strong>Matplotlib</strong>
* <strong>Seaborn</strong>
* <strong>Scikit-Learn</strong>
* <strong>LightGBM</strong>
* <strong>XGBoost</strong>
* <strong>MissingNo</strong>
</details>

## Structure of Notebooks:
<details>
<a name="Structure"></a>
<summary>Show/Hide</summary>
<br>
  
    
1. Packages and loading
   * 2.1 Import Libraries

2. Data Preparation
   * 2.1 Meet the Data

3. The 4 C's of Data Cleaning: Correcting, Completing, Creating, and Converting
   * 3.1 Clean Data
   * 3.2 Convert Formats
   * 3.3 Split Training and Testing Data

4. Exploratory Analysis

5. Machine Learning
   * 4.1 Metrics used : Accuracy
   * 4.2 Metrics used : AUC

6. Ensembling and tuning
   * 3.1 LightGBM
   * 3.2 XGBoost
   * 3.3 Gradient Boosting

7. Producing the Submission file

Conclusion

</details>  


<a name="Executive_Summary"></a>
## Future Development
    
* Spend more time on preprocessing and feature engineering. In order to better align the CV score and Kaggle score and improve the overall accuracy.

