# Sentiment-Analysis-of-Course-Review-using-DistilBERT-Transfer-Learning

Progress List

| Date  | Progress |
| ------------- | ------------- |
| 16/05/2023  | I found that doing downsampling isn't a good idea. The accuracy is very low (25%) and the loss is more than one (>1) in every epoch. Maybe there are some loss information. So I'll try to use class weight in the loss function. The file will be push soon.  |
| 17/05/2023 | Have using class weight in loss function, but the accuracy is in 50%. The file has been pushed. Next will try to determined sentiment polarity based on ratings and need to do more preprocessing |
