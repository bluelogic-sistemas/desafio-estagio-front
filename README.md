![Desafio técnico | Estágio FrontEnd](https://res.cloudinary.com/das1rnjvi/image/upload/v1662943721/bluelogic/capa-desafio_ccpumj.png)

Conheça mais sobre a **[Bluelogic](https://www.bluelogic.com.br/)**

## Orientações

- Crie um repositório no seu GitHub.
- Faça seus commits no seu repositório.
- Você poderá consultar o Google, Stackoverflow ou algum projeto particular na sua máquina.
- Dê uma olhada nos [Materiais úteis](#materiais-úteis).
- Fique tranquilo, respire, assim como você, também já passamos por essa etapa. Boa sorte! :)

## Como funciona o desafio

Para nossa primeira etapa de avaliação técnica, propomos um teste onde o objetivo é compreender quais conhecimentos você já possui e sua desenvoltura diante a problemas ou tarefas que esteja se deparando pela primeira vez.


## 💬 Escopo do desafio

Desenvolver uma aplicação Front-end na linguagem/framework de sua preferência, tendo como requisito ser em SPA (single-page application) e atender os requisitos listados abaixo.

**Você deve seguir como base para o desenvolvimento do layout da aplicação o seguinte mockup:**
#### [ ► Mockup - Figma ]([https://www.figma.com/file/9rnzjWDSvwlENgQNwxfu28/GazinFilms?node-id=110%3A1881](https://www.figma.com/file/DIwSpshqBdTfvujx801ccs/Desafio-Front?node-id=0%3A1))

Com base no mockup do link acima você deve criar uma aplicação Front-end que consome a seguinte API : **[IMDb API](https://rapidapi.com/apidojo/api/imdb8/)**. Esta API é pública e tem dados de diversos filmes de todo o mundo. Para obter todas as informações sobre a API, pelo mesmo link você tem acesso a documentação da mesma.

## 💽 Requisitos

A aplicação deve ser componentizada, com os seguintes componentes obrigatórios:

- ***Header*** (Componente de cabeçalho);
- ***Footer*** (Componente de rodapé);
- ***Banner*** (Componente de banner com imagens recuperadas da API do IMBb);
- ***ListFilms*** (Componente de listagem de filmes com dados recuperados da API do IMBb);
- ***ListActors*** (Componente de listagem de atores com dados recuperados da API do IMBb);
- ***ListResults*** (Componente de listagem de filmes com dados recuperados da API do IMBb após um filtro aplicado via Front-End);
- ***Details*** (Componente de descrição da biografia/filmogragia/descrição de um filme ou ator com dados recuperados da API do IMBb).

A aplicação deve conter no mínimo as quatro páginas apresentadas no mockup com as seguintes rotas:

- ***/home ►*** Página incial da aplicação;
- ***/search ►*** Página que lista os filmes após serem filtrados via o campo de input presente no header;
- ***/movie-detail ►*** Página que exibe os detalhes de um filme selecionado;
- ***/actor-detail ►*** Página que exibe os dados de um ator selecionado.

A aplicação deve conter um campo de busca no header das páginas, que quando submetido renderiza a página `/search` contendo os filmes retornados da busca na API do IMDb.

⚠️ **O layout apresentado no Figma não precisa ser seguido 100% fiel, você pode implementar novas features, funcionalidades, campos, animações, etc... como bem desejar! Use sua criatividade com base no layout apresentado para nos surpreender, isso pode acabar contando mais pontos no seu desafio.** 😃

**Você também pode utilizar bibliotecas de componentes já existentes de sua escolha, como por exemplo MaterialUI, Tailwind, Bootstrap, etc..**


## Como entregar o desafio

O desafio deve ser entregue no prazo máximo de **5 dias**, considerando que o prazo começa um dia depois do momento em que lhe enviamos as instruções.
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
