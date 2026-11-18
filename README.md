# FloodNav — Intelligent Flood Emergency Navigation System

**Final Year Project (FYP) | Bachelor of Computer Science**

FloodNav is an intelligent flood emergency navigation and response system designed to help citizens navigate safely during flood emergencies, identify hazardous areas, and access emergency assistance.

## Project Overview

The system aims to provide safer navigation through flood-affected areas by combining real-time hazard reporting, intelligent route planning, offline map support, and emergency response features.

## Planned Features

- Interactive maps and flood hazard visualization
- Safe route calculation using Dijkstra's and A* algorithms
- Citizen flood and road hazard reporting
- Offline maps and navigation support
- Emergency SOS and location sharing
- Phone sensor-based emergency detection
- Administrative dashboard for hazard verification and management

## Technology Stack

| Component | Technology |
|---|---|
| Backend | Python, Django |
| Database | SQL |
| Web Frontend | React, TypeScript |
| Mobile Application | React Native |
| Maps | OpenStreetMap, MapLibre |
| Routing Algorithms | Dijkstra, A* |

## Development Status

🚧 **Under Development — Initial Setup**

The project is currently in its early development phase. Features, documentation, and installation instructions will be added progressively.

## Project Team

Developed as a Final Year Project by a team of three Computer Science students.

## License

This project is intended for academic and research purposes. Licensing details will be added later.

---


## Environment Configuration

Create a `.env` file in the root directory of the Django project.

### `.env` Structure

```env
# Django Configuration
SECRET_KEY=your-django-secret-key
DEBUG=True

# PostgreSQL Database Configuration
DB_NAME=floodnav
DB_USER=postgres
DB_PASSWORD=your-database-password
DB_HOST=localhost
DB_PORT=5432
```

### Configuration Notes

- `SECRET_KEY`: Django's secret key. Generate a unique, secure value.
- `DEBUG`: Set to `True` for local development and `False` for production.
- `DB_NAME`: PostgreSQL database name.
- `DB_USER`: PostgreSQL username.
- `DB_PASSWORD`: PostgreSQL password.
- `DB_HOST`: Database server hostname.
- `DB_PORT`: PostgreSQL port (default: `5432`).

**Security:** Never commit your `.env` file to GitHub. Ensure `.env` is included in `.gitignore`. Use a `.env.example` file with placeholder values to share the required configuration.


**Note:** This README is preliminary and will be updated as development progresses.