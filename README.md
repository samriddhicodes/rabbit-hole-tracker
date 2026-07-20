# Rabbit Hole Tracker

Rabbit Hole Tracker is a lightweight, interactive web application designed to map, organize, and summarize your Wikipedia research journeys. By automatically generating dynamic knowledge graphs as you explore connected topics, the application turns unstructured reading sessions into visual networks, structured timelines, and exportable notes.

## Features

- **Interactive Graph Visualizations**: Built with Cytoscape.js to render articles as visual nodes and link references as directional edges.
- **Topic-Based Category Clustering**: Color-codes articles based on primary Wikipedia category classifications with an auto-updating visual legend.
- **Live Search Autocomplete**: Integrated with the Wikipedia OpenSearch API to provide real-time article suggestions and prevent typos.
- **Unvisited Link Recommendations**: Displays interactive "ghost nodes" for adjacent unvisited Wikipedia articles to facilitate exploratory reading.
- **Exploration Timeline**: Generates a sequential log of read articles alongside custom notes and source summaries.
- **Session Statistics**: Tracks key metrics including total articles read, unique topics covered, and total connections made.
- **Data Export Options**: Export your rabbit hole sessions into clean Markdown recaps or high-resolution PNG graph images.
- **Local Persistence**: Automatically saves session state to LocalStorage to preserve reading progress across browser refreshes.

## Tech Stack

- **HTML5 / CSS3**: Responsive UI layout with floating controls and side-panel drawers.
- **JavaScript (ES6+)**: Asynchronous API fetching and local state management.
- **Cytoscape.js**: Graph theory library used for visual network rendering and canvas manipulation.
- **Wikipedia REST API**: Used for fetching article extracts, category metadata, and page link relations.
- **Vercel Web Analytics**: Integrated script tracking for basic session insights.

## Project Structure

```text
├── index.html       # Single-page application containing styles, markup, and logic
└── README.md        # Project documentation