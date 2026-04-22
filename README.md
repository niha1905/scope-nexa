# Scope Nexa

A Flask-based web application deployed on Vercel. Scope Nexa provides a modern, responsive web experience with server-side rendering and dynamic content management.

## About

Scope Nexa is a web application built with Flask, featuring a clean and modern user interface. It is deployed on Vercel for reliable and scalable hosting.

## Features

- **Flask Backend** - Python-based server with routing and templating
- **Vercel Deployment** - Fast, serverless deployment
- **Static Assets** - Optimized static file serving
- **Responsive Design** - Mobile-friendly user interface
- **Environment Configuration** - Flexible configuration with .env files

## Tech Stack

- **Backend**: Flask (Python)
- **Frontend**: HTML, CSS, JavaScript
- **Deployment**: Vercel
- **Package Manager**: pip

## Project Structure

```
.
├── static/              # Static assets (CSS, JS, images)
├── templates/           # Jinja2 HTML templates
├── app.py               # Main Flask application
├── requirements.txt     # Python dependencies
├── vercel.json          # Vercel deployment configuration
└── .env.example         # Environment variable template
```

## Getting Started

### Prerequisites

- Python 3.8+
- pip

### Installation

```bash
# Clone the repository
git clone https://github.com/niha1905/scope-nexa.git
cd scope-nexa

# Install dependencies
pip install -r requirements.txt

# Copy environment variables
cp .env.example .env
```

### Running Locally

```bash
python app.py
```

## Deployment

This project is deployed on Vercel. Push changes to the master branch to trigger automatic deployment.

## License

MIT License
