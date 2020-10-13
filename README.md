#Redspace -Starwars Angular and Nodejs Application

#Date Created
10/10/2020

#Author
Swarali Ghalwadkar 


#Description 

This project basically involve establishing a connection between the Angular framework and an external API using nodeJS and the concept of services provided in Angular.
The starwars application has been developed using Angular as the front end framework along with Node.js and express as the backend/Server  environment. This application allows the user to navigate through and view few static pages. However, it mainly allows the user to perform a search functionality in order to search for their favourite star wars characters by either entering their name or entering their ID. Once the user provides the input, the application hits the respective endpoint and fetches the corresponding data accordingly. Lazy Loading takes place since nested API's are called in order to display certain data.


#Installation

1)Angular CLI was installed
2)Node was installed 
3)Express library was installed
4)Bootstrap was installed using the following command :-
npm i bootstrap@4 --save 
5)Al-shah package containing certain design files was copy pasted into node modules.
6)Font Awesome package was installed using the following command
npm install font-awesome --save
7)Materialise CSS folder was added to the assets folder 


#Built With 

Front end Framework - Angular
Backend Framework - NodeJS and library
Backend scripting Language - Javascript
Text Editor - Visual Studio Code
Design factors - Materialise CSS , Font- Awesome icons, Al-shah Package
Responsiveness- Bootstrap
Functions written in - Typescript 
UI - HTML , CSS , SCSS
Hosted on - Gtihub , EC2 AWS instance



#Functionalities:-

1)Created well defined components for aboutus page, films page, header, footer, homepage, and search.
2) Providing routing module that can route between various components. The common modeule used wad the app.routing.js module.
3)Created a service for establishing a connection from Angular to the external API. 
4)Used the concept of injections in order to inject the service in the search component.
5)Used Async pipes, RXJS library and observables in the service in order to observe and catch the changes made in the endpoints while the user keeps providing various input values for the name or ID.
The concept of subscription was used in the searchcomponent.ts file in order publish the responses of the observables 
6)Used the concept of Lazy Loading in order to fetch data from nested APIs.
7) Utilised *ngIf and a local reference variable in order to display a message incase if the user enters a non-existing value.
8)Added a javascript element in order to clear out the input text from the input feild upon clicking the search button.
9)Utilised a few inbuilt color functions belonging to SCSS.
10)Utilised the Bootstrap framework in order to make the website responsive.
11) Installed the al-shah package in order to acheive additional UI enhancements.
12) Utilised the materilise CSS framework in order to make certain html elements more enhanced and creative.
13)Utilised the font-awesome icons library to add font awesome icons in the footer.
14) Wrote a function in the typescript file of the aboutUs page that allows the user to click on various links in the sub-header and that auto scrolls to that particular link's section. 
15) Added the colour flapping effect upon hovering across the character cards on the homepage and the movie cards on the films page. 
16)Deployed the project to Github. 
17) Deployed backend of the project onto an EC2 instance on the AWS cloud.



#Constraints

1) Please copy paste the al-shah folder to nodemodules (under node modules) once node modules has been installed otherwise the UI will not look the way it supposed to .
2) The species API did not consist any data originally. The code to access it has been written , however it has been commented in order to not spoil the display. The purpose was commenting it out was just to show the logic written behind it.



#Deployment and URLS

Upon taking a pull from Github and setting up an angular and node js application on to your machine , the following steps need to be followed :-
1)Copy paste the al-shah folder to the nodemodules
2)Run the following commands upon entering the frontend folder.
npm i font-awesome --save 
npm i bootstrap@4 --save
3)Run the command ng serve-o after entering the frontend folder for running the Angular application
4) Run the command node server.js after entering the nodeapp folder in order to run the node application. 

URLS:-
1)Github
Github Project Link -   https://github.com/swaralisg/redspaceTask/tree/master

2)AWS EC2 Machine 
Nodeapp (backend) is hosted on AWS EC2 Instance
AWS Cloud URL for accessing all the data -  http://52.23.238.97:8080/people

AWS Cloud URL for accessing a character's data by ID- 
http://52.23.238.97:8080/people/1
http://52.23.238.97:8080/people/2

AWS Cloud URL for accessing a character's data by name -
 http://52.23.238.97:8080/people/name/Luke Skywalker
 http://52.23.238.97:8080/people/name/Biggs Darklighter

