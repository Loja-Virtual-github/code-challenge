![lojavirtual header](https://admin.lojavirtual.com.br/img/admin_loja/logo_loja_virtual.png)

# [LojaVirtual.com.br](https://www.lojavirtual.com.br/) - Teste prático de PHP

## Objetivo
O objetivo desta etapa é conhecer suas habilidades com PHP, MySQL e REST. Você deverá construir um CRUD simples de cadastro de usuário no formato de uma API REST.

A sua API deverá ter um único endpoint e todos os processos do CRUD deverão ser implementados utilizando os verbos HTTP.
```url
[GET] https://localhost:8000/user/{id} // Caso não seja informado o ID, deverá listar todos usuários cadastros
[POST] https://localhost:8000/user
[PUT] https://localhost:8000/user
[PUT] https://localhost:8000/user/:id
```

Os campos que deverão ser persistidos no banco de dados são:
- Nome
- Email
- Data de nascimento
- Telefone
- CPF
- Endereco (logradouro, bairro, cidade, estado, cep)
    `Para o endereço, a única entrada deverá ser o CEP, os outros campos deverão ser preenchidos utilizando a API do ViaCEP.`
- Data de cadastro (Controlado pelo sistema)
- Data de atualização (Controlado pelo sistema)

## Problema
### Cadastro de usuário
Você deverá criar um CRUD simples em formato de API de cadastro de usuário. 
A aplicação **não** precisa ter uma interface visual, somente a API.

Os campos de entrada serão:


### Requisitos obrigatórios
- Deverá ser implementado utilizando as especificações REST
- A API deverá aceitar os formatos **json** e **multipart/form-data**
- A aplicação deverá ter um controle de acesso de por Token
- A aplicação deverá ser disponibilizada no GitHub com todas instruções necessárias para rodá-la no README.md.

## Diferenciais
- Utilização de patterns
- PSR's
- Desenvolvimento de testes unitários
- Docker

## ViaCEP
[ViaCEP](https://viacep.com.br/)

## Boa sorte! ;)
