# Standalone Web Application

A simple Flask web application that can run independently.

## Installation

1. Install the required dependencies:
```bash
pip install -r requirements.txt
```

## Running the Application

To run the application locally:

```bash
python app.py
```

The application will start on `http://localhost:5000`

## Available Endpoints

- `GET /` - Returns "Hello World!" message
- `GET /health` - Returns health status of the application

## Configuration

The application runs on:
- Host: `0.0.0.0` (accessible from all network interfaces)
- Port: `5000`
- Debug mode: `True` (for development)

To run in production, consider setting `debug=False` and using a proper WSGI server like Gunicorn.