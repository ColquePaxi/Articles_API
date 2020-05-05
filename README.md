# PROJETO: ARTICLES API (RAILS) 
---
Se você se interessa em aprender o básico sobre backend utilizando Ruby on Rails e PostgreSQL, seja bem-vindo(a) a essa tutorial.
Apesar de ser básico, aqui você poderá aprender um pouco sobre a estrutura do Rails e também sobre alguns aspectos de segurança.
 
  
## INSTALANDO E PREPARANDO O POSTGRESQL PARA SERVIR AO BACK-END
---
- [ ] Instalação
- [ ] Ver se o Postgres está rodando (se o serviço está ativo)
- [ ] Criar um usuário com permissão de root para conectar ao banco de dados
- [ ] Ver se a porta está ok (instalar antes:> apt-get install nmap)
- [ ] Conhecer as facilidades do pgAdmin (subir interface gráfica via Área de Aplicativos Linux)  

## DESENVOLVENDO A API E CONECTANDO-A AO POSTGRES
---
- [ ] Setup
  - [ ] Criar o scaffold do projeto
  - [ ] Criar o banco de dados da API
  - [ ] Alterar a senha do usuário que vai conectar o banco de dados
  - [ ] Planeja a conexão com o banco de dados que vamos usar na API

- [ ] Desenvolvimento
  - [ ] Adicionar a dependência do Postgres no arquivo GemFile
  - [ ] Configura a conexão com o banco de dados que vamos usar na API
  - [ ] Criar o model da API
  - [ ] Migrar o model para o banco de dados
  - [ ] Ver se foi migrada
  - [ ] Validar campos para serem obrigatórios na API
  - [ ] Popular tabela com dados FAKE
    - [ ] Editar arquivo GemFile
    - [ ] Instalar a dependência
    - [ ] Gerar 50 artigos fake
    - [ ] Executar o comando para popular o banco de dados
    - [ ] Verificar se foi populado
  - [ ] Criar estrutura das rotas de nossa API
    - [ ] Editar o arquivo config/routes.rb
    - [ ] Gerar as rotas com base as definições no routes.rb
    - [ ] Subir o servidor
    - [ ] Acessar o servidor via browser
  - [ ] Criar os Controllers da nossa API
    - [ ] Criar os diretórios pata versionar a API
    - [ ] Método index
      - [ ] Criar um arquivo controller específico para a v1 da API chamado articles_controller.rb
      - [ ] Usar o Postman para testar o acesso à rota (GET)
    - [ ] Método show
      - [ ] Criar esse novo método em articles_controller.rb p/ listar um único artigo (id param)
      - [ ] Usar o Postman para testar o acesso à rota (GET)
    - [ ] Método create
      - [ ] Criar esse novo método dentro do articles_controller.rb para criar um novo artigo
        - [ ] def create e def articles_params
      - [ ] Usar o Postman para testar o acesso à rota (POST)
        - [ ] id na URL 
        - [ ] Parâmetros do header 
        - [ ] Parâmetros do body 
    - [ ] Método destroy
      - [ ] Criar esse novo método dentro do articles_controller.rb para excluir (deletar) um artigo
      - [ ] Usar o Postman para testar o acesso à rota (DELETE)
    - [ ] Método update
      - [ ] Criar esse novo método dentro do articles_controller.rb para alterar/atualizar um artigo
        - [ ] def create e def articles_params
      - [ ] Usar o Postman para testar o acesso à rota (POST)
        - [ ] id na URL 
        - [ ] Parâmetros do header 
        - [ ] Parâmetros do body 

## APLICANDO A SEGURANÇA BÁSICA NA API
---
- [ ] Rack-CORS
- [ ] Rack-Attack
- [ ] Devise