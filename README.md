# Recommendation-Systems-using-GNN

Movie Recommendation System Using Graph Neural Networks (GNN)

This repository presents a personalized movie recommendation system developed using Graph Neural Networks (GNN). The system leverages the MovieLens 25M dataset to model user-movie interactions as a bipartite graph, utilizing a two-layer GraphSAGE architecture to learn user and movie embeddings through message passing.

Features:

Personalized Recommendations: High-quality, personalized movie recommendations based on user preferences.

Interactive Exploration: Users can interactively explore recommendations using genre, year, and similarity score filters.

Visualization: Includes embeddings visualization, recommendation graphs, and user-movie interaction subgraphs for interpretability.

Performance:

Mean Squared Error (MSE): 0.0406

NDCG@K: 0.9857

Technologies:

PyTorch and PyTorch Geometric

GraphSAGE GNN Model

NetworkX for graph visualization

Demonstration Video

Watch the detailed 15-minute walkthrough here on YouTube: https://youtu.be/siK5MfFOr-w

Setup Instructions

Detailed installation and usage instructions can be found in the notebook provided in the repository.

Dataset

MovieLens 25M Dataset: https://grouplens.org/datasets/movielens/25m/
