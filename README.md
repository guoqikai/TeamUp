# TeamUp

A web application built from scratch using React, Express.js and MongoDB.

[Demo(1.0.0): Deployed on Heroku](https://team-up-2021.herokuapp.com/)

Note: Since the application is deployed on Heroku, it takes longer to load if it has not been accessed for a period.

## About the App

There are a lot of times that we have an interesting project idea but fails to find people who are also interested. Other times, we may want to be a part of an amazing team and work on a creative project but have no idea where to look for such opportunities. Team-up is an application for sharing project ideas and looking for teammates. There is also an in-app live chat box that supports both group chat and direct message.

## Navigate the App

After landing on the main page of the application. Users can click **Log In/Sign Up** button to log in or create a new account.   
<img src="./app-previews/main-page.png" />   

Enter the information and sign up for an account. Users can return to the home page by clicking on the **Team-Up** logo in the side bar.   
<img src="./app-previews/sign-up.png" />   

After logging into the account, users can update their profile, including the profile picture, through **My Profile** link button on the side bar.   
<img src="./app-previews/my-profile.png" />

To create a project, click on the **Create Project** link button in the side bar. Users can add project name, description, project image and open positions on the page. The option of creating a chat group for the project is also given.   
<img src="./app-previews/create-project.png" />

Everyone in the community can see your project and apply for the roles now by clicking on the project card in project list. In the popup, users can apply for one or multiple roles, like the project, and view project details. The project owner can also apply for roles.   
<img src="./app-previews/project-popup.png"/>   

Users can view their projects by clicking **My Projects** link button in the side bar. Owner of a project can delete the project; member of a project can exit the project.   
<img src="./app-previews/my-projects.png"/>   

Owner of a project can update the project information, including project image, add/delete open roles, accept/reject applications for roles. 
<img src="./app-previews/add-delete-role.png"/> <img src="./app-previews/accept-reject-role.png"/>   

After an application is accepted, the user will be added as a member to the project, and the role will no longer be open.   
<img src="./app-previews/updated-project.png"/>   

In the main page of the application, there are 3 sections, **Projects**, **People** and **Skills**. The search bar can search for each category separately. The search function is case-insensitive, and only exact match of whole word will be displayed.   
<img src="./app-previews/search.png"/>   

In the **People** section, all users of the application will be shown in an infinity scroll list with random order.   
<img src="./app-previews/people-page.png"/>   

Clicking on a user card will open a popup that has options of talking to the user, by clicking the **Add to Chat List** button, and viewing the user's profile, by clicking the **View Profile** button. If a user is added to chat list but no conversation occurs, the user will be removed from the chat list later.   
<img src="./app-previews/user-popup.png"/>   

On the user profile page, the profile information and the projects enrolled by the user are displayed.   
<img src="./app-previews/user-profile.png"/>   

In the **Skills** section, the skill channels are listed in descending order of popularity. If users want to discuss about certain topics or look for people with specific skills, they can join corresponding skill channels. 
<img src="./app-previews/skills-page.png"/>   

Clicking on a skill channel card will open a popup with the description of the channel and a button to join/leave the channel.   
<img src="./app-previews/skill-popup.png"/>   

Clicking on the **Messages** link button will open the chat box with all the group chat and direct message of the user listed on the left.   
<img src="./app-previews/group-chat.png"/> <img src="./app-previews/direct-message.png"/>   

## How to Start The App Locally

1. cd to the root folder
2. run `npm run-script setup`
3. run `npm run-script build-run`
4. after server starts, visit `localhost:5000` 

