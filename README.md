# Pepipost-Heroku-addon :email: 

## Introduction

 Developer likes to invest quality time for challenging problems. So we are just about to add some spice to our challenge by making the collaboration of Paas and Saas product. This challenge is all about making a Heroku *addon* for sending mail using Pepipost. 
 
 Heroku as a Platform allows you to make apps offering the flexibility of using multiple add-ons which minimizes the extra efforts of development. Similarly, Pepipost helps to deliver your emails right into the inbox to keep your IP reputation strong. SDKs of 6 out of 8 languages are available with pepipost which Heroku supports for development.
 
## What is my Challenge ?

 You need to contribute by making an add-on which will help developers to send email directly through Pepipost on Heroku platform. 

  * Integrating pre developed SDKs(all languages) within Heroku add-ons.
  * Defining usage of each language in add-ons.
 
 **Note : Information can be taken from Official [Pepipost website](https://pepipost.com)**

#### How can i start my challenge ?

  Using the below information you can easily get started with your challenge 
  
  * You can just have read through this great [article](https://akrabat.com/the-beginners-guide-to-contributing-to-a-github-project/) which will help you in contribution to this project, followed by our [CONTRIBUTING.md]()  
  
  * [Sign-up](https://app.pepipost.com/index.php/signup/registeruser) to pepipost for apikey which will be required for your Utilities , activate your account and send your first test mail using our sandbox domain.
  
  * Pepipost APIs from our [developers documentation](https://developers.pepipost.com) (This includes all the open APIs which is describe above in challenge). 
  
  * SDK from [Github reposistory](htt.ps://github.com/pepipost)(SDKs has only Email sending functionality)
  
### How should it look ?

  * On Heroku Dev center it would look has below.
  
    ![heroku](http://app1.falconide.com/integration_imgs/heroku.png)
    
      * Provisioning the add-on : 
        Pepipost can be attached to a Heroku application via the CLI mentioned below
        
        ```bash
        heroku addons:create pepipost
        ```
        Once pepipost is has been added a PEPIPOST_USERNAME, PEPIPOST_PASSWORD settings will be available in the app configuration and will contain the credentials used to access the newly provisioned Pepipost service instance
              
      * Obtaining an API key :
      
        Defining how API can be obtained from the panel and usage of APIKEY. As API Keys are used by your application, mail client, or website to authenticate access to Pepipost Service.
        
      * Golang,Java,Node.js,php,ruby,python :
       
        Defining usage of each language within Heroku application.
 
      * Dashboard,Migrating between plans : This is optional 
      
      * Removing the add-on : 
      
        ```bash
        heroku addons:destroy pepipost
        ```
  
#### What are requirements to get my pull request(PRs) accepted ?

  * Brief introduction of your challenge and making.
  * Prerequisites.
  * Installation Guide.
  * Example
  * Usage cases for each functionality.
  * Blog representing you hard work.
  
  You can publish your challenge by creating a pull request here in this reposistory.
  
### cheers :beer:

### All the Best :thumbsup:

## Happy Coding...! :tada:


  
