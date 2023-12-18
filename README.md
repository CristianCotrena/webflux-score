<h1 align="center">FormaNT - API Web Flux Score</h1>

FormaNT - API Web Flux Score é uma aplicação web baseada em Java que permite a um utilizador registar pontuações semelhantes à uma maquina de fliperama. A API é desenvolvida no formato web flux de programação reativa.

<hr/>

# Aplicação

- Sistema de Edição/Atualização: pode-se adicionar, editar e remover as pontuações de jogadores, informando o nome do jogador, a pontuação e o nome do jogo.

<hr/>

# CRUD:

- Método POST
- Método PUT
- Método DELETE
- Método GET - listar todas as pontuações
- Método GET - listar uma pontuação de um jogador
- Método GET - listar o top 5 de um jogo
- Método GET - listar todas as pontuações de um jogador

<hr/>

# Tecnologia

FormaNT - API Web Flux Score é construido usando as seguintes tecnologias:

BACKEND:
- Java: versão 17;
- Mongo DB Compas: 1.40.4;
- Spring Boot: versão 3.1.3;

<hr/>

# Como executar o projeto

## Passo 1: Baixar e extrair o código

Primeiramente, baixe o código do website e extraia o arquivo ZIP para uma pasta no seu sistema local.

## Passo 2: Faça as configurações necessárias

### Configurar o banco de dados
Esta aplicação usa o Mongo DB como DB rodando em um sistema local, mas que precisa ser logado à uma DB na nuvem.
Passo a passo:
    - instale o Mongo Db Compass e crie uma conexão 
    - a conexão deve ser com a seguinte url: mongodb+srv://candiollimateus:<password>@cluster0.xhhgsb1.mongodb.net/
    - acesse "Advanced Connection Options" clique em "Authentication" e informe "Username" e "Password" e clieque em "Save" e depois "Connect"

🚨 NOTA: O banco de dados roda na porta 27017. A configuração realizada não informa a porta.

- USUARIO: candiollimateus
- SENHA: *************

## Passo 3: Execute seu projeto

Abra seu editor de código (Como o IntelliJ), navegue até o diretório do projeto e execute a aplicação.

<hr/>

# 🚨 Avisos Importantes

- 🚨 O Netty está configurado para rodar na porta 8080, então, além do PostgreSQL na porta 7502, certifique-se de que não tenha nenhum outro aplicativo rodando nesta porta (8080). Caso haja, faça as alterações necessárias (application.properties).
- 🚨 O projeto já vem com algumas dependências previamente instaladas. Caso seja necessário realizar alterações, lembre-se que o mesmo foi desenvolvido seguindo as configurações acima.