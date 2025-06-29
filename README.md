# RightSpot - Intelligent Business Location Advisor

An AI-powered platform that helps businesses find the perfect location using machine learning analysis of foot traffic, demographics, competition, and market data.

## 🚀 Quick Start with GitHub Codespaces

1. Click the green "Code" button
2. Select "Codespaces" tab
3. Click "Create codespace on main"
4. Wait for the environment to build (2-3 minutes)
5. Run the setup commands below

## 📋 Setup Commands (Run in Codespaces Terminal)

```bash
# 1. Copy environment file
cp .env.example .env

# 2. Start database
docker-compose up -d

# 3. Run Django migrations
cd backend
python manage.py migrate

# 4. Create superuser
python manage.py createsuperuser

# 5. Start Django server
python manage.py runserver 0.0.0.0:8000
```
## 🏗️ Project Structure

- backend/ - Django REST API
- frontend/ - React.js application
- ml_models/ - Machine learning pipeline
- data/ - Training datasets
- docs/ - Documentation

## 🔧 Development Workflow

- Backend runs on port 8000
- Frontend runs on port 3000
- PostgreSQL on port 5432
- All ports auto-forwarded in Codespaces

## 📊 Features

- 🗺️ Interactive location analysis
- 🤖 ML-powered location scoring
- 📈 Competitor analysis
- 👥 Demographic insights
- 💰 Free API integration (OpenStreetMap, Census data)

## 🛠️ Tech Stack

Backend: Django, Django REST Framework
Frontend: React.js, Leaflet Maps
Database: PostgreSQL
ML: scikit-learn, pandas
APIs: OpenStreetMap, Census API, Foursquare
