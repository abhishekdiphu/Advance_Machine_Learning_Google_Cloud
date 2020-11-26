# Advance_Machine_Learning_Google_Cloud
Coursera specializations Projects

Please follow the follwing steps first: 
```
git clone https://github.com/GoogleCloudPlatform/training-data-analyst
cd training-data-analyst > courses > machine_learning >
```




## COURSE 4

Sequence Models for Time Series and Natural Language Processing



# lab 3 : real world data: Points to remember:

- 1. improving loss function : instead of using a single prediction , take multiple predictions from  multiple time steps and average them out , to compute the loss function.

## Case study : tempreture deatils from 36 weather station 
-2. split the sequences.
-3. chop it into multiple seq , good data aug. trains faster.
-4. take emprical method.
-5. length of the sub seq length.
-6. do good feature enginnering .like for yearly prediction , avg last yr is a good idea
-7. overplaping seq and non overlaping seq.
-8. propagate states between batches.
-9. multiple predic in time ahead like temp for next 10 days . 
-10. use a differnt model ecoder decoder .
-11. or get  the pred from one time step again put it back as a feeback along with the state, 
and , but lonnger preds will be in-accuate .(re-sampling)

-12. one model or multiple model 
-13. multi-models for mutplle stations  
-14. resamping data


## COURSE 5
Recommendation Systems with TensorFlow on GCP

