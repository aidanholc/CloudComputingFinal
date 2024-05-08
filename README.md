# Microservices & Cloud Computing Final Project
### Movie Recommender

This repo contains a web app that gives movie recommendations. The typical flow is creating an account/logging in, rating movies, and getting recommendations based on all movies your account has rated.

## Installation

Download the repository. Extracty myRepo.zip (there is a pickle file that was larger than the allowed size on github so it had to be zipped).

Run
docker-compose build
docker-compose up -d

connect to app on 127.0.0.1:5000

Notes:
* This assumes docker-compose version 2.24.6
* Make sure ports 5000-5003 are open 
