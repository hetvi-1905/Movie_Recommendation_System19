# π¬Movie_Recommendation_SystemπΏ
![Movie_Recommendation_System19](https://user-images.githubusercontent.com/84613393/198863557-3aed9695-a34c-4cf9-b574-3a80a8b04ee2.png)

## π Brief Intro 
A Web Base user-input Movie Recommendation Engine using Cosine Similarity, built to give recommendation based on the user's previous choice of a movie.

## π Importance 
Such recommender are used to filter and predict only those movies that a corresponding user is most likely to want to watch.

## π₯ Demo Video 
https://user-images.githubusercontent.com/84613393/198866938-39c80bf8-d702-4adf-a88d-045281625890.mp4


## π Dataset
The data set used for this notebook is a TMDB 5000 Movies which was generated from The Movie Database API and uses the TMDb API.

## π Pipeline 
<ul>
  <li> Merging the Genre, Cast , Crew , Keywords columns into one column named Tags.</li>
  <li> Then clearing out all the other columns except Movie_ID , Title as Movie Name and Tags. </li>
  <li> Using Stemming, Count Vectorization and Feature Extraction on Tags column , thus creating Vectors for each movie. </li>
  <li> Applying Cosine Similarity on each Movie Vectors. </li>
  <li> Sorting and giving top 5 nearest cosine similar movies based on the user input choice of movie. </li>  
</ul>

## π― Deployment at Heroku
I have deployed the ML-Pipeline on a Web application using Flask.
https://movie-recommender2002.herokuapp.com/

## π· Screenshots
Landing Page 
![Screenshot (484)](https://user-images.githubusercontent.com/84613393/198864582-9814d904-934b-4af0-b29b-c068b071d43d.png)
User Input
![Screenshot (485)](https://user-images.githubusercontent.com/84613393/198864610-9cd40c2d-14ba-4861-a5d1-93eca3697e99.png)
Output
![Screenshot (486)](https://user-images.githubusercontent.com/84613393/198864648-4883732f-4091-43e6-8ced-334c3f37caa5.png)

 ## π¨ Tech-Stack



 <ul>
  <li> Front-end:Streamlit </li>
  <li> Back-end:Flask </li>
  <li> Machine Learning Libraries:Numpy, Pandas, NLTK, Cosine Similarity, Vectorization</li>
 </ul>
