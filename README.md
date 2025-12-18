# 🚀 Selecta API — Backend da Plataforma de Vendas

A **Selecta API** é o backend completo de uma plataforma de vendas inspirada no Mercado Livre, construída em **ASP.NET Core** com **MySQL**. Toda a aplicação foi projetada pensando em escalabilidade, integração limpa com React e práticas profissionais de arquitetura.
    
🎥 Demonstração do projeto:  
https://youtu.be/w0WsiXkFmgM?si=kvHTewI93AHZH2K7
---

## ⚙️ Tecnologias Utilizadas
- **ASP.NET Core 8**
- **Entity Framework Core**
- **MySQL**
- **AutoMapper**
- **AWS S3** (upload de imagens)
- **Swagger**
- **DTOs + Services + Interfaces**
- **Injeção de dependência**
- **Arquitetura RESTful**

---


## 🎯 Objetivo

A Selecta API foi criada para:

- Gerenciar **clientes, produtos e vendas**.  
- Servir como backend de uma plataforma de anúncios e marketplace.  
- Permitir **upload de imagens** via AWS S3.  
- Integrar com um front-end em React.  
- Seguir padrões profissionais para utilização em **TCC**.

---

## ▶️ Como executar o projeto

### 1️⃣ Clonar o repositório
```bash
git clone https://github.com/devCauaRaphael/SelectaAPI.git 
cd SelectaAPI

2️⃣ Crie um arquivo .env e preencha as seguintes variaveis de ambiente:
AWS_REGION = sa-east-1
AWS_ACCESS_KEY_ID = suaAccessKey
AWS_SECRET_ACCESS_KEY = suaSecretKey
JWT_KEY = Zk9h8dU2mQwXrL9tPbN3sVy7cJk5aZx0RjWmFnTqYpBvHsKdLu1oE3Cg6Df4Sh7T

3️⃣ Restaurar dependências
dotnet restore

4️⃣ Rodar a API
dotnet run

5️⃣ Acessar o Swagger
https://localhost:7065/swagger/index.html

Container desativo por ultrapassar o limite do plano gratuito da Amazon S3
