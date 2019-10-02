<!-- AUTO-GENERATED-CONTENT:START (STARTER) -->
<p align="center">
  <a href="https://www.gatsbyjs.org">
    <img alt="Gatsby" src="https://www.gatsbyjs.org/monogram.svg" height="80" />
    <img alt="AWS" src="https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png" height="80" />
  </a>
</p>
<h1 align="center">
  Deploying a website with Continuous Deployment using AWS Amplify
</h1>

## Prerequisites 

Before starting the project you will need the following tools:

* AWS Account 
* GitHub Account
* Git
* Node.js & NPM (Optional for local development)
* Gatsby CLI (Optional for local development)

## 🚀 Clone repository and run website locally

1.  **Clone repository.**

    Open the terminal and go the desired directory.

    ```shell
    # clone the repository using the following command
    git clone https://github.com/carloteran19/tmu-blog-amplify.git
    ```

1.  **Install dependencies and run website locally (optional)** 

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
    
    Go to [AWS Amplify](https://console.aws.amazon.com/amplify/home)
    
    Click on **Get Started**
    
    Select GitHub as your repository service.
    
    Connect to **master** branch and click **Next**
    
    Review build settings - Click **Next** and then click **Save & Deploy**
    
    AWS will build and deploy your website 
    
    Click on the new generated URL for go to your new website.


## 🎓 Helpful Resources


<!-- AUTO-GENERATED-CONTENT:END -->
