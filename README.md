MANTENBOT
## Table of Contents
- [Technology Summanry](#technology-summary)
- [Installation](#installation)

----------------------
### Technology Summary
| Library | Version |
| -------- | -------- |
| Ruby     | 3.2.0     |
| Rails     | 7.1.3.2    |
| Postgres |14.11|
| Bootstrap | not built |
| Redis     | not built     |
----------------------
### Installation

- Install [OrbStack](https://orbstack.dev/download) for using Docker (Note that you may need to install Homebrew on your local device first if you want to install OrbStack using terminal)

- Create a .env file and add below values (contact me for the RAILS_MASTER_KEY value)
```
RAILS_ENV=production
POSTGRES_HOST=db
POSTGRES_DB=mantenbotdb_production
POSTGRES_USER=
POSTGRES_PASSWORD=
RAILS_MASTER_KEY=
```
- Compose build and compose up (due to access permission, you may need to run this command with sudo)
```
docker-compose build && docker-compose up
```
