Helm chart for Sonarqube 7.8 is not available anymore, I had to switch for v8.5.1
This version of Sonarqube doesn't support MySQL, so I switched to PostgreSQL
No need for separate Nginx ingress installation, as Minikube has addon which is enabled by the script

Clone the repo
cd into it

To run stuff you will need installed:

1. Docker engine
2. Kubectl
3. Minikube
4. Podman
5. Helm
6. Terraform

OR

you can run script risky.sh which maybe will install everything successfully (risky, as it says)


Make sure your machine is not 1Gb RAM (should be at least 4, but I would advice 8)

When everything is ready run justrunthis.sh script

