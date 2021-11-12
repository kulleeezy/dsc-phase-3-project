
# Phase 3 Project

## Project Overview

For this project, I used a database from Kaggle based on SyriaTel. By using OSEMN, the data science process, I showed my ability to obtain, clean, explore, model, and interpret data. I used several machine learning models in order to finally choose the best predictive model for SyriaTel to be able to identify why customers are churning, as well as give them general insights about their business. 



## EDA

![image](https://user-images.githubusercontent.com/53548138/141460254-30ecc5a7-5a47-46f0-bde1-5925e63c5749.png)

I was able to tell that 85% of customers were loyal, as opposed to 14% of the customers who were churning. Although there were less customers churning, from a business aspect it is best to further decrease that amount and promote customer retention. My findings allowed me to look further into what was causing churn to help SyriaTel work on those things.



![image](https://user-images.githubusercontent.com/53548138/141461123-cbd11a88-843c-4d92-a457-013f6b525ece.png)


This heat map allowed me to see the features that strongly correlated with churn. They were total day charge, customer service calls, and total day charge/plan.

Recommendations for SyriaTel would be to curate more options that tailor the customers' needs more personally. It seems as if more unlimited plans would help a ton, since daily costs of usage is what is running the customers away. Also, when better plans are created, it may bring a decrease in those calls. However, there should definitely be some sort of training to those employees to ensure they are diffusing the customers' situations properly so they don't resort to churn.


### Final Model Findings

![image](https://user-images.githubusercontent.com/53548138/141461674-dd84a474-6454-4945-824f-d395bb173cad.png)

My best model, the Random Forest model found that our heat map was in fact correct about which features cause customers to churn the most, and was 95% accurate in classifying churn. Our recall, which measured how well the model identified true positives was 82%.


