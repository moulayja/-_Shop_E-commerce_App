# & Shop E-commerce App:

E-commerce store 

## Table of Contents

- [App Preview](#app-preview)
- [Collaborators](#collaborators)
- [Project Description](#project-description)
- [Technologies](#technologies)
- [Getting Started](#getting-started)

#### Project Status: [Completed]
Final Version

## App Preview
[For a full demo, click here](https://youtu.be/N70zLvOkDuk)

## Collaborators
| Name | Github Page |
| --- | --- |
| Jamal Farah | [Profile Page](https://github.com/moulayja) |


## Project Description
#### Overview:

The idea is to create a responsive E-commerce app that allows the Admin to have full access to the CRUD

At the footer, I used an SVG managed by the state to change the colors between, Create(Pink-color), Read (Pink-color), Update(Green-color), Delete(Red-color).

The website can go from darker to lighter themes by pressing the Plugin Logo.

The user can add a product to his cart once, while he can add more once he is inside the cart component  

You can also Sign Up, Sign In simply.
#### Challenges:
Passing functions and states through props can be daunting, I wanted to use React Hooks with Context at certain points, but I learnt a lot this way.


## Technologies
- Dynamic & responsive Front-end using ReactJS
- Bootstrap and CSS
- Rails API for the Back-end
- PostgreSQL as a backend Database-API
- RESTful architecture for CRUD actions
- Managed global state through props
- Custom login authentication & authorization with use of JWT

## Getting Started
1. Clone this repo
2. Cd to the project file 'back_end' 
   ```bash
      $rails db:reset && rails s -p 3007
   ```
3. Open another CMD terminal, cd to the project file 'front_end' 

   ```bash
      $sudo npm install && npm start
   ```
4. The server will open a new window under the localhost at port 3000
   ```bash
      http://localhost:3000/
   ```


5. Keep navigating the store


