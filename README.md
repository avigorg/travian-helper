# Travian Companion

A full-stack application to support and enhance the Travian gaming experience.  
This project includes:

- 🌐 **Frontend**: Angular 19 for a dynamic and modern UI.
- 🔧 **Backend**: NestJS REST API to manage data and business logic.
- 🗄️ **Database**: MySQL for persistent storage.
- 🐳 **Dockerized**: Easily deployable and scalable architecture using Docker & Docker Compose.

## Goals

- Track resources, villages, armies, and strategic plans.
- Provide custom tools and dashboards for Travian players.
- Serve as an extensible base for future features like notifications, map analysis, etc.

## Technologies

| Layer      | Tech          |
|------------|---------------|
| Frontend   | Angular       |
| Backend    | NestJS        |
| Database   | MySQL         |
| DevOps     | Docker, Docker Compose |

---

## Development Setup

```bash
# Clone the project
git clone https://github.com/your-username/travian-companion.git
cd travian-companion

# Start all services
docker-compose up --build
