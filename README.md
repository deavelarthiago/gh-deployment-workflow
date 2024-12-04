##################################################################################################

GitHub Deployment Workflow

##################################################################################################

## Description ##

This project demonstrates how to set up a GitHub Actions workflow to deploy a static website to GitHub Pages. It detects changes to the `index.html` file and automatically publishes them.
This project was created for `Roadmaps.sh`.
https://roadmap.sh/projects/github-actions-deployment-workflow

## Features ##

- Automated deployment to GitHub Pages using GitHub Actions.
- Detects changes in the `index.html` file and deploys only when necessary.
- Simple and reusable workflow configuration (`deploy.yml`).

## How to Use ##

1. Clone the Repository
    git clone https://github.com/deavelarthiago/gh-deployment-workflow.git
    cd gh-deployment-workflow

2. Modify the Website Content
Edit the index.html file to update the content of the website.

3. Push Your Changes
Once you've updated the content, commit and push your changes:
    git add index.html
    git commit -m "Update website content"
    git push origin master

The deployed website can be accessed at:
https://<your-username>.github.io/gh-deployment-workflow/    

GitHub Actions will automatically deploy your changes to GitHub Pages.

## Contribution ##
Fork the project.

Create a branch for your feature:
   git checkout -b `my-feature`

Make your changes and commit:
   git commit -m "Added feature X"

Push your changes:
   git push origin my-feature

Open a Pull Request.
