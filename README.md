# VotingApp-Using-Kubernetes

This repository contains the Kubernetes manifests and configurations for deploying a Voting Application using MongoDB as the database. The application is set up on a Kubernetes cluster and includes an API service and a database service.

<h2>Overview</h2>
The Voting Application allows users to vote on various topics and stores their votes in a MongoDB database. The application is designed to be scalable and easily deployable on a Kubernetes cluster.

<h2>Components</h2>
API Service: Manages user interactions and voting logic.
MongoDB Database Service: Stores votes and user data.

<h2>Setup Instructions</h2>
Ensure you have a Kubernetes cluster set up and configured.
Deploy the Kubernetes manifests provided in this repository to set up the application and MongoDB.

<h2>Accessing the Application</h2>
Once deployed, the application can be accessed via the external IP or service endpoint provided by the Kubernetes cluster. MongoDB will be running as a service within the cluster.

<h2>Troubleshooting</h2>
For troubleshooting any issues related to deployment or application runtime, check the logs of the Kubernetes pods and services. Ensure that MongoDB is running correctly and is accessible to the API service.

License
This project is licensed under the MIT License.
