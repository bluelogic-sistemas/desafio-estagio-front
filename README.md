![Desafio técnico | Estágio TI](https://res.cloudinary.com/das1rnjvi/image/upload/v1662943721/bluelogic/capa-desafio_ccpumj.png)

Conheça mais sobre a **[Bluelogic](https://www.bluelogic.com.br/)**

## Orientações

- Crie um repositório no seu GitHub.
- Faça seus commits no seu repositório.
- Você poderá consultar o Google, Stackoverflow ou algum projeto particular na sua máquina.
- Dê uma olhada nos [Materiais úteis](#materiais-úteis).
- Fique tranquilo, respire, assim como você, também já passamos por essa etapa. Boa sorte! :)

## Como funciona o desafio

Para nossa primeira etapa de avaliação técnica, propomos um teste onde o candidato deve desenvolver uma API RESTFul, veja a seguir os requisitos obrigatórios do desenvolvimento.

Requisitos:

- Desenvolver CRUD de usuários (Criar, Listar, Atualizar e Deletar).
- Desenvolver um endpoint para realizar login.
- O Schema do usuário deve conter os seguintes campos (Nome, Idade, E-mail, Senha e tipos de usuário), os tipos de usuários possíveis são (ADMIN, CLIENTE).
- Desenvolver o processo de **autenticação** dos endpoints, somente o endpoint de cadastro de usuários e login devem ser públicos, os demais endpoints devem ficar protegidos.
- Documentação dos endpoints (Postman ou Insomnia) [como exportar](#materiais-úteis),adicionar os no projeto.
- Adicionar instruções de como executar o projeto.

### Sobre o ambiente da aplicação:

- Utilizar NodeJs e as linguagens JavaScript ou TypeScript para implementação do código de back-end.
- Utilizar Banco de dados MongoDB
- Utilizar para Authenticação JWT.

### Payload

Faça uma **proposta** :heart: de payload, se preferir, temos um exemplo aqui:

GET /users

```json
{
    "message": "Usuários listados com sucesso!"
    "data": {
       "nome" : "Dev",
       "idade" : 20
    }
}
```

POST /users

```json
{
   "nome" : "Dev",
   "idade" : 20
}
```


## Como entregar o desafio

O desafio deve ser entregue no prazo máximo de **2 dias**, considerando que o prazo começa um dia depois do momento em que lhe enviamos as instruções.
Enviar para o e-mail **desenvolvimento@bluelogic.com.br** com o assunto `Desafio Técnico - [NOME DA CANDIDATO(A)]`.

*No Corpo do E-mail com o link do repositório do desafio*

>Seu Nome
>
>Link do repositório

#### Como pré-requisito, o projeto não deve conter nenhum problema para executar a aplicação.

Caso tenha qualquer problema e não puder iniciar o desafio no prazo estabelecido, ou tiver dúvidas e dificuldades durante o processo, ou mesmo precisar de um feedback sobre sua avaliação, nos envie um e-mail e estaremos prontos para ajudar :)

## O que será um Diferencial :heart_eyes:
- Uso framework NestJs (https://nestjs.com/)
- Uso de Docker
- Interface web simples para mostrar as informações

## Materiais úteis
- https://docs.nestjs.com/
- https://wanago.io/2021/08/16/api-nestjs-mongodb/
- https://dev.to/carlomigueldy/building-a-restful-api-with-nestjs-and-mongodb-mongoose-2165
- https://www.sohamkamani.com/nodejs/jwt-authentication
- https://docs.insomnia.rest/insomnia/import-export-data
- https://learning.postman.com/docs/getting-started/importing-and-exporting-data/

Boa sorte! 🏆 🏆
