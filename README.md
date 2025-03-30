🎵 Spotify API Explorer

A Python project that interacts with the Spotify API to search for artists and retrieve their top tracks. It uses client credentials authentication to fetch data and display results in the console.

🚀 Features

Authenticate with Spotify API using client credentials

Search for an artist by name

Fetch the top tracks of an artist

🔑 API & Tokens

This project utilizes the Spotify Web API, which requires authentication via a client credentials flow. The authentication process involves generating an access token using the provided `client ID` and `client secret`. This token is then used in API requests to access Spotify's data.

Authentication: The project retrieves an access token by making a request to the Spotify authentication server.

Bearer Token Usage: The token must be included in the request headers as a Bearer token for all API calls.

📌 Usage

Search for an artist by name.

Retrieve the top tracks of the artist.

Display the results in the console.

📦 Dependencies

python requests library

python-dotenv

🔥 Example Output
```
Enter name of Artist:Eminem
Eminem
1:Without Me
2:Mockingbird
3:Lose Yourself
4:The Real Slim Shady
5:Love The Way You Lie
6:Till I Collapse
7:Houdini
8:Godzilla (feat. Juice WRLD)
9:Superman
10:Stan

Enter name of Artist:Shankar Mahadevan
Shankar Mahadevan
1:Mitwa
2:Sajdaa
3:Uff Teri Adaa
4:Gallan Goodiyaan
5:Shiv Tandav Stotram
6:Noor E Khuda
7:Kajra Re
8:Desi Girl
9:Enna Solla Pogirai
10:Tere Naina (From "Chandni Chowk To China")
```

💡 My Learning
- `Working with APIs` - Fetching using RESTful APIs
- `Requests Library` - get and post requests
- `JSON handling` - Parsing JSON requests and extracting useful info
- `dotenv` - Used for securely storing and handling API creds


