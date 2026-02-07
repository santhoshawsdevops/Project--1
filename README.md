***** CI/CD Pipeline for Static Website using Jenkins & Nginx on AWS EC2*****
--------------------------------------------------------------------------------------------------------------------------------------------
Project Overview

This project demonstrates a basic CI/CD pipeline that automatically deploys a static website to an AWS EC2 instance running Nginx using Jenkins.

Whenever code is pushed to the GitHub repository, Jenkins pulls the latest code and deploys it to the web server without manual intervention.
---------------------------------------------------------------------------------------------------------------------------------------------
 Objectives

Understand CI/CD pipeline concepts

Automate deployment using Jenkins

Deploy a static website on Nginx

Gain hands-on experience with AWS EC2 and Linux permissions

Troubleshoot real-world deployment issues

-----------------------------------------------------------------------------------------------------------------------------------------------------

*** Architecture ***

Flow:

Developer → GitHub → Jenkins → EC2 (Nginx) → Website Live


Description:

Developer pushes code to GitHub

Jenkins detects changes and triggers the pipeline

Jenkins copies website files to /var/www/html

Nginx serves the updated website
