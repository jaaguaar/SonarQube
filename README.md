# SonarQube Docker Setup

This repository contains a Docker Compose configuration for setting up a SonarQube instance along with its dependencies, including PostgreSQL and NGINX. SonarQube is an open-source platform for continuous inspection of code quality, which helps developers manage code quality and security vulnerabilities.

https://docs.sonarsource.com/sonarqube/latest/devops-platform-integration/github-integration/setting-up-at-global-level/setting-up-github-app/


docker run --rm -v /opt/nginx/certbot/www:/var/www/certbot:rw -v /opt/nginx/logs:/var/log/letsencrypt:rw -v /opt/nginx/certbot/conf:/etc/letsencrypt:rw certbot/certbot certonly --webroot --webroot-path /var/www/certbot/ -d <YOUR_DOMAIN> --email <YOUR_EMAIL> --non-interactive --agree-tos
