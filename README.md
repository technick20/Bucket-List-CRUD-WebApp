# Bucket-List

## A To - Do List Website! 📆

A web application built with Node.js ,Express and EJS templates. Database used here is MongoDB which performs all the CRUD( create, read, update , delete ) operations on the To-Do list items. Database is hosted on MongoDB Atlas and then deployed using Heroku.

Project Link :https://evening-sierra-53249.herokuapp.com/

## Project First Look



https://user-images.githubusercontent.com/64360913/125173788-b45e4b80-e1de-11eb-9873-c077c00c97c1.mp4




## Features

| Functions              | Detail                                            | URL                         |
| :--------------------: | ------------------------------------------------- | --------------------------- |
| Add item to Today's List | 1. User can add item to list by entering the activity in input field and clicking '+' button<br>2. User can delete an item by clicking the checkbox | / |
| Add items to new route | 1. User can navigate to a new route example /home <br>2. This will create a fresh and new list independent of "Today's" list which can perform same CRUD operations  |/newListName |

### Prerequisites

- [Node.js v14.16.0](https://nodejs.org/en/download/)
- [npm](https://www.npmjs.com/get-npm)
- [MongoDB shell version v4.4.6](https://www.mongodb.com/)
- 

## Installation:
* Fork/clone this project to your local machine.
* Go to the location where project is downloaded in your terminal.
* Download all the dependencies.
```bash
> npm install
```
* Create todolistDB by running app.js in mongo shell and using mongoose.
* Start the by running app.js.
```bash
> node app.js
or
>nodemon app.js
```
* Run your project on localhost:3000
