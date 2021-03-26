# Team 26 - Untangle Money

## Description 
We are planning to build a mobile-responsive web application that helps women aged 20-30 have a better understanding of their current financial situation along with helping them plan their future finances. This product is trying to solve the issues that women aged 20-30 have which is a nagging suspicion they should understand money better but haven't found anything that resonates with them yet. For example a woman who has just started her life as an independent adult wouldn't have much knowledge about her current financial situation and might not have set financial goals both present and in the future, this application would be able to solve her problem.


## Key Features
The key features of our application starts with the registration feature: it allows the user to create an account by inputting their first name, email address, and password. Building upon the registration feature we also included a feature to create a financial baseline for the user that receives the financial information to generate additional financial details that are useful for them. The next key feature would be the login feature, it forces the user to verify their email address before their first login and once verified it allows the user to access the financial features of the application. Another key feature of our application is displaying the users own financial baseline which then projects additional information regarding their financial situation based on their inputs from registration. We also included the analyzing financial decision scenario feature which shows the user potential future graphs based on inputs from a scenario of their choice. The last key feature of our application is the save/modify/delete financial scenario feature it allows the user to save any potential scenarios they feel are beneficial to them, modify saved scenarios in the future if a key value has changed since the save, or delete scenarios that are no longer useful to them.


## Instructions
<ol>
    <li>Go to: <a href='https://cscuntangleff.web.app/'>https://cscuntangleff.web.app/</a></li>
    <li>If the user doesn’t have an account they must go register by clicking the: “Don’t Have An Account? Sign Up” link.</li>
    <li>If the user is registering they must provide a first name, email, and password then submit</li>
    <li>Once the user registers they will be redirected to the Financial Input page where they must input all the required financial information and then submit.
</li>
    <li>If the user already has an account they must first check if their email has been verified by checking the inbox of the email associated with the account and verifying through the email sent from Firebase.
</li>
    <li>Once the user has logged in or completed filling out their Financial Input page they will be redirected to the User Dashboard where they can see all their financial information and make any edits to their financial values if need be.
</li>
    <li>If the user wants to make decisions on a scenario (Debt, Retirement Saving, etc.), they should click the corresponding block at the bottom on the dashboard page.
</li>
    <li>There are a row of buttons at the top right corner of the dashboard: Home, About, Progress, Logout. Clicking “Home” will send the user to the top of the dashboard; clicking “About” will direct the user to the area where shows the user information; clicking “Progress” will direct the user to the area where they can go to do financial analysis; clicking “Logout” will send the user back to the login page.
</li>
    <li>The user can do financial analysis in the progress section at the bottom of the dashboard page. Currently only the Debt Payment Analysis is supported. On the analysis page, moving the slider bar can adjust the amount of the monthly payment that the user would like to pay (it can not be smaller than the sum of the minimum payment of all the debts). The table shows information about the expected debt payment progress in the future (the data of payment periods of each debt is large and should be deployed by a graph, but the graph is not finished yet).
    </li>
    
</ol>
 
 ## Development requirements
 If a developer were to set this up on their machine, they would require the Node Package Manager, if they do not have this would need to visit: https://nodejs.org/en/download/ then install npm, and Git if they do not have this either they need to visit: https://git-scm.com/downloads to install Git. There are no requirements regarding OS, or libraries. Once they have all the tools listed above they would need to clone a copy of the application’s repository, then from the command line the would need to change their present working directory to untangle-money directory from here they would then enter into command line: “npm install” which would then proceed to install all the packages required for the application to run, and afterwards the developer would just need to enter: “npm start” into the command line which would then automatically start up our application on their local server.

 ## Deployment and Github Workflow

Our team shares a codebase, while avoiding conflicts, and deploying the application via manual deployment which for our team means creating separate branches for each feature we work on, for example for the login/registration feature the developer creates a branch to specifically work on that feature thus avoiding any conflicts with other developers working on other parts of the code. After the feature has been completed the developer working on that branch will make a pull request from the feature branch to the master branch, then once the request is made we take time in our weekly meetings to look over the pull request as a team to see what if there are any adjustments that need to be made once everyone approves, the pull request and feature branch is then merged into the master branch, and then we repeat this process with other features we implement and once we have completed and approved a couple of features we then deploy a live application thus in terms of deployment tools we didn’t use any but rather manually checked everything as a group which we would then deploy. We chose this workflow because it forces each member to up-to date as to what everyone else is working on and allows them to understand the code of other developers so when they implement their own feature they may remember how another developer implemented a similar way which helps them implement their own code as opposed to everyone just working on their own features without looking at what others are doing this way makes the process of coding easier.

 ## Licenses 

 The license we had chosen for this project is the MIT Open Source License. It allows us to share our code under a copyleft license without forcing others to expose their proprietary code. The main reason that we chose this is that it is business friendly and open source friendly while still allowing for monetization. 



