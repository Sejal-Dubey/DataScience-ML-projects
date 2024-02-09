# DataScience-ML-projects
# 1.# Statistics for Data Science

# a.Steel Industry Energy Consumption
In this group project,we have used this dataset from kaggle- https://www.kaggle.com/datasets/csafrit2/steel-industry-energy-consumption,
where we have performed statistical analysis of Steel Industry Energy Consumption.

>This dataset contains information on the Electrical Energy
consumption by a Steel Industry Plant of Korea 

-Time Duration : 1 Year

-Time Interval: 15 mins

-Number of Records : 35041

-Number of Variables : 11

>We performed descriptive statistics on following variables-Usage _kwh,Lagging _Current_Reactive _Power _kVArh,Leading _Current_Reactive _Power _kVArh,CO2,Lagging _Current _Power_,Factor,Leading _Current _Power_
Factor.

>We plotted density plot,histogram,box plot,scatter plot,violin plot and correlation heatmap,for data visualization.

>We applied sampling technique using Simple Random Sampling and concluded that sample is a part of population.

>Through correlation heatmap it was concluded that lagging_current_reactive_power was highly correlated with useage_kwh so we used it as x in the linear regrssion equation and predicted the related useage_current and we got R^2 as 0.8031.

# Inferences from this analysis-
 -This dataset has a Positively Skewed Data. Hence 3 σ rule cannot be used to remove outliers.

-Homoscedasticity can be achieved to some extent for data of Usage and Lagging Current Reactive Power.

-Linear Regression is applicable to predict the Amount of Energy consumed keeping Lagging Current Reactive Power as Input.

 -Also, we predict amount CO2 from the Usage by doing a Linear Regression.

 -The Density Plots shows that random sampling can represent the population data.




# 2.# STAIML(Software tools for AIML)

# b.Customer Review Analysis

# ->Project Idea:
A dataset of customer reviews for different brand of shoes available on Amazon has been used in this project.Basically,the goal of the project is to analyze the reviews of each customer using # Sentiment Analysis and then performing necessary statistical analysis in excel to draw insightful conclusions.

# ->Significance:
Business values customers's feedback to stay ahead in market,so analyzing the needs,demands or complaints of customers has become crucial.Mostly,people across the world speak in different languages and prefer to review in their native languages.To resolve the task combining NLP and statistics tools will be apt option to review each sentiment and take actions accordingly to stay ahead of the curve.


The following steps has been taken inside the project:

# >Step1:Using NLP to give positive(pos),negative(neg),neutral(neu),compound score to the written reviews.

# >> Libraries used:

>> Pandas-data reading

>> NlTK(Natural Language Toolkit)-for necessary nlp pre-processing

>> Vader(Sentiment analyzer)-for giving polarity scores(positive,negative,neutral,compound).

# >Step2:Performed statistical analysis.
The dataset has 11 columns and 6824 rows.

Columns:url,product_name,reviewer_name,review_title,review_text,review_rating,verified_purchase,review_date,helpful_count,uniq_id,scraped_at



>>In the uploaded excel ,10 sheets are made each displaying necessary observations:

>>i.downloaded_dataset: the original dataset

>>ii.new_dataset: the new dataset created using NLP has 4 extra columns named pos,neg,neu,compund with their respective sentiment score.

>>iii.review_title: plotting of Pivot Chart of review_text vs average of pos,neg,neu,compound

>>iv.Sheet3:plotting of average of review_rating vs product_name

>>v.compound: Pivot Chart of average of compound score vs product_name

>>vi.pos: Pivot Chart of average of pos(positive) score vs product_name

>>vii.neg: Pivot Chart of average of neg(negative) score vs product_name

>>viii.neu: Pivot Chart of average of neu(neutral) score vs product_name

>>ix.average of review_rating: Pivot chart average of review_rating vs unique_id(of customer) based on the product_name(as filter).

>>x.Dashboard: Overall analysis in the form of dashboard including filters like date,review_rating and overall analysis of review_title and observing average_rating vs product_name using filter of product_name.



The related dataset with necessary analysis and dashboard has been uploaded in the zip folder.
