# DISCIPLINE V2 DEPLOY

This build combines:
- verified backend from `discipline_fixed_verified`
- latest futuristic frontend from `discipline_futuristic_v6`
- 37 API routes
- client/trainer roles
- slots/bookings
- program/training days
- nutrition
- water/habits
- measurements/photos/reports
- trainer controls
- Telegram Mini App initData validation

## Railway variables

BOT_TOKEN=<NEW TOKEN>
TRAINER_TG_ID=8144320404
MINIAPP_URL=https://<your-railway-domain>
DB_PATH=/data/discipline.db
PORT=8000

For persistent SQLite data, attach a Railway Volume mounted at `/data`.

## Start

`python main.py`

Health:
`/health`

Do not commit `.env` or a real Telegram token.
