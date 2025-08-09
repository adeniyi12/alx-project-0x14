## API Overview
The api provides extensive and complete and updated data for over 9 milion titles ( movies, series and episodes)

## API Version
Version 1.0.0

## Available Endpoints
1. Fetch all titles
2. Fetch a single title
3. Fetch all titles by type
4. Fetch all titles by year
5. Fetch all titles by rating
6. Fetch all titles by genre
7. Fetch all titles by language
8. Fetch all titles by country
9. Fetch all titles by director
10. Fetch all titles by actor
11. Fetch all titles by plot
12. Fetch all titles by poster

## Request and Response Format
The API uses JSON for both requests and responses. e.g
```json
{
    "title": "The Matrix",
    "year": 1999,
    "rated": "R",
    "released": "31 Mar 1999",
    "runtime": "136 min",
    "genre": "Action, Sci-Fi",
    "director": "Lana Wachowski, Lilly Wachowski",
    "writer": "Lilly Wachowski, Lana Wachowski",
    "actors": "Keanu Reeves, Laurence Fishburne, Carrie-Anne Moss, Hugo Weaving",
    "plot": "A computer hacker learns from mysterious rebels about the true nature of his reality and his role in the war against its controllers.",
    "language": "English",
    "country": "USA",
    "awards": "Won 4 Oscars. Another 34 wins & 44 nominations.",
    "poster": "https://m.media-amazon.com/images/M/MV5BNzQzOTk3OTAtNDQ0Zi00ZTVkLWI0MjMtMDllMGYxOWU3YzE0XkEyXkFqcGdeQXVyNjU0OTQ0OTY@._V1_SX300.jpg",
    "ratings": [
        {
            "source": "Internet Movie Database",
            "value": "8.7/10"
        },
        {
            "source": "Rotten Tomatoes",
            "value": "89%"
        },
        {
            "source": "Metacritic",
            "value": "73/100"
        }
    ],
    "metascore": "73",
    "imdbRating": "8.7",
    "imdbVotes": "1,307,077",
    "imdbID": "tt0133093",
    "type": "movie",
    "dvd": "15 Jun 1999",
    "boxOffice": "$171,470,677",
    "production": "Warner Bros. Pictures",
    "website": "http://thematrix.com",
    "response": "True"
}
```

## Authentication
To access the API, you need to provide a valid API key in the request header. The API key is provided in the response when you register for an account.

## Error Handling
The API returns appropriate HTTP status codes and error messages for invalid requests or server errors.

## Usage Limits and Best Practices
The API has a usage limit of 1000 requests per day. Please use the API responsibly and avoid making too many requests in a short period of time.