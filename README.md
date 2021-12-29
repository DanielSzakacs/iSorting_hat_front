# Sorting hat -> iSortingHat
Hello, 
This is a small, short-term pet project. 
The main goal was to create an API for a random school by using Spring framework, maven, creating Students model, and CRUD Rest endpoints for the students.
I wanted to make this project a bit more interesting, so I thought I will make the "Sorting hat" 2.0... the iSorting_Hat! 
A brand new way for students to make know more about their school, their teachers, and about each other. 
No need to have one of "The Marauder's Map" to know where is your mate, and no more unknown faces in the dark corridors of Hogwarts.

# Technology Stack:
- Spring Boot
- Java 8
- Docker
- Bootstrap
- Angular

# Homepage
![alt text](img/home_page.png)   
# Students
All the data for the Students are coming from an API (http://hp-api.herokuapp.com/api/characters/students)
The data from this API is not the best .. (there is no good API) .. so I have to filter them by some preferences. 
To make the page faster, after I got all the necessary data an Entity will be created and saved to our local DB, so next time we don't have to search for the 
valuable data. 
![alt text](img/students.png)
# Teachers 
The teacher Entity is created and saved to your local DB right after the project is started.
You can see the teachers names and positions in the school, and by clicking on the 'Profile' button you can find more details about their work or life.
![alt text](img/teachers.png)   
# Map
![alt text](img/map.png)
# History
![alt text](img/house_story.png)   




------------------------------------------------------------------------------------------------------------------------


This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 13.1.2.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
# iSorting_hat_front
