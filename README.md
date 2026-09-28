# Ryzen Moderation Bot

A Discord bot project organized around moderation, server utilities, database-backed features, interactive components, and community tooling.

## Project Structure

The repository is organized into dedicated modules for bot components and supporting systems, including:

- `cogs/` — feature and command modules
- `core/` — shared bot infrastructure
- `checks/` — command and permission checks
- `Buttons/` — interactive button components
- `games/` — game and entertainment features
- `database/` — database-related modules
- `database.py` — database access layer

The repository also contains media and font assets used by the bot's responses and generated content.

## Development

Clone the repository and inspect the current project configuration before running the bot:

```bash
git clone https://github.com/PauzeDevs/Ryzen--Moderation-Bot.git
cd Ryzen--Moderation-Bot
```

The project currently contains Python source modules and a local database layer. Use the Python version and dependency configuration expected by the source tree when deploying it.

## Data & Configuration

Runtime data such as local databases should be treated as application state. Bot tokens, API credentials, and other secrets must never be committed to the repository.

## Status

Ryzen Moderation Bot is maintained as a development project. Commands and internal modules may change as the codebase evolves.

## Maintainer

Maintained by [PauzeDevs](https://github.com/PauzeDevs).
