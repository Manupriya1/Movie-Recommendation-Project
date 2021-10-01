# Movie Recommendation Project
Designing a Movie Recommendation System
## Click here for [*Data*](https://www.kaggle.com/rohan4050/movie-recommendation-data)

## Dimensional Modelling
*Business Value*: Movie Recommendation - Input as movie name and 3 movies recommended as an output.

*Grain:* Details of the Movies released between 1902 to 2013 with their ratings.

### Dimensions
- Dim_Movie > adult, belongs_to_collection, budget, genres, homepage, id, original_language, original_title, overview,poster_path, production_companies, production_countries,release_date , runtime, spoken_languages, status, tagline, title
- Dim_User > userId
### Facts:
1. FK_1_Movie
3. FK_2 User
4. Revenue
5. Popularity
6. vote_average
7. vote_count
8. Ratings
9. timestamp

## Logical Model
![Movies Logical Data Model (BIMarathon 2021)](https://user-images.githubusercontent.com/69255270/135682649-992ab5b6-3631-40ad-bfee-295891ef2b34.png)

## Physical Model
![Physical Data Model_Movies (BIMarathon 2021)](https://user-images.githubusercontent.com/69255270/135682643-8d5ccd0b-d039-426a-92e1-809834fcf9bf.png)
