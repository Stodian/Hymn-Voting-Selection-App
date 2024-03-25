# Hymn Voting and Selection App

The Hymn Voting and Selection App is an iOS application designed to streamline the process of selecting hymns for group singing sessions, particularly within the Christadelphian community. This app allows individuals to view a list of hymns, vote on their favorites, and suggest new hymns. Additionally, it provides functionality for aggregating user preferences from multiple devices into a master list, which can then be used to generate a final list of hymns for singing sessions.

## Features

- **View Hymn List**: Browse a list of hymns with their first lines.
- **Vote on Favorite Hymns**: Vote on favorite hymns to indicate preferences.
- **Visual Representation of Favorites**: Visual representation of favorite hymns in ranking order for each user.
- **Generate Presidents Hymn List**: Generate a master list of hymns based on aggregated user preferences.
- **Filter by Category/Theme**: Filter hymns by category or theme for specific occasions (e.g., breaking of bread, Death of Christ, Evening).
- **Lock Screen Widget**: Show a widget on the lock screen displaying the user's current favorite hymns.

## Project Structure

- **hymn-voting-app/**
  - **public/**: Contains public assets such as HTML, CSS, and client-side JavaScript.
    - index.html: Main HTML file.
    - styles.css: CSS stylesheets.
  - **src/**: Backend code (Node.js/Express).
    - index.js: Main server file.
    - database.js: Database setup.
    - hymnModel.js: Database model for hymns.
    - hymnController.js: Route handlers for hymns.
    - users.js: Route handlers for user authentication.
  - **database/**: Contains database schema and setup scripts.
    - schema.sql: Database schema definition.
    - seeds.sql: Sample data for initialization.
- README.md: Project overview, setup instructions, and usage guide.
- LICENSE: License information.
