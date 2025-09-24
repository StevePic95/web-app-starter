# Supabase Docker

This is a minimal Docker Compose setup for self-hosting Supabase. Follow the steps [here](https://supabase.com/docs/guides/hosting/docker) to get started.

- Supabase infrastructure comes from docker compose files copied from the supabase/supabase repo. By default, docker-compose.yml files have container versions "pinned" at a specific version. To keep this repo current, I will have to manually change version numbers in the compose files and test/refactor to keep up with any potential breaking changes.