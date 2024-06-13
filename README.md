# Movie_Recommendation_RAG_System_With_OpenAI_Embeddings

This project demonstrates a movie recommendation system that uses a combination of natural language processing and vector search to provide users with movie recommendations based on their queries. The dataset, consisting of embedded movie plots, is utilized to perform similarity searches and return relevant movie recommendations.

## Overview

The project leverages the embedded_movies dataset to provide movie recommendations based on plot similarity. The embeddings for the movie plots are generated using OpenAI's embedding API, and MongoDB is used to store and search the embeddings efficiently.

## Dataset

The dataset used is the embedded_movies dataset available on Hugging Face:

Dataset URL: https://huggingface.co/datasets/AIatMongoDB/embedded_movies

## Setup

Clone the repository.
Install the required libraries.
Set up the necessary API keys and MongoDB connection strings.

## Usage

Loading the Dataset
Load the dataset using the Hugging Face datasets library.

## Generating Embeddings

Generate embeddings for the movie plots using OpenAI's API.

## Storing Data in MongoDB

Store the dataset with embeddings in MongoDB.

## Vector Search

Perform a vector search in the MongoDB collection based on the user query.

## Handling User Queries

Handle user queries to provide movie recommendations.

## Requirements

pandas

datasets

openai

pymongo

## Acknowledgements

The dataset used in this project is provided by AIatMongoDB and is available on Hugging Face.
Embeddings are generated using OpenAI's API.
MongoDB is used for efficient storage and retrieval of movie plot embeddings.
