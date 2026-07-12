# System Architecture

DietBite follows a modern three-tier architecture.

```text
React (Frontend)
        │
        ▼
FastAPI (Backend)
        │
        ▼
SQLAlchemy ORM
        │
        ▼
PostgreSQL Database
```

## Components

### React
- User interface
- Authentication pages
- Dashboard
- Meal planner

### FastAPI
- REST API
- Authentication
- Business logic

### SQLAlchemy
- Database ORM
- Model relationships
- Query management

### PostgreSQL
- Stores users
- Food database
- Patients
- Meal plans
