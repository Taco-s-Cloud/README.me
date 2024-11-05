# README.me
Repository holding project README.

**Database Access**
- Install Google Cloud CLI by following the instructions here: https://cloud.google.com/sdk/docs/install
- In GCP console, go to IAM & ADMIN -> Service Accounts, click on a service account (or make a new one)
- Add a key or select a new one. Save the {id}.json file with the key in a folder called 'Credentials' in the project folder in your local machine.
- In the project docker file in this directory, edit all the GOOGLE_APPLICATION_CREDENTIALS lines to GOOGLE_APPLICATION_CREDENTIALS=/app/credentials/{id}.json

**Codebase Setup**
- Clone all repos in the project inside on folder. You will likely require a Githu Personal Access Token if you don't have one already.
- Download and install docker, https://www.docker.com/products/docker-desktop/
- Move the docker .yml file in this repo to the project directory holding all the repos.
- Go to the GCP database and turn it on.
- Run the following in terminal, from the folder holding all the repos: docker compose up --build
- UI should be available by going to http://localhost:80
