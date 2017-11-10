# Mongo_Movie_Data (Detailed Design Document)

**Project Description**  
The goal of this project is to help people find good movies to watch. This project will use MongoDB. Potential users can be anyone who wants to make better movie selections. This project can also help to showcase my database skills and market myself for internships.  

**Data Dictionary**  
The data that will be stored is rows of movies and columns that have attributes of the movies.

Final Columns  
C1 - Genres: what genre categories describe the film  
C2-  Id: a unique number that identifies each row (film) in the database  
C3- Keywords: words that describe the plot of the film  
C4- Title: name of the movie  
C5- Popularity: how well-liked the movie is by IMDB users  
C6- Date: when the movie was released  
C7- Vote average: what IMDB users rated the movie out of 10   

To find the highest rated movies by IMDB popularity in the entire db  
To find the highest rated movie by vote avg within a genre he likes  
To see which are the most popular movie in a genres  
To input keywords and return movies that match those words  
To movies released in a specific time period  

Schema of the Database: Since I am using Mongo, each row of the table will be a document. 

![ScreenShot](https://raw.github.com/basillatif/Mongo_Movie_Data/
