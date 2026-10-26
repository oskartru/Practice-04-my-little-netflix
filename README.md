# Practice-04-my-little-netflix

https://github.com/oskartru/Practice-04-my-little-netflix.git


## Project Overview
"My Favourite Movies" is a client-side movie database built with HTML, CSS and
JavaScript following the MVC pattern. Movies (title, director, thumbnail) are stored
in the browser's localStorage under the key `my_movies`. Open `index.html` in
Chrome or Firefox to run the app.

## Changes
- **Show**: `view` button displays a movie's title and director (`showContr`, `showView`).
- **New**: `add` button opens a form to enter a new movie (`newContr`, `newView`).
- **Create**: `Create` button validates the input and saves the new movie (`createContr`).
- **Delete**: `delete` button removes a movie after confirmation (`deleteContr`).
- **Reset**: `reset` button restores the original movies (`resetContr`).
- **Router**: extended with the five new actions.
- **Tests**: `tests/checks.js` updated to the English identifiers
  (`title`, `thumbnail`, `my_movies`).