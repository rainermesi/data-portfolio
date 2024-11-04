---
layout: post
title: "Setting Up a DBT-BigQuery Pipeline Directly in GitHub"
date: 2024-11-04
---

# Setting Up a DBT-BigQuery Pipeline Directly in GitHub

This project demonstrates how to set up a DBT pipeline to run basic transformations on BigQuery data, entirely from GitHub. Key elements include:

1. **Basic DBT Transformations**: Using the `raw` model layer in DBT, the project reads data from BigQuery and writes it back to a new dataset.

2. **In-Browser Development with VS Code**: I set up and tested the whole project using GitHub's in-browser VS Code, including activating a Poetry environment for DBT commands.

3. **Automating Credentials**: The repository includes a shell script that generates a temporary service account key, enabling secure DBT execution within the GitHub environment.

Overall, I found GitHub’s setup surprisingly efficient for this workflow, highlighting a streamlined approach for DBT projects directly on GitHub.

---

For more details, check out the project [here](https://github.com/rainermesi/DBT-BigQuery-Analytics-Look-eCommerce).
