# MovieServiceProject


Here are two short README templates for Task 1 and Task 2:

README for Task 1: Movie Service (Backend)
Project Name: MovieService

Description: This is a backend service that interacts with the OMDb API to fetch movie information based on the movie title or specific movie ID. The service is built using .NET 8, providing two key functionalities:

Search movies by title.
Fetch detailed information about a specific movie.
Features:

Uses HttpClient to make API requests to OMDb.
Dynamically generated API key for OMDb integration.
API endpoints to search movies and retrieve movie details.

Installation:

Clone the repository:

git clone https://github.com/YourGitHubAccount/MovieService.git
Navigate to the project folder:

cd MovieService
Restore the dependencies:

dotnet restore
Run the application:

dotnet run

Endpoints:

GET /api/movies?s={title} – Search for movies by title.
GET /api/movies/details?id={movieId} – Get detailed movie information by ID.

README for Task 2: Movie Search App (Frontend)
Project Name: MovieSearchApp

Description: A frontend Angular application to interact with the MovieService backend. It allows users to search for movies by title and view details for each movie.

Features:

Search movies by title.
View detailed information on selected movies.
Connects to the backend API for movie data retrieval.
Installation:

Clone the repository:

git clone https://github.com/YourGitHubAccount/movie-search-app.git
Navigate to the project folder:

cd movie-search-app
Install the dependencies:

npm install
Run the application:

ng serve
Navigate to http://localhost:4200 to access the app.
Technologies:

Built using Angular.
Interacts with the MovieService API.
