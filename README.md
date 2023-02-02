<p align="center"> <img src="https://imgur.com/J3hD21O.png" alt="Javascript: criando requisições"> </p>

<hr>

<p align="center"> <img src="https://github.com/MonicaHillman/aluraplay-requisicoes/blob/main/img/logo.png" alt="Logo da Alura"> </p>
<p align="center">Página inicial e formulário de cadastro de vídeos da AluraPlay, uma plataforma de compartilhamento de vídeos.</p>

## Tecnologias utilizadas durante o curso
* Javascript
* NodeJS
* Json-server

## Tecnologias utilizadas no projeto
* HTML
* CSS

## Screenshots
![Screenshot da tela inicial do AluraPlay](https://imgur.com/aymxEsh.png)
![Screenshot da tela do formulário do AluraPlay](https://imgur.com/ShNADf2.png)

## Para inicializar
Você tem que escrever *npx json-server --watch db.json* no terminal

## O que aprendi?

### fetch()
Depois de inserir a url na função fetch vc pode colocar outro tipo de dado que é o *method*, esse método pode ser definido como `POST`, `DELETE` e `UPDATE`. Não precisa declarar o `GET` pois está implicito.

O *headers* nele vc pode colocar o tipo de conteudo `Content-type` que vai ser `application/json`.  

O *body* vc coloca o `JSON.stringify` que vai converter de json => string.

### Math.floor()
Transforma o resultado da função anterior (Math.random) em um número inteiro.