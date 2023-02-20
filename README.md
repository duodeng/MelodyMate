# Song Recommender Project
MelodyMate is a music recommendations app that suggests new songs and artists to users based on their music preferences. 
The app uses advanced algorithms to analyze users' listening history and creates personalized playlists, curating new songs and artists to match their taste. Users can also explore new genres and discover music from around the world. MelodyMate's intuitive interface and user-friendly design.

I am trying to come up with ways to enhance our music recommendations. One of the new features I'd like to research is to recommend songs (not only bands). I'm also aware of the limitations of our collaborative filtering algorithms, and would like to give users two new possibilities when searching for recommendations:

- Songs that are popular around the world right now, independently from their tastes.
- Songs that are actually similar to the ones they picked from an acoustic point of view.

## Data Collection
To start our project, I collected data from popular songs on the Billboard 100 and 30 playlists from Spotify. I cleaned the data to ensure that each song was only included once.

## Clustering
I then used clustering algorithms to group spotify data songs that are similar to each other. Our idea is that if a user inputs a song from one group, I'll prioritize giving them recommendations of songs from that same group.

## Authors
Duo Deng

## Acknowledgements
Billboard
Spotify

