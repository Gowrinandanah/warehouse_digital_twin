# Digital Twin-Based Warehouse Planning and Simulation System

A software-based Digital Twin system for warehouse layout planning and simulation.

## About

This project provides a virtual 2D representation of a warehouse that allows users to:

- Create warehouse layouts
- Place and configure racks and work areas
- Assign products to storage locations
- Define warehouse orders/workloads
- Simulate worker movement
- Calculate warehouse performance metrics
- Compare different warehouse layouts

The main goal is to answer:

> "If I arrange my warehouse this way, how will it perform?"

## Tech Stack

### Frontend
- React
- TypeScript
- React Konva
- Recharts
- Tailwind CSS

### Backend
- Python
- FastAPI
- SQLAlchemy
- SQLite

### Simulation
- Grid-based warehouse model
- A* pathfinding
- Worker route simulation
- Performance metrics

## Main Metrics

The system will evaluate layouts using:

- Total Travel Distance
- Average Travel Distance per Order
- Estimated Picking Time
- Space Utilization

## Project Structure

```text
warehouse-digital-twin/
│
├── frontend/       # React frontend
│
├── backend/        # FastAPI backend
│
└── README.md
