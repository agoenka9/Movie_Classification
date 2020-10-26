# Movie-Classification
Folder Structure
1) Final_API.ipynb - Code to retrieve youtube comments for a given video id (for eg. 'AAABB'). The code saves the comments as a csv file with the name as the corresponding video id (for ed. 'AAABB.csv')
2) Data Files
     - Movie_dataset_3subcategories.xlsx : masterlist of movies corresponding parameters such as actors, genres, directors etc., along with the target variable (1-Flop,2-Average,3-Blockbuster) and videoids
     - actor-cat.csv : Name of the actors and their corresponding categories based on twitter followers
     - cast - cast.csv : Name of the actor and their number of followers as collected from twitter ( This was carried out manually)
     - allmovies : folder containing comments corresponding to all the movies used for the project. Comments for a movie are named after their videoids
3) Feature Engineering
     - Method-1/Model_1.ipynb : Code to generate the feature matrix as per method-1. Uses different files in Data Files folder
     - Method-2/Model_2.ipynb : Code to generate the feature matrix as per method-2. Uses different files in Data Files folder
     - Method-3/Feature_Engineering_(4)_Bucket_Actors (1).ipynb : Code to generate the feature matrix as per method-3. Uses different files in Data Files folder
4) Feature Engineering Output
      Folder contains feature matrices generated under method-1, method-2, method-3 to run the models. F4_model_data_500_catex.csv,F4_model_data_target_3.csv are the files used for final model
5) Models
      - Random_Forest.ipynb : Code to generate the baseline model
      - CNN_Model.ipynb : Code that can be modified slightly (instructions commented) to generate different CNN,CRNN,MLP,RNN models for the feature matrix
