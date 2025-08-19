
Project Setup: Boston Region STOPS (Hugo & Docsy)
======================================================

This guide covers the one-time setup for this project on a new computer.

--------------------
Part 1: Prerequisites
--------------------

1. Install Git: https://git-scm.com/
2. Install Hugo (Extended Version): https://gohugo.io/installation/
3. Install Go Language: https://go.dev/dl/


--------------------
Part 2: GitHub & Local Setup
--------------------

1.  **Clone the Repository:**
    Download the project source code from GitHub. The `--recurse-submodules` flag also downloads the theme.
    
    `git clone --recurse-submodules https://github.com/CTPSSTAFF/boston-region-stops.git`

    `cd boston-region-stops`


2.  **Fetch Theme Dependencies:**
    If the theme's dependencies are missing, run the following command to download them.
    
    `hugo mod tidy`


3.  **Run the Local Server:**
    Start the Hugo server to preview the website locally.
    
    `hugo server`


4.  **View the Site:**
    Open a web browser and go to the URL provided in the terminal (usually http://localhost:1313/).


--------------------
Part 3: Daily Workflow
--------------------

1.  **Start the Server:** Before making changes, run `hugo server`.
2.  **Edit Content:** Add or edit Markdown files in the `content/en/` directory.


--------------------
Part 4: Deployment
--------------------

Deployment to the live website is **automatic**. Every time you push a commit to the `main` branch, a GitHub Action will automatically build and publish your site. You can monitor its progress in the "Actions" tab of your GitHub repository.