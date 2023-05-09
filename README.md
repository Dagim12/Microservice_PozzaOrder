## Microservice in .NET - Simple Pizza Order App

Microservice applications are composed of small, independently versioned, and scalable customer-focused services that communicate with each other over standard protocols with well-defined interfaces. Each microservice typically encapsulates simple business logic, which you can scale out or in, test, deploy, and manage independently.  Smaller teams develop a microservice based on a customer scenario and use any technologies that they want to use. This module will teach you how to build your first microservice with .NET.

## To Deploy backend to Kubernetes run 
kubectl apply -f backend-deploy.yml

## To Deploy frontend to Kubernetes run 
kubectl apply -f frontend-deploy.yml

## This will give the status of the containers
kubectl get pods 

## The following command to scales the backend microservice to five instances.
kubectl scale --replicas=5 deployment/pizzabackend