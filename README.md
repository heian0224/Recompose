# Recompose

Go from Kubernetes to Docker Compose

`Recompose` is a tool to help users who are familiar with [Kubernetes API](http://kubernetes.io) move
to `docker-compose`. `kompose` takes all kubernetes resources and translates it into docker compose.

`Recompose` is a convenience tool to go from cloud-native environment to private deploy environment.

Transformation of the Kubernetes resources manifest to Docker Compose format may occur when you develop an application
in cloud, but deploy for old environment that doesn't have kubernetes, usually it's vendor's projects.
