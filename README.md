# Flatdango - Movie Ticket Booking App

Flatdango is a simple web application that allows users to view a list of movies, check the available tickets, and purchase tickets for their desired films. Users can also mark movies as their favorites, and the app shows movie details including runtime, showtime, and the remaining available tickets.

## Features
- Display a list of movies fetched from a JSON file.
- Show detailed information for each movie, including a poster, runtime, showtime, and available tickets.
- Users can "buy" tickets for a film (which decreases the available tickets).
- Movies can be marked as favorites, and users can toggle this status.
- A "delete" button to remove films from the list.

## How to Use

1. **View the Film List**: When you open the app, you will see a list of films. Click on a film to view its details.
2. **Buy Tickets**: If tickets are available, you can click the "Buy Ticket" button to reduce the number of available tickets.
3. **Favorites**: Mark a movie as a favorite by clicking the "Add to Favorites" button. It will change to "Remove from Favorites" if the film is added.
4. **Delete Films**: Films can be deleted from the list by clicking the "Delete" button.

## Files Overview
- `index.html`: The HTML structure of the application.
- `flatdango.js`: The JavaScript logic that fetches movie data, handles user interactions (buying tickets, adding to favorites, etc.).
- `flatdango.css`: The CSS file for styling the movie list and details sections.
- `db.json`: The JSON file containing an array of movie objects used by the app to display film details.

## Example JSON Structure
Here is an example of the JSON format for each film:
```json
{
  "id": "1",
  "title": "The Giant Gila Monster",
  "runtime": "108",
  "capacity": 30,
  "showtime": "04:00PM",
  "tickets_sold": 27,
  "description": "A giant lizard terrorizes a rural Texas community...",
  "poster": "https://www.gstatic.com/tv/thumb/v22vodart/2157/p2157_v_v8_ab.jpg"
}
# code-challenge-week3
