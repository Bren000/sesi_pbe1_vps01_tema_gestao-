# Gestão de Resíduos Sólidos - Back-end
Exemplo simples de back-end com armazenamento em arquivo JSON para cadastro e monitoramento de ocorrências de descarte irregular de resíduos sólidos utilizando operações CRUD.

## Tecnologias 
- Node.js
- JavaScript
- VsCode
- VsCode Thunder Client

## Passos para testar 
- 1. Clone este repositório
- 2. Abra o projeto no VsCode e em um terminal digite: 
```
npm install
node server.js
```

- 3. Teste as rotas utilizando a extensão Thunder Client.

- 4. Abra o arquivo ```client/index.html```  utilizando o navegador ou a extensão Live Server.

## Print dos testes e exemplo de requisições


GET - TODAS AS OCORRÊNCIAS <br>
![Get](./prints/get-todasasocorrenciaspng.png)

GET - BUSCAR POR ID <br>
![Get](./prints/getbuscarporid.png)

GET - BUSCAR POR LOCAL <br>
![Get](./prints/getbuscarporlocal.png)

GET - BUSCAR POR TIPO <br>
![Get](./prints/getbuscarportipo.png)

POST - CADASTRAR OCORRÊNCIA <br>
![Post](./prints/postcadastrarocorrencia.png)

PUT - ATUALIZAR OCORRÊNCIA <br>
![Create](./prints/putatualizarocorrencia.png)

DELETE - EXCLUIR OCORRÊNCIA <br>
![Delete](./prints/deleteexcluirocorrencia.png)

## Cliente 

Formulário <br>
![Cliente](./prints/site.png)

Resposta do Formulário <br>
![Resposta](./prints/envio.png)
