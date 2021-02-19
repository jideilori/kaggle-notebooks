# chest xray pneumonia

Link to the dataset -  https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia

### Results 
confusion matrix
|TN=181|FP=53|
|---|--|       
|FN=20|TP=370|

since recall = tp/(tp+fn) i.e 370/(370+20) = 95% this means out of the 390 pneumonia images, we classifed 95% correctly
and precision =  tp/(tp+fp) i.e 370/(370+53) = 87% which means how many of the pneumonia cases labelled by the model as positive are actually positive.

We need to optimize recall over precision because there will consequences associated with a false negative i.e the model predicts that the patient doesnt have pneumonia when infact the person has pneumonia.
