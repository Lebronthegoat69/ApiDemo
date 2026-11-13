# ApiDemo

## Project Description

ApiDemo is an ASP.NET Core Razor Pages application that demonstrates how to create and use Web API endpoints. The application allows users to retrieve posts as JSON, add new posts, and display post information on a dashboard using JavaScript fetch.

## Features

- GET API endpoint that returns all posts as JSON.
- POST API endpoint that adds new posts.
- Automatic model validation using Data Annotations.
- Razor Pages dashboard.
- JavaScript fetch retrieves posts from the API.
- Displays the total number of posts.
- Displays the five most recent post titles.

## Technologies Used

- C#
- ASP.NET Core
- Razor Pages
- Web API
- JavaScript
- HTML
- CSS
- Visual Studio 2022

## API Endpoints

### GET /api/posts

Returns all posts in JSON format.

### POST /api/posts

Adds a new post to the application.

Example JSON:

```json
{
  "title": "My New Post",
  "content": "This post was added using the API."
}
```

The application validates the title and content before adding a post.

## Dashboard

The Dashboard page uses JavaScript fetch to retrieve posts from `/api/posts`.

It displays:
- The total number of posts.
- The five most recent post titles.

## How to Run the Project

1. Clone or download this repository.
2. Open `ApiDemo.csproj` in Visual Studio 2022.
3. Build the project.
4. Run the application using the green Play button.
5. Visit `/Dashboard` to view the dashboard.
6. Visit `/api/posts` to view the JSON data.
<img width="975" height="64" alt="image" src="https://github.com/user-attachments/assets/b36d8702-23a2-42d8-9ff8-ceac0c5c9c4e" />
<img width="663" height="274" alt="image" src="https://github.com/user-attachments/assets/4287a3d1-9105-4224-896a-80f4ae5625b9" />
<img width="975" height="127" alt="image" src="https://github.com/user-attachments/assets/f0aa031a-03fe-4f9d-b4e7-11d7a23fabdd" />
<img width="855" height="270" alt="image" src="https://github.com/user-attachments/assets/8b8979b5-879c-4876-8b53-d44c7f03bfbd" />



## Author

Sam
