Serenity Palworld Server
========================

Contains the configuration for the palworld server being run.

## Usage

1. Copy `.env.example` into `.env` and configure the values.
2. Edit game settings in `game-settings.env`.
3. Create the data directory.
   ```shell
   mkdir <data_dir>
   ```
4. Start the services.
   ```shell
   docker compose up -d
   ```