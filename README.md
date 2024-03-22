# Hymn Voting and Selection App

The Hymn Voting and Selection App is an iOS application designed to streamline the process of selecting hymns for group singing sessions, particularly within the Christadelphian community. This app allows individuals to view a list of hymns, vote on their favorites, and suggest new hymns. Additionally, it provides functionality for aggregating user preferences from multiple devices into a master list, which can then be used to generate a final list of hymns for singing sessions.

## Features

- **View Hymn List**: Browse a list of hymns with their first lines.
- **Vote on Favorite Hymns**: Vote on favorite hymns to indicate preferences.
- **Visual Representation of Favorites**: Visual representation of favorite hymns in ranking order for each user.
- **Generate Master Hymn List**: Generate a master list of hymns based on aggregated user preferences.
- **Filter by Category/Theme**: Filter hymns by category or theme for specific occasions (e.g., breaking of bread, Death of Christ, Evening).
- **Lock Screen Widget**: Show a widget on the lock screen displaying the user's current favorite hymns.


## Repository Structure


- **hymn-voting-app/**
  - **frontend/**: Contains the frontend code written in iOS Swift.
    - `MainView.swift`: Main view displaying hymns and voting options.
    - `HymnTableViewCell.swift`: Table view cell for displaying hymn information.
    - `HymnDetailViewController.swift`: View controller for displaying detailed information about a hymn.
    - `...`: Other view controllers and UI components.
  - **backend/**: Contains the backend code, possibly written in Node.js/Express or another backend framework.
    - `server.js`: Express server setup.
    - `routes/`: Route handlers.
    - `controllers/`: Controller logic.
    - `models/`: Database models.
    - `config/`: Configuration files.
  - **database/**: Contains database schema and setup scripts.
    - `schema.sql`: Database schema definition.
    - `seeds.sql`: Sample data for initialization.
  - `README.md`: Project overview, setup instructions, and usage guide.
  - `LICENSE`: License information.




