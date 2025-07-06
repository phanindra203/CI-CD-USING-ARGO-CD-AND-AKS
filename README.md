# CI-CD-USING-ARGO-CD-AND-AKS
I built and deployed a voting application using Kubernetes (K8s) clusters and Argo CD for continuous deployment. The application, featuring a "Ford vs Ferrari" voting interface, leverages a container registry to manage and push images. I successfully addressed challenges such as resolving an ImagePullBackOff error in Argo CD by configuring image pull secrets, ensuring the pod transitioned from an unhealthy to a healthy state. This project honed my skills in K8s cluster management, container registry operations, and Argo CD workflows. Check out the screenshots and GitHub repo for more details! [Link to GitHub]


GitHub Repository Description
This repository contains the source code and configuration files for a voting application built and deployed using Kubernetes (K8s) clusters and Argo CD. The application allows users to vote between Ford and Ferrari, showcasing a simple yet effective use case for containerized deployments.

Key Components:

Kubernetes Cluster: Managed and orchestrated the application deployment.
Container Registry: Images were built and pushed to a container registry.
Argo CD: Utilized for continuous deployment, with successful resolution of an ImagePullBackOff error using image pull secrets.
Features: A user-friendly voting interface for Ford vs Ferrari.
Challenges Overcome:

Resolved pod health issues by configuring image pull secrets, transitioning the pod from unhealthy to healthy status.
Explore the code, manifests, and deployment configurations to see the implementation in action. Contributions and feedback are welcome!

[xaiArtifact artifact_id="a1b2c3d4-e5f6-4g7h-8i9j-0k1l2m3n4o5p" title="README.md" contentType="text/markdown">

Voting Application
Overview
This repository contains the source code and configuration files for a voting application built and deployed using Kubernetes (K8s) clusters and Argo CD. The application allows users to vote between Ford and Ferrari, showcasing a simple yet effective use case for containerized deployments.

Key Components
Kubernetes Cluster: Managed and orchestrated the application deployment.
Container Registry: Images were built and pushed to a container registry.
Argo CD: Utilized for continuous deployment, with successful resolution of an ImagePullBackOff error using image pull secrets.
Features: A user-friendly voting interface for Ford vs Ferrari.
Challenges Overcome
Resolved pod health issues by configuring image pull secrets, transitioning the pod from unhealthy to healthy status.
Usage
