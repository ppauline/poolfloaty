<!-- AUTO-GENERATED-CONTENT:START (STARTER) -->
<p align="center">
  <a href="https://www.gatsbyjs.org">
    <img alt="Gatsby" src="https://www.gatsbyjs.org/monogram.svg" height="80" />
    <img alt="AWS" src="https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png" height="80" />
  </a>
</p>
<h1 align="center">
  Deploying a Gatsby site with AWS Amplify
</h1>

## Prerequisites 

Before starting the project you will need the following tools:

* AWS Account 
* GitHub Account
* Node.js & NPM
* Git
* Gatsby CLI 

## 🚀 Clone repository and run website locally

1.  **Clone repository.**

    Open the terminal and go the desired directory.

    ```shell
    # clone the repository using the following command
    git clone https://github.com/carloteran19/tmu-blog-amplify.git
    ```

1.  **Install dependencies and run website locally.**

    Navigate into your new site’s directory and start it up.

    ```shell
    cd tmu-blog-amplify
    gatsby develop
    ```
    Your site is now running at `http://localhost:8000`!
    
## 💫 Deploy to AWS Amplify

1.  **Create a new repository to store your website**

    Go to GitHub and create a new repository
    
    Open your terminal and replace the remote URL to point to your new repository

    ```shell
    # replace origin url with the following command (replace the_url_of_your_repo_here with the url of your new repo)
    git remote set-url origin the_url_of_your_repo_here
    ```
    
    Run the following commands to upload your site to your new repository
    
    ```shell
    git add .
    git commit -m "initial commit"
    git push origin master
    ```
2.  Log into the AWS Amplify Console

## 🎓 Helpful Resources

Looking for more guidance? Full documentation for Gatsby lives [on the website](https://www.gatsbyjs.org/). Here are some places to start:

- **For most developers, we recommend starting with our [in-depth tutorial for creating a site with Gatsby](https://www.gatsbyjs.org/tutorial/).** It starts with zero assumptions about your level of ability and walks through every step of the process.

- **To dive straight into code samples, head [to our documentation](https://www.gatsbyjs.org/docs/).** In particular, check out the _Guides_, _API Reference_, and _Advanced Tutorials_ sections in the sidebar.

<!-- AUTO-GENERATED-CONTENT:END -->
