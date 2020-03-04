🇺🇸/[🇧🇷](https://github.com/Vinicciusjs/MaratonaDev3-Lista-de-Doadores-Sangue/blob/master/README.md) 

<p align = "center">
<a href="#Introdução">Introduction</a> |                                                                                                  <a href="#Funcionamento">Running</a> |                                                                                                          <a href="Procedimentos">Procedures</a>
</p>

<div id='Introdução'/>  
<h1 align = "center">Introduction</h1>
<p align = "justify">
Application created from "Maratona Dev 3.0". On the front-end you can find the introdu ction of the situation and the form to capture the data of a blood donator (name,e-mail and blood type). The back-end is reponsible with the configuration of the server and register the data captured in the front-end in a database. 
</p>

Inicial        |  Formulário
:-------------------------:|:-------------------------:
![](https://i.imgur.com/gkM9vZg.png)  |  ![](https://i.imgur.com/hvKsewO.png)|
<br /><br /><br /><br /><br />

<div id='Funcionamento'/>  
<h2 align = "center">Running</h2>

<p style= align = "justify">
The button "Quero Ajudar" (I want to help) will open the form. The form must be filled for the data to be saved at the the database and the list of "Ultimos Doadores"(Last Donators) to be updated with the related donator. If one or more data are left in blank the error page will be loaded and will warn the user that "Todos os campos devem ser preenchidos"(All the blanks must be filled). In that case no data will be saved at the database and nothing will be added to the "Ultimos Doadores"(Last Donators) list.
</p> <br />

<div id='Procedimentos'/>  
<h2 align = "center">Procedures to start the application</h2>

[Node.js](https://nodejs.org/en/download/) installation: Download and follow the installation procedures.

<p align = "justify"> Starting the server: Use the commando "npm start" at the terminal (CTRL + ') do vscode (CTRL + C to close the server).
</p>

<p align = "justify"> Configure the database: Edit the database's configuration parameters on the server.js file. The database must contain the tables "name", "email" and "blood" respectively and they all must be "text" type and cannot be null.
</p>

![](https://i.imgur.com/jxvFqay.png)

-user: Fill with the database's username. <br/>
-password: Fill with the database's password.<br/>
-host: Fill with the host adress. <br/>
-port: Fill with the conection port.<br/>
-database: Fill with the database's name.<br/>

