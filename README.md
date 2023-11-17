Welcome to my website.
Please find it here : https://widyaliu.site/
Here are the instructions on how to deploy my website from github to the custom domain. 

## Table of contents

- Netlify Deployment
- Purchasing Custom Domain
- Connecting Netlify with the Custom Domain

Assignment : to create a readme file that includes relevant information about the deployment process, connecting to a custom domain, and any additional details or configurations.

## Netlify Site Deployment
1.Go to your team’s Sites page, open the Add new site menu, and select Import an existing project.
2.Select the Git provider where your project is hosted.
3.Select your project’s existing repository.
4.Adjust site and build settings if necessary.

##Purchasing Custom Domain
1.Go to Niagahoster
2.Enter the domain that you preferred. In this case I chose widyaliu.site
3.Proceed with the payment
4.You will receive a confirmation email from your domain registry

##Connecting Netlify with the Custom Domain
1.On your Netlify, go to "Setup your site" Section, click "Setup a Custom Domain"
2.Please enter the domain that you purchased from Niagahoster. e,g widyaliu.site then click "Verify"
3.Go back to Netlify Dashboard, Open your Project, Custom Domain. You will see your custom domain is pending for External DNS. 
4.Now go to domains, scroll down and look for Name Severs.
5.Copy all 4 Name server to point your domain’s name servers to Netlify, paste all these 4 to : 
You should be able to find this in Domains-> Manage ->Domain Overview -> Click change on Name servers
6.Congratulations! This is all completed! Please wait for up to 1x24 hours for your custom domain to be connected and hosted
  

## Changing your repository
1.Go to Netlify, Build&Deploy then go to Continuous Deployment. You can either link to a different repository or
unlink your current repository. In this case I will go ahead and pick option 1

![alt text](https://github.com/revou-fsse-3/milestone-1-wwliurevou/blob/main/asset/deploy1.PNG)

2.Don't forget to connect to your repository, and pick appropriate one. 
![alt text](https://github.com/revou-fsse-3/milestone-1-wwliurevou/blob/main/asset/deploy2.PNG)

3.Make sure that your repository is NOT private. Please change it to Public if so. 
![alt text](https://github.com/revou-fsse-3/milestone-1-wwliurevou/blob/main/asset/deploy3.PNG)

4.As you can see, it will show which Git repository, please choose appropriately
![alt text](https://github.com/revou-fsse-3/milestone-1-wwliurevou/blob/main/asset/deploy4.PNG)

5.Files will be uploaded from repository to your netlify, and you can click Open Production Deploy to check the website
If everything looks good, please proceed with choosing Publish Deploy
![alt text](https://github.com/revou-fsse-3/milestone-1-wwliurevou/blob/main/asset/deploy5.PNG)

6.As you can see the status change to lock to stop auto publishing! voila you have your site ready!
![alt text](https://github.com/revou-fsse-3/milestone-1-wwliurevou/blob/main/asset/deploy3.PNG)

