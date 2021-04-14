# Personal-trAIner
A final project for ELEC879 (Internet of Things). 

In this project, Inertial Measurement Unit data in the form of time-series were obtained from a previously published paper. Sensors worn on participants performing variations of a dumbbell curl were analyzed to attempt to classify if the participant is using proper form.

The task for this project was to compare alternative machine and deep learning algorithms to the original results of the published paper. 


To reproduce this paper:

1. Download and add data.csv to the folder
2. run dataset_separation
3. run baseline_decisiontree
4. run impute_and_normalize
5. run feature_selection
6. run modelling and lstm

Source: Velloso, E.; Bulling, A.; Gellersen, H.; Ugulino, W.; Fuks, H. Qualitative Activity Recognition of Weight Lifting Exercises. Proceedings of 4th International Conference in Cooperation with SIGCHI (Augmented Human '13) . Stuttgart, Germany: ACM SIGCHI, 2013.
Read more: http://groupware.les.inf.puc-rio.br/har