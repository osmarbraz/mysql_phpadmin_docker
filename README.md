# Docker Compose com MySQL e PHPAdmin

Docker Componse com as imagens do MySQL e PHPAdmin para uso em outras aplicações.

## Sobre o projeto
 - Utiliza o **Docker Compose** para definir e gerenciar o serviço do banco de dados e o phpadmin. 
 - Utiliza o **MySQL 8.4** como banco de dados da aplicação. 
 - A ferramenta **PHPMyAdmin 5.2.3** vem configurada no arquivo compose.yml.
 
## Docker
 - Utilizar o terminal do Windows Powershel em modo administrador.

### Para criar os conteiner e os serviços
 - ```docker compose up -d```

### Para verificar o serviço em execução
 - ```docker compose ps```

### Parar o serviço
 - ```docker compose down -v```

### Remover a imagem
 - ```docker compose down --rmi all```

### Abra o PHPAdmin com o navegador em:
 - http://localhost:88/

## Arquivos

- Dockerfile - Arquivo de configuração do Docker.
- compose.yml - Arquivo de configuração da composição do Docker.

