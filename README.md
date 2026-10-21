# Enterprise Carbon Footprint Tracker & AI Advisor

A web-based sustainability management platform that helps enterprises monitor, analyze, and reduce their carbon footprint using Python-based analytics and AI-generated sustainability recommendations.

---

## Project Overview

The system allows enterprise administrators to record environmental activities, calculate estimated CO₂ emissions, visualize carbon footprint statistics, and receive AI-powered recommendations for reducing emissions.

This project is being developed as a Capstone Project for the Python Preparatory Course at FH Dortmund.

---

## Features

- Enterprise authentication and profile management
- Carbon activity management
- CO₂ emission calculation using configurable emission factors
- Interactive analytics dashboard
- AI-powered sustainability recommendations
- Enterprise-specific data storage
- Activity history and reporting

---

## Carbon Activity Categories

The system currently supports the following activity categories:

- Electricity
- Natural Gas & Heating Fuel
- Petrol & Diesel
- Waste Management

---

## Technology Stack

### Frontend

- React
- Chart.js

### Backend

- Python
- FastAPI

### Database

- MongoDB

### AI Integration

- OpenAI API

### Other

- JSON (Emission Factors)
- Git & GitHub

---

## Project Structure

```
enterprise-carbon-footprint-tracker/

│
├── frontend/
├── backend/
│   ├── app/
│   ├── data/
│   │   └── emission_factors.json
│   └── requirements.txt
│
├── docs/
├── database/
├── assets/
│
└── README.md
```

---

## System Workflow

```
Enterprise Admin

↓

Login

↓

Enter Carbon Activity

↓

Python Backend

↓

Validate Input

↓

Load Emission Factors

↓

Calculate CO₂ Emissions

↓

Store Data (MongoDB)

↓

Generate Analytics

↓

OpenAI API

↓

AI Sustainability Recommendations

↓

Dashboard
```

---

## Team Members

Usama Rasheed
Xiangping Kong
Oscar Daniel De la Cruz Jara

---

## Repository Workflow

- `main` → Stable production branch
- `develop` → Integration branch
- `feature/*` → Feature development branches

Each new feature should be developed in its own feature branch and merged through a Pull Request.

---

## Project Status

🚧 Currently under development.

---

## License

This project is developed for academic purposes as part of the FH Dortmund Python Preparatory Course.
