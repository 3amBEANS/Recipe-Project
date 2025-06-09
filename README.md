# ReciMe: Recipe Finder Web App

[ReciMeProposal.pdf](https://github.com/user-attachments/files/20633601/ReciMeProposal.pdf)

https://github.com/user-attachments/assets/d3904e9f-4075-44ea-85f2-c6cff9870678

# Project Description

The purpose of the app is to help users find the recipe they are looking for without frills--just immediate access to their favorites. Users can create recipes, engage with the Recime community, and use numerous health/diet filters to narrow down their search. Learn more in the above proposal.

# Table of Contents

1. ### [Installation](https://github.com/3amBEANS/Recipe-Project/edit/main/README.md#installation-1)
2. ### [How Login Works](https://github.com/3amBEANS/Recipe-Project/edit/main/README.md#how-login-works-1)
3. ### [Major Components and Features](https://github.com/3amBEANS/Recipe-Project/edit/main/README.md#major-components-and-features-1)
4. ### [Tech Stack](https://github.com/3amBEANS/Recipe-Project/edit/main/README.md#tech-stack-1)
5. ### [Credits](https://github.com/3amBEANS/Recipe-Project/edit/main/README.md#credits-1)

# Installation 
* cd into the backend folder and type the command `npm install` to install the dependencies
* Contact one of the members in order to gain access to the .env files and permissions.json files
* Run `npm start` in your backend file to run your server

* cd into the recipe-project folder
* Run `npm install` to install the dependencies
* Finally, run `npm run dev` to start the Vite app and open your localhost port to access the webpage.

# How Login Works

* User clicks “Sign up” to create a ReciMe account, or "Sign in" if they already have an account (NOTE: password storage is not yet encrypted)
* Server saves your login information in Firebase.
* User gets sent to the homepage.

# Major Components and Features

* Homepage with easy navigation
* Recipes page to search for Edemam or community (user-created) recipes
* Recipe details page when clicking on an individual recipe (includes review/comment system and AI-chatbot)
* My Recipes page which displays the user's created and saved recipes
* Create Recipes page which has a form to create your own recipe (will not show in community recipes until admin account approves recipe)
* Admin page (only accessible and viewable to admin users) for reviewing, publishing or rejecting all user-submitted recipes (For admin access, modify Firebase user attribute "admin" to true

# How to use the Project

See Above Demo video

# Tech Stack

React Frontend
Express Backend
Firebase Data Storage

# Credits

### Technologies

- [Edamam API](https://www.edamam.com/)
- [Chakra UI](https://chakra-ui.com/)
- [MUI](https://mui.com/)
- [Firebase Firestore](https://firebase.google.com/)

### Developers

- [Aiden Ha](https://github.com/3amBEANS)
- [Julia Rieger](https://github.com/jvrieger)
- Danielle Quaye
- Sarathy Selvam
- Henok Misgina Fisseha
