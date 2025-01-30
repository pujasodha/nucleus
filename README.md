# README

## This is a basic ruby app with docker that can be used as a starting point for any new app made

### Steps 
1. Navigate to `Dockerfile-dev` and specify Ruby Version
2. Navigate to `Gemfile` to specify rails version
3. Run `docker compose up --build` first time at least to get it started
   - `docker compose up` from there
4. Run `docker-compose run --service-ports web bash` to get into the bash
