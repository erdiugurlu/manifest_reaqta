# ReaQta Platform Manifest

This repository contains namespace definition in the cluster and manifest files of ReaQta Hello World Application. The configuration is pretty simple, only container port number was updated since my application listens to 8080.... 

Once the configurations are pushed, **ArgoCD** pulls them and implement the changes on the EKS cluster. 