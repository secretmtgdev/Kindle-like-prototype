# Word Search
## Objective
Emulates a standard word search functionality of a document with highlighting. This is a small project that leverages the RESTful architecture for uploading and reading files.

## Tech stack
- Frontend
    - React
        - Like the flexibility of the library over a framework
        - Enjoy the rich features of the virtual DOM
    - Axios
        - Provides progress tracking that fetch doesn't
- Backend
    - Python
        - Easy language to pick up
        - Using psycog2 to connect to postgres
    - Postgres
        - Flexible data types

## How to run
- Client `npm start`
- Server `flask --app PyAPI.py run`

## Q & A
- What can this project do?
    - Read files from blob storage
    - Upload files to the database & blob storage
- Will this project be expanded on?
    - Most likely yes but it is more of a sandbox to try things out for a bigger project