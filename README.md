# Projectary

Final project of the discipline Projeto de Sistemas de Informação of Instituto Politécnico de Tomar[2017].

## Team AS

| Name | Username |
| --- | --- |
| Alexandre Ferreira | AlexandreFerreira65 |
| António Ferreira | todaniel |
| Arruá Valentim | Valentiim |
| Cristina Coxinho | coxinho |
| Rafael Escudeiro | rafescu |
| Renato Antunes | rffantunes |
| Ricardo António | ricardma |

## Diagramas de Sequência em falta!! 25/05/2017 @rffantunes
![Diagramas de sequência em falta](https://github.com/iptomar/gittests/blob/master/17422/Diagramas%20.png)

## Database

Information about the database can be found [here](https://github.com/iptomar/projectary-bd)

## API

Information about the API can be found [here](https://github.com/iptomar/projectary-api)

## Frontend

Information about the frontend can be found [here](https://github.com/iptomar/projectary-frontend)

## Methods 

### User  31/05/2017
| Method | Arguments | User | Function | Description |
| --- | --- | --- | --- | --- |
| GET | /USER | [USER] | list | Get User's list |
| PUT | /USER | [USER] | update | Update a User |
| GET | /USER/PENDING | [ADMIN] | pending | Get not confirmed users |
| GET | /USER/:ID | [USER] | info | Get a User |
| POST | /USER/:ID/APPROVE | [ADMIN] | approve | Approve a user |
| POST | /USER |  | createStudent | Create a Student |
| POST | /TEACHER | [ADMIN] | createTeacher | Create a Teacher |
| PUT | /USER/CHPASSWORD | [USER] | chPassword | Change User Password |
| PUT | /USER/:ID/SWLOCK | [ADMIN] | swLock | Switch the lock state of the user |
| POST | /LOGIN |  | login | Login a User |

## Built With

* [Angular2](https://angular.io/) - The framework used by the frontend
* [Node.JS](https://nodejs.org/en/) - Used in API
* [CasperJS](http://casperjs.org/) - Navigation scripting & testing
* [PhantomJS](http://phantomjs.org/) - Headless WebKit scriptable
* [MySQL](https://www.mysql.com/) - Database

and much more...

## Authors
List of [contributors](https://github.com/orgs/iptomar/people) who participated in this project.

