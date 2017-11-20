# Traefik with Docker

## About
I used this to learn Traefik wtih SSL and the Docker provider.  Included is a Jupyterlab notebook.

To run this, you'll need to add in .env files with the environment variables provided in the docker compose files.  You'll also need a .htpasswd file with your salted user/password for the basic http auth of the monitoring dashboard.

This is an old configuration and Traefik has updated it's dashboard/API so this won't work with the newest release.
