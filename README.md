# Documentação do Projeto: Autenticação e Autorização com .NET 6

## Introdução
Este repositório contém um projeto que explora os conceitos de autenticação e autorização em aplicativos .NET. O objetivo é fornecer uma base sólida para implementar sistemas de login, gerenciamento de sessões e controle de acesso.

## Tecnologias Utilizadas
- **ASP.NET Core**: Framework para desenvolvimento de aplicativos web e APIs.
- **Identity Framework**: Biblioteca para gerenciamento de autenticação e autorização.
- **Entity Framework Core**: ORM (Object-Relational Mapping) para acesso a banco de dados.

## Funcionalidades
1. **Cadastro e Login de Usuários**:
   - Registro de usuários e autenticação de usuários.
   - Armazenamento seguro de senhas usando o Identity Framework.

2. **Validação do JWT**:
   - Implementação de Tokens Utilizando JWT para guardar e validar nossas criptografias.

3. **Verificação de Idade mínima para Login**:
   - Verificação da idade cadastrada pelo usuário para o login de 18 anos, caso não atendida não será autorizado.

## Configuração
1. **Clonando o Repositório**:

   git clone https://github.com/heroshg/auth-.net8.git


2. **Configurando o Banco de Dados**:
- Configure a conexão com o banco de dados no arquivo `appsettings.json`.
- Execute as migrações para criar as tabelas de usuário e roles:
  ```
  dotnet ef database update OU
  Update-Database no Console Nuget
  ```

3. **Executando o Projeto**:

dotnet run OU
CTRL + F5 no Visual Studio

