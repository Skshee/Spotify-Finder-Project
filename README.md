🎵 Spotify API Explorer

A Python project that interacts with the Spotify API to search for artists and retrieve their top tracks. It uses client credentials authentication to fetch data and display results in the console.

🚀 Features

Authenticate with Spotify API using client credentials

Search for an artist by name

Fetch the top tracks of an artist

🔑 API & Tokens

This project utilizes the Spotify Web API, which requires authentication via a client credentials flow. The authentication process involves generating an access token using the provided client ID and client secret. This token is then used in API requests to access Spotify's data.

Authentication: The project retrieves an access token by making a request to the Spotify authentication server.

Bearer Token Usage: The token must be included in the request headers as a Bearer token for all API calls.

Search Endpoint: The /v1/search endpoint is used to find artists based on a query string.

Top Tracks Endpoint: The /v1/artists/{id}/top-tracks endpoint fetches an artist’s most popular songs, requiring an additional market parameter.

📌 Usage

Search for an artist by name.

Retrieve the top tracks of the artist.

Display the results in the console.

📦 Dependencies

requests

python-dotenv

🔥 Example Output
```
{
  "artist": "Selena Gomez",
  "top_tracks": [
    "Lose You to Love Me",
    "Rare",
    "Look At Her Now"
  ]
}
```

🤝 Contributing

Feel free to fork, submit issues, or open pull requests!

📜 License

This project is licensed under the MIT License.

