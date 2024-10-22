### Run server
1. Create virtual environment, install requirements
2. Run src/main.py

### Migrations
In root directory run
`alembic revision --autogenerate -m "Message"`
Apply changes
`alembic upgrade head`