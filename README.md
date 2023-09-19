# NyPv2.0Architecture

# Requirement and problem
* While (Cosmos DB) is a distributed, multi-model database service that is easier to scale, the costs and lack of competence to maintain this model are two of the main drawbacks
* The backend application is a .NET app that has a soultion containing multiple services and even a SPA frontend build with Angular but running on IIS.
* Cyclic dependencies between the services

# The Solution
The solution consist of dividing the problem into smaller problem
* Setup a SQL Server database
* Setup a .NET6 app with EFCore
* Separating the FE app into another repository
* Creating a dockerfile for backend and frontend
* Using kubernetes to run those services 
