# practicalMLearning

Various devices equipped with embedded accelerometers can be worn on the body during physical exercise to collect data for subsequent analysis of the quality of the exercise after the fact.  These devices are used to measure quality of performance of the movements of arms, legs etc.  Resulting data is trained by resampling with cross validation to come up with reproducible metrics for accuracy and error rates to classify each performance of the exercise.  The data we use was collected from 6 participants who performed one set of 10 repetitions of the Unilateral Dumbbell Biceps Curl in five different variations of the specified exercise:
* Class A - exactly according to the specification
* Class B - throwing the elbows to the front
* Class C - lifting the dumbbell only halfway
* Class D - lowering the dumbbell only halfway
* Class E - throwing the hips to the front

#### GOALS
The goal of this study is to make a reasonable prediction.  To do this, we run models that produce predictions typical of each model.  We compare the metrics of each (accuracy and error rates) & select the best prediction as our outcome.  We focus on the 'classe' variable in the above described training set: A,B,C,D,E.  
