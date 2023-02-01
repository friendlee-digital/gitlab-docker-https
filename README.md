# About

Hi this is an example config that would allow you to run your Gitlab instance on a VPS or VDS or any other standalone server of yours.

Assuming that you have Docker installed. Steps to run your Gitlab:

1. Copy `docker-compose.yml` config.
2. Replace all values that contain the word `your` in your `docker-compose.yml`.
3. Create a `gitlab` folder at the same folder as `docker-compose.yml`.
4. Run `docker compose up -d`
