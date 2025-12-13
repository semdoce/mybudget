# findash-ieee

## Technologies

- List your tech stack here (e.g., React, Node.js, PostgreSQL, etc.)

* React
* Vite
* Tailwind
* Toastify
* Axios
* Jsonwebtoken
* Node.js
* Knex
* Express
* Highcharts

## Features

- Creates a local database for users and transactions;
- Profile picture uses a folder to copy paste your image in DB side, the DB can then read the file location and show.
- Show your transactions in a pizza, bar or line graph using Highcharts;

## What Users Can Do

- Create, login and delete an account;
- Change their: username, profile picture, password;
- Create, delete and change their transactions;

## Creation Process

Describe the development journey and key milestones:

- When we started this project we didnt knew how it would turn out. It was my very first big project, so I was about to approach it like anything I did before: just learning the tools I had to use and then coding. Well, it didnt turn out that way, besides I had to learn how to structure a database first, and learn how to work with a team. Took some months, many people helped us a lot with this, telling us new things about data security and design.

- The principal idea was to integrate React (with Vite) and Node.js to create a program that can help you with finances. Creating transactions of adding cash or subtracting it from more than one way of payment (credit card, debit card, emergency account, etc).

- Testing and refinement

## What I Learned

- wip, its a plenty of things.
-
-

## How It Can Be Improved

- Group finances workflow (multiple people interaction).
- CRUD Category management
- Change the filtering method from front to backend (Is better to work with databases on filtering data situation.)
- Bug testing
- Reducing the ai slopped code (that will be a pain on my vacation...)

## How to Run the Project

### Prerequisites

- To run it, you'll need Node.js 24.11 or later.

### Installation

```bash
git clone https://github.com/semdoce/findash-ieee.git
cd findash-ieee
cd front
npm install
cd ../back
npm install
```

### Env Example

- Before you run the project, you'll need to set the env (environmental variables). Onto back folder, there's a .env.example file with these variables:

```
DB_CONNECTION -> This is the database you use. Knex have to understand it. (For ex.: mysql, mysql2, postgres)
DB_NAME -> That's the database name (For ex.: findashieee)
SERVER_HOST -> Just set to localhost
SERVER_PORT -> Just set to 3000
DB_PORT -> Just set to 3306
DB_USER -> Your user on your database manager (For ex.: root)
DB_PASSWORD -> Your database manager password (For ex.: 1234)
JWT_KEY -> This has to be any key you want, the application will use it to encrypt and decrypt the html headers (can say its a paywall). (For ex.: secret_key_jwt)
```

### Running

```bash
cd back
npm run start
cd ../front
npm run dev
```
