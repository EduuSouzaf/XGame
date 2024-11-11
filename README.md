# Projeto de API - Arquitetura Baseada em DDD

Este projeto é uma API desenvolvida com foco em uma arquitetura robusta e modular, baseada nos princípios do **Domain-Driven Design (DDD)**. Foi criada para auxiliar no aprendizado e prática de técnicas avançadas de desenvolvimento de APIs, incluindo segurança, mensageria e documentação automática.

## Objetivo do Projeto

O propósito desta API é ensinar a criar uma aplicação voltada ao domínio, aplicando conceitos fundamentais de DDD. A API foi projetada com práticas que aumentam a legibilidade e manutenção do código, utilizando **Entity Framework**, **Swagger** para documentação, e compactação de respostas para otimizar o tráfego de dados.

## Funcionalidades

- Criação de uma aplicação focada no domínio
- Estruturação de **Entidades**, **Value Objects** e **Diagrama de Classes**
- Utilização de **NotificationPattern** para gerenciamento de mensagens e erros
- Desenvolvimento orientado a interfaces, promovendo baixo acoplamento
- Implementação de **Domain Services** e **Partner Repositories**
- Produtividade aprimorada com **Generics**
- Configuração de segurança e compactação das respostas da API
- Teste e documentação da API com **Swagger** e **Postman**

## Tecnologias Utilizadas

- **ASP.NET Core** - Framework principal para a criação de APIs RESTful
- **Entity Framework Core** - ORM para gestão de dados (Code First e Migrations)
- **NotificationPattern** - Para comunicação de erros e mensagens sem exceções
- **Swagger** - Geração automática de documentação da API
- **Postman** - Ferramenta de testes de API
- **C# e .NET Core** - Linguagem e ambiente de desenvolvimento
- **DDD (Domain-Driven Design)** - Arquitetura principal para organização do código

## Pré-requisitos

- **Visual Studio** (ou outro ambiente compatível com .NET Core)
- **.NET SDK 6.0+**
- **SQL Server** (ou outro banco de dados, conforme configuração do projeto)