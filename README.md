# NestJS + Keycloak

Nesse exemplo vamos utilizar essa ferramenta **Keycloak** para gerenciar
todas as permissões e autenticações.

## Requisito

- Docker e Docker Compose
- NodeJS
- NestJS
- Keycloak

## Inicializar

```bash
docker-compose up
```

## Procedimento

Open `http://localhost:8080/auth` no seu navegador.
  
Para obter mais detalhes, consulte a [documentação do Keycloak](https://www.keycloak.org/documentation.html).

1) Criar um novo **REALME** de nome **MRDS**
    ![image](./.img/2021-09-09-15-12-26.png)
2) Criar um usuário exemplo1@exemplo.com
    ![image](./.img/2021-09-09-15-12-48.png)
3) Adicionar um Client: **nest**
    ![image](./.img/2021-09-09-15-05-04.png)
  
    Selecionar *Access Type* : confidential
