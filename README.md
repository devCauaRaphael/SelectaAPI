# 🚀 Selecta API — Backend da Plataforma de Vendas

![Banner do Projeto](https://via.placeholder.com/1000x250?text=Selecta+API)

A **Selecta API** é o backend completo de uma plataforma de vendas inspirada no Mercado Livre, construída em **ASP.NET Core** com **MySQL**. Toda a aplicação foi projetada pensando em escalabilidade, integração limpa com React e práticas profissionais de arquitetura.

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

## 📌 Avisos

- Todas as interfaces e controllers possuem **`summary` implementado**.  
- A arquitetura segue boas práticas de separação de responsabilidades.  
- A API pode ser facilmente adaptada para microserviços no futuro.  
- Documentação completa via **Swagger**.

---

## ▶️ Como executar o projeto

### 1️⃣ Clonar o repositório
```bash
git clone https://github.com/devCauaRaphael/SelectaAPI.git 
cd SelectaAPI

2️⃣ Configurar o appsettings.json
{
  "AWS": {
    "BucketName": "seu-bucket",
    "Region": "sa-east-1",
    "AccessKey": "sua-access-key",
    "SecretKey": "sua-secret-key"
  }
}

3️⃣ Restaurar dependências
dotnet restore

4️⃣ Rodar a API
dotnet run

5️⃣ Acessar o Swagger
https://localhost:7065/swagger/index.html

Sinta-se livre para enviar PRs, sugestões ou melhorias!
Esse projeto faz parte do meu TCC e continua evoluindo diariamente.

