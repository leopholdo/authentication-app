
# Authentication APP

Este projeto visa demonstrar a implementação de um sistema de autenticação de usuários, permitindo o registro, login e comunicação com uma API de forma autenticada via Bearer token, além de demostrar a implementação da biblioteca Vuetify em conjunto com o VueJS com visual complexo e validações de dados pertinentes.

## Aviso importante

Este repositório é somente a parte do front-end do projeto. Para funcionar do modo esperado, deve-se executar também a API que se encontra neste repositório: https://github.com/leopholdo/authentication-api


## Funcionalidades

- **Registro de usuários** persistindo os dados em banco ou memória
- **Criptografia de password** com BCrypt
- **Validações de dados de usuários** em camadas diferentes
- **Autenticação de usuários**
- **Comunicação com API** de forma anônima e autenticada via Bearer token
- **Implementação de uma API segura** por CORS, autenticação e autorização com JWT e Bearer
## Stack utilizada

**Front-end:** VueJS e Vuetify

**Back-end:** ASP.NET Core 8

**Banco de dados:** PostgreSQL (opcional)


## Como usar

1. **Configuração do ambiente:**
- Clone e configure o repositório da API [que se encontra neste link](https://github.com/leopholdo/authentication-api);
- Clone este repositório;
- Instale as dependências necessárias:

**NPM**
```
npm install
```

**YARN**
```
 yarn install
```


3. **Execução do Projeto:**
**NPM**
```
npm run dev
```

**YARN**
```
 yarn dev
```
## Contribuindo

Contribuições são sempre bem-vindas!

Se você encontrar algum problema ou tiver sugestões, sinta-se à vontade para abrir uma [issue](https://github.com/leopholdo/authentication-app/issues/new) ou enviar um [pull request](https://github.com/leopholdo/authentication-app/pulls).