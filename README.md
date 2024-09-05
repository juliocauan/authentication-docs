# Autenticação e Autorização API - Documentação

![youshallnotpass](https://github.com/juliocauan/authentication-server/assets/84354526/e4d27e22-8a5f-4d74-aacc-b95119852c10)

## 📖 Descrição

Esta é a documentação de uma API Rest para autenticação e autorização de usuários. Limitando o acesso do usuário apenas ao que foi especificamente atribuído a ele.

Esta API foi desenvolvida como um desafio pessoal para aprender diferentes áreas de desenvolvimento, que são:
- Cíber segurança
- Desenvolvimento Web com Spring Boot
- CI/CD
- Administrador de Banco de Dados (DBA)
- Políticas de Segurança e Retenção de Dados
- Gerenciamento de tokens
- Registro e Auditoria
- Integração com Sistemas de Identidade

## 🛠️ Funcionalidades
**Armazenamento de dados do usuário**
   - Armazena com segurança os dados do usuário, incluindo senhas criptografadas e funções associadas.

**Autenticação de usuário com JWT**
   - Fornece autenticação do usuário, gerando JSON Web Tokens (JWT) após login bem-sucedido para acesso seguro.

**Recurso "Esqueci a senha"**
   - Implementa uma funcionalidade segura "Esqueci minha senha" para que os usuários redefinam suas senhas.

**Gerenciamento de funções administrativas**
   - Permite que os administradores atualizem as funções dos usuários para um controle de acesso eficaz.

Para ver todas as descrições de endpoints, visite a [página Swagger(OpenAPI)](https://app.swaggerhub.com/apis/juliocauan/authentication/1.5.x-oas3)

## 🔮 Futuras implementações

1. Políticas extras de segurança
   - Bloqueio de conta após tentativas de login malsucedidas
   - Verificação de e-mail ao registrar usuário

2. Autenticação multifator

3. Autenticação via Google

4. Front-End responsivo desenvolvido em Angular

## 📡 Tecnologias utilizadas 
<div align="center">
  <img align="left" alt="OpenAPI (Swagger)" title="OpenAPI (Swagger)" height="30" width="30" src="https://avatars.githubusercontent.com/u/37325267?s=200&v=4">
</div>
<br/>

## 🔎 Status do Projeto

![Status Badge](https://img.shields.io/badge/status-development-green)
<br/>

Para executar essa API localmente, visite [Authentication API Server](https://github.com/juliocauan/authentication-server).