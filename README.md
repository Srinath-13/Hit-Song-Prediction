# Hit-Song-Prediction
![image](https://github.com/Srinath-13/Hit-Song-Prediction/assets/79263421/7af2a8a2-ec42-4e5c-8a39-a8d405f13f6f)

Hit Song Science uses machine learning tools to predict a song's success before publication. Hit 
Song Science may help artists and producers understand their audience and write songs that will 
appeal to them. Artists can better pick lyrics and customize songs to their audiences. Audio 
engineers may also help artists improve basic musical components to make songs more appealing, 
straightforward, and enjoyable. This research examines if song lyrics and audio quality might 
predict popularity. Statistics and analytics aside, music lovers worldwide have watched musical 
trends evolve throughout time. Popular songs are simple to spot, even when listeners have different 
musical preferences. Popular tunes evolve. The project seeks to discover hits using intrinsic music 
data

## Dataset
You would want to take a look at the [dataset](https://www.kaggle.com/datasets/theoverman/the-spotify-hit-predictor-dataset). The Spotify Hit Predictor Dataset from Kaggle contains track features retrieved via the Spotify 
Web API. The recordings are labelled '1' or '0' ('Hit' or 'Flop') based on the author's criteria. This 
dataset can be used to create a classification model that predicts whether or not a song will be a 
"Hit." The dataset contains 41,106 instances recorded over 22 attributes viz., 'track', 'artist', 'uri', 
'danceability', 'energy', 'key', 'loudness', 'mode', 'speechiness', 'acousticness', 'instrumentalness', 
'liveness', 'valence', 'tempo', 'duration_ms', 'time_signature', 'chorus_hit', 'sections', 'target' and
'decade'.

## Methodology
![image](https://github.com/Srinath-13/Hit-Song-Prediction/assets/79263421/f5b236a3-eec8-4388-95fc-f4ae272bf3a7)

## Results
### Best Standalone Model
![image](https://github.com/Srinath-13/Hit-Song-Prediction/assets/79263421/17e971d7-f1ab-41bf-92d0-b5312a656ca3)


From the above ROC-AUC plot, it is concluded that Random Forest, SVM and K-NN are reliable 
and good performing models. These models alone will be considered for ensemble learning in the 
forthcoming steps.

### Best Ensemble Model
![image](https://github.com/Srinath-13/Hit-Song-Prediction/assets/79263421/b959d66f-88cf-4d91-abbd-94b06e056c5a)

Out of all these models, Voting Classifier with Soft Voting with SVM, KNN and RF (with its 
best hyper parameters) is chosen to be the best classifier owing to its highest score and relatively 
feasible computational complexity.

### References
You might want to take a look at this [Presentation](https://github.com/Srinath-13/Hit-Song-Prediction/files/12053892/Hit.Song.Prediction.pdf)
