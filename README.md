# CODE CHALLENGE TWO - SUPERHEROES_API

## Table of Contents
- [Project Description](#project-description)
- [Features](#features)
- [Technology Used](#technology-used)
- [Setup Instructions](#setup-instructions)
- [Copyright and license information](#copyright-and-license-information)
- [Author's Information](#authors-information)
- [Support and contact details](#support-and-contact-details)


### Project Description
This project is a simple Rails REST API that fetches heroes and their powers. It is a code challenge for the [Moringa School](https://moringaschool.com/) Full Stack Web Development course. The project is hosted on [Heroku](#).

The API allows users to manage superheroes and their powers. The application has two models: Hero and Power. The Hero model represents a superhero, and the Power model represents a power that a superhero can have. The application also has a join table model called HeroPower that manages the relationship between a Hero and a Power.

The HeroPower model has a strength attribute that can take one of the following values: Strong, Weak, Average. The Power model has a description attribute that must be present and at least 20 characters long.

The application provides several RESTful routes that allow users to view, create, update, and delete heroes and powers.

### Features
- Users can view a list of all heroes and their associated powers.
> `GET /heroes`
- Users can view a list of all powers.
> `GET /powers`
- Users can view details of a specific hero by id, including their name, superhero name, and powers.
> `GET /heroes/:id`
- Users can view details of a specific power, including its name and description.
> `GET /powers/:id`
- Users can create a new hero power association.
> `POST /hero_powers`
- Users can update the description of a power.
> `PATCH /powers/:id`


### Technology Used
- Ruby on Rails
- Postgres



### Setup Instructions

#### How to run the application locally on your computer.
- Open your terminal.
- Clone the repository `git@github.com:KarenKanana/Superheroes-code-challenge.git`
- `Bundle install`
- Run rails server `Rails s` or `Rails server`
- Use Postman to access the endpoints. 
- Internet connection is not needed to run API successfully.


### Copyright and license information
> [MIT License](https://github.com/KarenKanana/Superheroes-code-challenge/blob/master/License)

Copyright (c) 2022 Karen Kanana


### Author's Information
- Name: Karen Kanana 
- Email: kananakaren21@gmail.com
- [LinkedIn](https://www.linkedin.com/in/karen-kanana-4b8a78205/)



### Support and contact details
For any further clarification and support contact:

Email: kananakaren21@gmail.com

Show support with ⭐️ if you like this project!:wink::wink:

