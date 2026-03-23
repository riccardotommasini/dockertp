# Wordsmith Docker Exercises

This repository contains a small multi-service application used to explore
Docker, Docker Compose, and Docker Model Runner through hands-on exercises.

It was originally developped by Jerome Petazzoni [original](https://github.com/jpetazzo/wordsmith)

The project currently includes:

- `web`: the original Go frontend
- `web2`: a Node.js evolution of the frontend with newer UI interactions
- `words`: a Java API serving generated words
- `db`: a PostgreSQL database storing the word lists and generated stories
- `narrative`: a Python API that calls `words` and a model server to generate short stories

The repository is designed as a learning playground for:

- writing Dockerfiles
- connecting services with Docker Compose
- exposing ports and volumes
- integrating Docker Model Runner into an application stack
- extending the application with new services

Documentation:

- [English guide](README.en.md)
- [Guide en français](README.fr.md)
