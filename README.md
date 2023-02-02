# About

Hi this is an example Docker Compose config that would allow you to run a Gitlab instance on a VPS or a VDS or any other standalone server of yours. Please pay attention to optimization config values. You can remove them but if you plan to use Gitlab for a small team then I'd suggest to keep them.

Assuming that you have Docker installed. Steps to run your Gitlab:

1. Copy `docker-compose.yml` config.
2. Replace all values that contain the word `your` in your `docker-compose.yml`.
3. Create a `gitlab` folder at the same folder as `docker-compose.yml`.
4. Run `docker compose up -d`
