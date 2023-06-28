# WACAD012 - Contêineres

## Etapas de inicialização dos serviços
1) De antemão, você deve ter instalado o [Docker](https://docs.docker.com/get-docker/) e o [Docker Compose]( https://docs.docker.com/compose/install/);
2) Baixe e descompacte a pasta do projeto (WACAD012-conteineres). Nela você encontrará a seguinte estrutura:
    * ``webacademy-livros-backend`` - pasta com o código fonte do back-end;
    * ``webacademy-livros-frontend`` - pasta com o código fonte do front-end;
    * ``docker-composer.yml`` - arquivo de configuração de construção dos contêineres.
3) Através do seu terminal, acesse a pasta raíz do projeto (WACAD012-conteineres) e execute o seguinte comando para iniciar os contêineres do projeto: ``docker-compose up``. Os contêineres serão construídos e iniciados com base nas configurações definidas no arquivo ``docker-compose.yml``.
4) Após a execução dos contêineres, por meio do comando citado anteriomente, as URLs do projeto estarão disponíveis para serem acessadas.
    * Front-end: http://localhost:8000
    * Back-end: http://localhost:4444
    * phpMyAdmin: http://localhost:8080
5) Por fim, caso queira encerrar e remover os contêineres inicializados, basta executar o segunite comando: ``docker-compose down``. Já para inicializar novamente os contêineres, siga o passo 3.
