# bsuir-assistant
A repository for launching up the BBSUIR RAG Assistant

## Setting up

To run the bsuir-assistant you need:
* The __qdrant_data__ directory which was created as Volume for Docker

* A __.env__ file which contains the environment variables for the serivces. Refer to __.env.example__

* Registered __telegram__ bot and __token__ for it

* An [OpenRouter](https://openrouter.ai/) _token_ for your model

* A set up Docker compose, working example of which is provided in this repository

## Running

You need Docker to run the assistant. After setting up is complete, you can run the assistant by writing in terminal in the root folder:

```bash
docker compose up
``` 

## System Requirements

* Fast internet connection

* Docker-compose

* [OpenRouter](https://openrouter.ai/) account

* At least 7GB free storage space

* Natural intelligence