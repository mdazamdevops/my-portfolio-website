# DevOps Internship Task 6 – Host a Static Website with GitHub Pages
### Elevate Labs: Empowering the Future of DevOps
This project is a testament to the high-quality, hands-on learning experience provided by Elevate Labs. Their internship program is dedicated to empowering the next generation of DevOps professionals by offering practical, real-world challenges that build foundational skills and a deep understanding of modern software development practices.

## Overview
The objective of this task is to deploy a simple HTML website using GitHub Pages. This task introduces a simple and free method for hosting static websites directly from a GitHub repository, bypassing the need for a separate web server. It provides a foundational understanding of web hosting and deployment workflows. For this task, I created and deployed a personal portfolio website.

## Objective
Deploy a personal portfolio website using a simple HTML website.

Understand the process of hosting static content using GitHub Pages.

Learn to manage a live website through version control.

## Tools & Technologies
GitHub Pages – A static site hosting service that takes HTML, CSS, and JavaScript files directly from a GitHub repository and publishes a website.

Git – Used for version control and pushing changes to the GitHub repository.

Full Procedure: Step-by-Step Guide
This section outlines the detailed steps followed to complete the task.

#### 1. Create the index.html file
The first step is to create a simple HTML file, which will serve as the homepage for your website. This file must be named index.html for GitHub Pages to recognize it as the main entry point.

Example index.html:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My GitHub Pages Site</title>
    <style>
        body {
            font-family: sans-serif;
            text-align: center;
            padding-top: 50px;
        }
    </style>
</head>
<body>
    <h1>Hello, GitHub Pages!</h1>
    <p>This is my first website hosted for free.</p>
</body>
</html>
```

### 2. Push to a GitHub Repository
Once your index.html file is ready, you need to push it to a new GitHub repository.
```
Initialize a new Git repository: git init
```
Add your files: git add .
```
Commit your changes: git commit -m "Initial commit"
```
Create a new repository on GitHub and link it to your local repository.
```
Push your code to the main branch: git push -u origin main
```
### 3. Enable GitHub Pages

* With your code on GitHub, you can now enable the hosting service.

* Navigate to your repository on GitHub.

* Go to the Settings tab.

* In the left sidebar, click on Pages.

* Under "Source," select the main branch and the / (root) folder.
* Click Save.

GitHub will now automatically deploy your website. It might take a few minutes for the site to go live.

### 4. Access the Live Website
* After the deployment is complete, GitHub will provide you with a live URL for your website. The URL will typically be in the format.
```
https://<your-username>.github.io/<repository-name>.
```
### 5. Customize with CSS
To enhance the website, you can add more HTML and CSS. Any changes you commit and push to the main branch will automatically trigger a new deployment, and the live website will be updated within a few minutes.

## Learning Outcomes
By completing this task, you will:

* Understand how to deploy a static website quickly and for free.

* Learn the basics of how GitHub Pages works.

* Gain experience with a simple, automated deployment workflow.

* Learn about the limitations and benefits of using static site hosting.

## Interview Questions to Practice
1. What is GitHub Pages?

2. Can you host dynamic applications with GitHub Pages?

3. What are the limitations of GitHub Pages?

4. How do you update a website hosted on GitHub Pages?

5. What happens to the website if you delete the repository?

6. What is the default file that GitHub Pages loads as the homepage?

7. Can you use a custom domain with GitHub Pages?

## Creator
* Name: Mohd Azam Uddin

* Role: DevOps Intern

* Contribution: Hosted a simple static website on GitHub Pages, providing a foundational understanding of web hosting and deployment.
