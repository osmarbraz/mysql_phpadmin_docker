# Docker Compose com MySQL e PHPAdmin

Cria as imagens do MySQL e PHPAdmin para uso em outras aplicações.

## Sobre o projeto
 - Utiliza o **Docker Compose** para definir e gerenciar o serviço do banco de dados e o phpadmin. 
 - Utiliza o **MySQL 8.4** como banco de dados da aplicação. 
 - A ferramenta **PHPMyAdmin 5.2.3** vem configurada mas comentada no arquivo compose.yml.
 
## Docker
 - Utilizar o terminal do Windows Powershel em modo administrador.

### Para criar os conteiner e os serviços
 - ```docker compose up --build```

### Parar os serviços
 - ```docker compose down -v```

### Abra o navegador em:
 - http://localhost:88/

### Remover as imagens
 - ```docker compose down --rmi all```

## Arquivos

- *.png - Arquivos de imagens do README.md.
- Dockerfile - Arquivo de configuração do Docker.
- compose.yml - Arquivo de configuração da composição do Docker.

