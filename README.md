<div align="center">
<h1 align="center">Recipe App</h1>
<p align="center">
A recipe management application built using the MERN stack styled with Tailwind CSS.
</p>
</div>

# Table of Contents

1. [Introduction](#introduction)
    * [About the project](#about)
    * [Goals and Objectives](#goals)
    * [Built with](#built)
2. [Installation](#installation)
   * [Installation Steps](#installation)
3. [Navigation](#navigation)
4. [Screenshots](#screenshots)

<h1 id="introduction">Introduction</h1>
<h2 id="about">About the project</h2>

This application, built using the MERN stack (MongoDB, Express, React, Node.js) and styled with Tailwind CSS, is a recipe management page designed to streamline the process of recipe creation, sharing, and discovery. It offers a user-friendly interface for both recipe enthusiasts and those looking to share their culinary creations.

<h2 id="goals">Goals and objectives</h2>

This project was undertaken as a hands-on exercise to solidify my understanding of MERN technologies. 
Through the development of this recipe management application, I gained practical experience in building a full-stack web application, from designing the user interface to implementing server-side logic and database interactions. 

In the future, I plan to enhance the application by integrating an external API to fetch a wider range of recipes. This would allow users to not only explore recipes created by the community but also discover new and diverse culinary options from the API, further enriching the user experience.

<h2 id="built">Built with</h2>

* ![React](https://img.shields.io/badge/react-%2320232a.svg?style=flat-square&logo=react&logoColor=%2361DAFB) 
* ![React Router](https://img.shields.io/badge/React_Router-CA4245?style=flat-square&logo=react-router&logoColor=white) 
* ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=flat-square&logo=javascript&logoColor=%23F7DF1E) 
* ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=flat-square&logo=css3&logoColor=white) 
* ![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=flat-square&logo=tailwind-css&logoColor=white) 
* ![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=flat-square&logo=node.js&logoColor=white) 
* ![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=flat-square&logo=express&logoColor=%2361DAFB) 
* ![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=flat-square&logo=mongodb&logoColor=white) 

<h1 id="installation">Installation</h1>
<h2 id="installation">Installation Steps</h2>

1. Clone the client repository
   ```sh
   git clone https://github.com/patr-silva/recipe-app-client.git
   ```

2. Clone the server repository
   ```sh
   git clone https://github.com/patr-silva/recipe-app-server.git
   ```

3. Install the required dependencies using npm on each repository
   ```sh
   npm install
   ```
4. Run the backend application 
   ```sh
   nodemon src/index.js
   ```
5. Run the frontend application 
   ```sh
   npm run start
   ```

<h1 id="navigation">Navigation</h1>

| Route | Component     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `/`      | Home | Displays the homepage |
| `/auth/register`      | Register | Displays the sign up page. |
| `/auth/login`      | Login | Displays login page. |
| `/recipes`      | Recipes | Displays all the recipes. |
| `/recipes/details/${recipeId}`      | Single Recipe | Displays the recipe details. |
| `/recipes/saved-recipes/${userId}`      | Saved Recipes | Displays the recipes saved by the user. |

<h1 id="screenshots">Screenshots</h1>

<img width="440" alt="Home" src="https://github.com/user-attachments/assets/0666ba8d-fd82-4a32-860f-65ac4c121905">
<img width="440" alt="Recipes Page" src="https://github.com/user-attachments/assets/ead4d746-f673-4743-b5b7-03fb4b86456e">
<img width="440" alt="Create recipe page" src="https://github.com/user-attachments/assets/a8ea3f34-e202-40f7-8bd7-5bcf5ac8eca5">
<img width="440" alt="Login page" src="https://github.com/user-attachments/assets/d0b50c16-80e4-471c-93f2-4b3b7b31e7b1">
