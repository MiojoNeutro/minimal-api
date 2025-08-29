# 📌 API em C# - Desafio DIO

Este projeto é uma **réplica de API** desenvolvida em **C# com .NET**, criada para atender ao **desafio de projeto da Digital Innovation One (DIO)**.  
O objetivo foi praticar conceitos de desenvolvimento de APIs RESTful utilizando boas práticas e recursos da linguagem.

---

## 🚀 Tecnologias Utilizadas
- **C#**  
- **.NET 6/7 (ajustar de acordo com a versão usada)**  
- **Entity Framework Core** (se aplicável)  
- **Swagger** para documentação  

---

## 📂 Estrutura do Projeto

- **Api/** → Projeto principal da API
  - `Dominio/` → Entidades, DTOs, Enums, Interfaces e Serviços de domínio
  - `Infraestrutura/` → Configuração e persistência de dados (DbContext, etc.)
  - `Migrations/` → Migrações do Entity Framework Core
  - `Properties/` → Configurações do projeto
  - `Program.cs` → Arquivo principal que inicia a aplicação
  - `Startup.cs` → Configuração dos serviços, middlewares e rotas
  - `appsettings.json` → Configurações da aplicação
  - `appsettings.Development.json` → Configurações específicas do ambiente de desenvolvimento
  - `minimal-api.csproj` → Arquivo de configuração do projeto

- **Test/** → Projeto de testes automatizados
  - `Domain/` → Testes relacionados às regras de negócio
  - `Helpers/` → Classes auxiliares para os testes
  - `Mocks/` → Objetos mockados para cenários de teste
  - `Requests/` → Estruturas de requisições usadas nos testes
  - `Test.csproj` → Arquivo de configuração do projeto de testes

- `.gitignore` → Arquivo para ignorar arquivos/pastas no versionamento  
- `minimal-api.sln` → Arquivo da solução que agrupa os projetos  


---

## ⚙️ Como Executar
1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   
Acesse a pasta do projeto:
cd nome-do-projeto

Restaure as dependências:
dotnet restore

Execute a aplicação:
dotnet run

Acesse a documentação no navegador:
https://localhost:5001/swagger

📌 Funcionalidades
 CRUD de entidades principais (listar, buscar, criar, atualizar, excluir)

 Documentação interativa com Swagger

 Integração com banco de dados (se aplicável)

🏆 Objetivo do Desafio
Este projeto foi feito para consolidar os aprendizados do curso da DIO, replicando a API proposta e entendendo na prática como estruturar uma aplicação back-end moderna em .NET.

👨‍💻 Autor
https://github.com/Didox
Replicado por Erick Santos Alves
