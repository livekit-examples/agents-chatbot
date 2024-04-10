## Run the agent

1. `cd server`
2. `cp .env.example .env`
3. populate real values in `.env`
4. `python -m venv .venv`
5. `pip install -r requirements.txt`
6. `python agent.py start`

## Run the NextJS app

1. `cd client`
2. `cp .env.example .env.local`
3. populate real values in `.env.local`
4. `pnpm i`
5. `pnpm dev`
6. navigate to `localhost:3000`
