# Improve Your English Essay with Artificial Intelligence

### University of California, Berkeley<br>
**W266 - Natual Language Processing with Deep Learning**<br>
Spring, 2023

**Contributors:**
  1. Iris Lew 
  2. Srila Maiti
  3. Heesuk Jang

**Objective & Background:** <br>

  Our goal is to develop the Automated Essay Scoring (AES), the task of NLP technology to automatically assign scores to essays at scale particulary to help English Language Learners (ELLs) from grade 8-12. The dataset is obtained from the [Kaggle website](https://www.kaggle.com/competitions/feedback-prize-english-language-learning/data) that comprises 3,911 argumentative essays. We introduced BERT-base_cased and BERTweet-base for the text regression task. To improve the performance, we then employed K-means clustering (k = 3) with stratified two-fold cross validation on each of the BERT base models. 
  
  **Key Files for the Final Submission:**
  
- Final report: **report/final_report.pdf**
- Main code that contains the final experiments: **W266_essay_evaluation_final.ipynb**
- Notebook with the hyperparameter tuning to define the best model: **heesuk\W266_Regression_with_BERT.ipynb**
- Presentation Google PPT: [Improve Your English Essay with Artificial Intelligence](https://docs.google.com/presentation/d/1xtAPxn-lysW8vIg6IQigyiGuU3QxiTP7fljnBX9c0LU/edit#slide=id.p)

**Note:** <i>W266_Regression_with_BERT.ipynb</i> is developed primarily to fine-tune different sets of hyperparameters using BERT-base-case then finally to find the best set of hyperparameters to apply our final experiments in the <i>W266_essay_evaluation_final.ipynb</i>. However due to the oversized content in the <i>W266_Regression_with_BERT.ipynb</i>, the results of training the models and predicting values on the test dataset are unable to display. Please feel free to reach out if you have any questions regarding the process and results. In the meantime, the screenshots of the model summary, architecure, and evoluation of the learning history of the best model are attached below for your reference: 

<img width="836" alt="Screen Shot 2023-04-15 at 11 35 32 PM" src="https://user-images.githubusercontent.com/83621566/232277283-8ec6b059-a4b5-4a65-addd-32e7b2007c1b.png">
<img width="545" alt="Screen Shot 2023-04-15 at 10 31 32 PM" src="https://user-images.githubusercontent.com/83621566/232276908-3a41410d-55be-4b4c-a2a7-71227f5c6126.png">
<img width="1144" alt="Screen Shot 2023-04-15 at 10 31 45 PM" src="https://user-images.githubusercontent.com/83621566/232276934-887b0bc7-e7e9-46c8-92b9-752aa202a011.png">
<img width="459" alt="Screen Shot 2023-04-15 at 10 32 29 PM" src="https://user-images.githubusercontent.com/83621566/232276958-8bbfb2cb-8c29-48a0-bf6f-6a08a2944e3a.png">
<img width="2547" alt="Screen Shot 2023-04-15 at 11 37 40 PM" src="https://user-images.githubusercontent.com/83621566/232277532-3fa46d22-db49-4aa5-ba0a-fb0b71083003.png">
