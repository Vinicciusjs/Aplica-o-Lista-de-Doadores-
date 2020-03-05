[🇺🇸](https://github.com/Vinicciusjs/MaratonaDev3-Lista-de-Doadores-Sangue/blob/master/README%20ENG.MD)/[🇧🇷](https://github.com/Vinicciusjs/MaratonaDev3-Lista-de-Doadores-Sangue/blob/master/README.md) 

<p align = "center">                                                                                                                             <img alt="Javascript" src="https://img.shields.io/badge/Code-Javascript-blue">                                                                 <img alt="CSS" src="https://img.shields.io/badge/Style-CSS-RED">                                                                                                          
<img alt="CSS" src="https://img.shields.io/badge/WEB-HTML-orange">   
<img alt="License" src="https://img.shields.io/badge/license-MIT-brightgreen">  
</p>

<p align = "center">
<a href="#Introdução">Introdução</a> |                                                                                                  <a href="#Funcionamento">Funcionamento</a> |                                                                                                          <a href="Procedimentos">Procedimentos</a>
</p>

<div id='Introdução'/>  
<h1 align = "center">Introdução</h1>
<p align = "justify">
Aplicação criada a partir da Maratona Dev 3.0. No front-end temos a introdução da situação e o formulário para cadastrar um doador de sangue (Nome,e-mail e tipo sanguineo) e o back-end é responsável configurar um servidor e registrar os dados capturados no front-end em um banco de dados.
</p>

Pagina Inicial        |  Formulário
:-------------------------:|:-------------------------:
![](https://i.imgur.com/gkM9vZg.png)  |  ![](https://i.imgur.com/hvKsewO.png)|
<br /><br /><br /><br /><br />

<div id='Funcionamento'/>  
<h2 align = "center">Funcionamento</h2>

<p style= align = "justify">
O botão "Quero Ajudar" irá abrir o formulário. O formulário deve ser preenchido para que os dados sejam salvos no banco de dados e a lista de "Ultimos Doadores" seja atualizada com os respectivos dados do doador. Caso um ou mais dados sejam deixados em branco a pagina de erro será carregada avisando o usuário que "Todos os campos devem ser preenchidos." Neste caso nenhum dado será salvo no banco de dados e nada será adicionado a lista de "Ultimos Doadores"
</p> <br />

<div id='Procedimentos'/>  
<h2 align = "center">Procedimentos para iniciar a aplicação</h2>

Instalação do [node.js](https://nodejs.org/pt-br/download/ "node.js")  = Fazer o download e seguir os procedimentos de instalação.

<p align = "justify"> Iniciar o servidor: Entrar com o comando "npm start" no terminal (CTRL + ') do vscode (CTRL + C para fechar o servidor).
</p>

<p align = "justify"> Configurar o banco de dados: Editar os parametros de configuração do banco de dados no arquivo sever.js. O banco de dados deve conter as tabelas "name", "email" e "blood" respectivamente sendo todos do tipo "text" e todas não devem receber valores nulos.
</p>

![](https://i.imgur.com/jxvFqay.png)
- user: Preencher com o usuário do banco de dados <br/>
- password: Preencher com a senha do banco de dados <br/>
- host: Preencher com o endereço do host<br/>
- port: Preencher com a porta da conexão <br/>
- database: Preencher com o nome do banco de dados <br/>

