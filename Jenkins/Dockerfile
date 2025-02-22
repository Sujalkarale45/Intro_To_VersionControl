# Use Jenkins official LTS image
FROM jenkins/jenkins:lts

# Switch to root user
USER root

# Update and install Python3 and virtual environment
RUN apt-get update && apt-get install -y python3 python3-venv

# Switch back to Jenkins user
USER jenkins
