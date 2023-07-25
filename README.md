# Sentiment-Analysis-of-Course-Review-using-DistilBERT-Transfer-Learning

## My Final Result is on Kaggle, you can view it in here
https://www.kaggle.com/code/nadyadtm/distilbert-with-class-weight/notebook

Progress List

| Date  | Progress |
| ------------- | ------------- |
| 16/05/2023  | I found that doing downsampling isn't a good idea. The accuracy is very low (25%) and the loss is more than one (>1) in every epoch. Maybe there are some loss information. So I'll try to use class weight in the loss function. The file will be push soon.  |
| 17/05/2023 | Have using class weight in loss function, but the accuracy is in 50%. The file has been pushed (distilbert-with-class-weight.ipynb and distilbert-with-downsampling.ipynb). Next will try to labeling the sentiment based on rating threshold and need to do more preprocessing. Also I'll try to train with more epoch. **UPDATED** for downsampling, the result is around 40%|
| 21/05/2023 | Try to labeling the sentiment based on rating threshold (4-5 positive, 3 neutral, 1-2 negative). After I labeled the sentence, the accuracy changed to around 80% |
| 22/05/2023 | Add more text analysis (wordcloud) and some preprocessing and simple narration, try to increase epoch, using parameter based on paper (optimizer Adam and learning rate 5-e5), but the precision and recall in negative and neutral class is very low. I have been update it to distilbert-with-class-weight.ipynb |
| 24/05/2023 | Add comparison to BERT based |
