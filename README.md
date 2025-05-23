# BSUIR RAG Assistant
A repository for launching up the BSUIR RAG Assistant

## Setting up

To run the bsuir-assistant you need:
* The __qdrant_data__ directory which was created as Volume for Docker

* A __.env__ file which contains the environment variables for the serivces. Refer to __.env.example__

* Registered __telegram__ bot and __token__ for it

* An [OpenRouter](https://openrouter.ai/) __token__ for your model

* A set up Docker compose, working example of which is provided in this repository

## Running

You need Docker to run the assistant. After setting up is complete, you can run the assistant by writing in terminal in the root folder:

```bash
docker compose up
``` 

## Requirements

* Fast internet connection

* Docker-compose

* [OpenRouter](https://openrouter.ai/) account

* Telegram bot

* At least 8GB free storage space

* Natural intelligence

## About Qdrant Data Folder

If you want to know how to build the proper data folder for this assistant, please refer to [Bsuir Assistant Data Module](https://github.com/semantic-hallucinations/bsuir-helper-data)

## Sources
This repository uses or refers to following services:

* [Answer Pipeline](https://github.com/semantic-hallucinations/answer_pipeline) by [Aliteya](https://github.com/Aliteya)

* [Telegram Bot](https://github.com/semantic-hallucinations/bsuir-helper-bot) by [Hohich](https://github.com/Hohichh)

* [Bsuir Assistant Data Module](https://github.com/semantic-hallucinations/bsuir-helper-data) by [Semantic Hallucinations](https://github.com/semantic-hallucinations)