<p style="text-align: right"> 🇧🇷 / 🇺🇸 </p>

<p style="text-align: center">
[Introdução](#Introdução) | [Funcionamento](#Funcionamento) | [Procedimentos](#Procedimentos)
</p>

<div id='Introdução'/>  
<h1 style="text-align: center">_Introdução_</h1>
<p style="text-align: justify">
Aplicação criada a partir da Maratona Dev 3.0. No front-end temos a introdução da situação e o formulário para cadastrar um doador de sangue (Nome,e-mail e tipo sanguineo) e o back-end é responsável configurar um servidor e registrar os dados capturados no front-end em um banco de dados.
</p>

Inicial        |  Formulário
:-------------------------:|:-------------------------:
![](https://i.imgur.com/gkM9vZg.png)  |  ![](https://i.imgur.com/hvKsewO.png)|
<br /><br /><br /><br /><br />

<div id='Funcionamento'/>  
<h2 style="text-align: center">_Funcionamento_</h2>

<p style="text-align: justify">
O botão "Quero Ajudar" irá abrir o formulário. O formulário deve ser preenchido para que os dados sejam salvos no banco de dados e a lista de "Ultimos Doadores" seja atualizada com os respectivos dados do doador. Caso um ou mais dados sejam deixados em branco a pagina de erro será carregada avisando o usuário que "Todos os campos devem ser preenchidos." Neste caso nenhum dado será salvo no banco de dados e nada será adicionado a lista de "Ultimos Doadores"
</p> <br />

<div id='Procedimentos'/>  
<h2 style="text-align: center">_Procedimentos necessários para iniciar a aplicação_</h2>

<p style="text-align: justify"> Instalação do [node.js](https://nodejs.org/pt-br/download/ "node.js")  = Fazer o download e seguir os procedimentos de instalação.
</p>

<p style="text-align: justify" > Iniciar o servidor: Entrar com o comando "npm start" no terminal (CTRL + ') do vscode (CTRL + C para fechar o servidor).
</p>

<p style="text-align: justify"> Configurar o banco de dados: Editar os parametros de configuração do banco de dados no arquivo sever.js. O banco de dados deve conter as tabelas "name", "email" e "blood" respectivamente sendo todos do tipo "text" e todas não devem receber valores nulos.
</p>

![](https://i.imgur.com/jxvFqay.png)

- user: Preencher com o usuário do banco de dados
- password: Preencher com a senha do banco de dados 
- host: Preencher com o endereço do host
- port: Preencher com a porta da conexão 
- database: Preencher com o nome do banco de dados


