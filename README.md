<h2 align="center">
  Won Games (DATABASE)
</h2>

<p align="center">
  <img alt="technology" src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white">

  <img alt="technology" src="https://img.shields.io/badge/Docker-2CA5E0?style=for-the-badge&logo=docker&logoColor=white">
</p>

<br>

### :writing_hand: About this project
This is the database repository of the Won Games platform, Won Games is an online game marketplace, where you can buy and download your games.

### :cyclone: Run container with database backup
You must have docker and also docker-compose installed on your machine.

```bash
# Clone this repository
$ https://github.com/wallisonmoura/won-games-database.git

# Access the project folder
$ cd won-games-database

# Get docker database container 
$ docker-compose pull

# Run database container
$ docker-compose up -d

# Verify container status
$ docker ps -a
```
