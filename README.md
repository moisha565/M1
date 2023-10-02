# M1
M1
movies = ["The Shawshank Redemption", "The Godfather", "The Dark Knight", "Schindler's List", "Pulp Fiction", "The Lord of the Rings: The Return of the King", "Forrest Gump", "Star Wars: Episode V - The Empire Strikes Back", "Inception", "The Silence of the Lambs"]
 
ratings = [9.3, 9.2, 9.0, 8.9, 8.9, 8.9, 8.8, 8.7, 8.7, 8.6]
 
movie_ratings = {}
 
for i in range(len(movies)):
    movie_ratings[movies[i]] = ratings[i]
 
json_object = json.dumps(movie_ratings, indent=4)
 
print(json_object)
