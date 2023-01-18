# medicalQuestionAndTags
We use Bert to predict the tags of a medical questions. We train our model on data from 4 different medical websites with questions and tags. With only 5 epochs, ww get pretty good prediction on multi-label classification.

This is the categorical accuracy which is true accuracy for over 50 tags, not binary-accuracy which can give completely wrong prediction but you can get 95% accuracy due to the numbers of non-tags label (we only have few tags for a question - 5% of number of tags). 
