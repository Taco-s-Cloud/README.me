# README.me
Repository holding project README.

**Database Access**
- Install Google Cloud CLI by following the instructions here: https://cloud.google.com/sdk/docs/install
- In GCP console, go to IAM & ADMIN -> Service Accounts, click on a service account (or make a new one)
- Add a key or select a new one. Save the {project_id}.json file with the key in a folder called 'Credentials' in the project folder in your local machine.

**Codebase Setup**
- Clone all repos in the project inside on folder.
- Run the following in terminal, from the folder holding all the repos: docker compose up --build
- UI should be available by going to http://localhost:80
