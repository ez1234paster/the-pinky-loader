# Discord API Bot

This is a Discord bot with an integrated REST API for sessions and player bans.

## Commands

- `!listsessions` → List active sessions
- `!listbans` → List banned players
- `!ban <player> [reason]` → Ban a player
- `!unban <player>` → Unban a player
- `!checkban <player>` → Check if a player is banned

## API Endpoints

- POST `/create-session` → `{ "game_id": "...", "player_name": "..." }`
- POST `/ban-player` → `{ "player_name": "...", "reason": "..." }`
- POST `/unban-player` → `{ "player_name": "..." }`
- GET `/check-ban/:player_name`
- GET `/list-bans`
- GET `/list-sessions`

## Deployment

Deploy on [Render](https://render.com):

1. Connect GitHub repo
2. Node environment
3. Build Command: `npm install`
4. Start Command: `npm start`
5. Add Environment Variable `DISCORD_BOT_TOKEN`
