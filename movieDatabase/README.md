# Movie web site project

This project allows to generate a website containing a selection of your favorite movies with details on the movie and the possibility to see a trailer.

This folder contains 4 files:

- README.md : This file
- media.py : Definition of the movie class
- fresh_tomatoes.py : Python module containing the functions used to generate the html file displaying the movies.
- entertainment_center.py : Python file which contains the descriptions of the movies and which use the fresh_tomatoes module functions to generate the html file.

## Usage

- Complete the file **entertainment_center.py** with your film description (name of the film, short pitch, link to movie image and link to movie trailer) which should look something like this:
	```
	avatar = media.Movie("Avatar",
						 "A marine on an alien planet",
						 "https://upload.wikimedia.org/wikipedia/en/b/b0/Avatar-Teaser-Poster.jpg",
						 "http://www.youtube.com/watch?v=-9ceBgWV8io")
	```
- Execute the file **entertainment_center.py** thru the command *python entertainment_center.py*

- This will create a file **fresh_tomatoes.html** and open it in your default browser

You are done you can now enjoy the movie web site








