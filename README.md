### Run server
1. Create virtual environment, install requirements
2. Rename `.env-example` to `.env` and change environmentы with yours
3. Run `python src/main.py`

### Migrations
1. In root directory run
`alembic revision --autogenerate -m "Message"`
2. Apply changes
`alembic upgrade head`
