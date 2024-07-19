# Fashion AId
Discover your next favorite clothing piece with just a click! Upload a picture and let FashionAId instantly recommend clothing that matches your style and preferences.

With FashionAId users can upload a product image or describe a product in text. The system analyzes these inputs and returns the closest matching items from our inditex database. Each recommendation includes the description of the product and the similarity score, based on this description.

## About the Project
The project was developed during the [HackUPC](h[ttps://www.inditexhackathon.com/](https://hackupc.com/)). The challenge was proposed by the company Inditex, where participants were given a large dataset of images and were tasked with building an algorithm to calculate similarity scores. 

Check out our blog post on devpost: https://devpost.com/software/inditex-fashionaid

## Architecture
Our system's backbone is a Python-based backend. We leverage a RAG (Retrieval Augmented Generation) Architecture by Product Fashion Images with the tiny Llava-1.5b model into high dimensional vector embeddings and saved them to a vector database to get efficient similarity search via cosine similarity. Our results are showcased through a easy-to-use React-developed frontend, offering users an intuitive and engaging interface.

## Technologies Used
- Python
- Flask
- React
- chromaDB
- llava
