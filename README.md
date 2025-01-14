# Traffic-tracker

# Traffic Time Monitor

A Flask-based web application that monitors and records travel time between two locations in Bangalore using Google Maps API. The application tracks traffic patterns during specific time windows and provides historical data visualization.

## Features

- Real-time traffic monitoring using Google Maps API
- Automated data collection at configurable intervals
- Timezone-aware scheduling (IST - Indian Standard Time)
- PostgreSQL database for persistent storage
- RESTful API endpoints for data retrieval
- Web interface for data visualization

## Prerequisites

- Python 3.11 or higher
- PostgreSQL database
- Google Maps API key
- Heroku account (for deployment)

## Environment Variables

The application requires the following environment variables:

```bash
DATABASE_URL=your_postgresql_database_url
GOOGLE_MAPS_API_KEY=your_google_maps_api_key
