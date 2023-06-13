[![SonarCloud](https://sonarcloud.io/images/project_badges/sonarcloud-black.svg)](https://sonarcloud.io/summary/new_code?id=Supriyo-Roy_project-2-devsecops)


DevSecOps Project

Tools Used: GitHub Actions, SonarCloud (SAST), Snyk (SCA), OSWAP ZAP (DAST), Argo CD, Docker, Minikube (Kubernetes Locally)

Security is an integral part of an workflow. It's always recommended to integrate the shift to left security pattern in your pipelines. Better to find security vulnerabilty in the eary stages of SDLC rather than in Production.

Created this project to impletement the Security in our DevOps pipeline.

Step 1: Developer pushes code to GitHub

Step 2: Workflow gets triggered due to push action

Step 3: SAST is performed with SonarCloud

Step 4: SCA is done with Snyk

Step 5: Docker image is built and pushed to DockerHub

Step 6: Application is deployed to Kubernetes Cluster

Step 7: DAST scan is performed on the application URL with OSWAP ZAP

Step 8: You can find the reports  of SCA scan in Code Scanning tab, and an artifact is created after a ZAP scan


