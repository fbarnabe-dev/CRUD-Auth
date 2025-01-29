# CRUD-Auth

## 📌 Sobre o Projeto

Este projeto é uma aplicação **CRUD (Create, Read, Update, Delete)** com autenticação e autorização integradas. Ele fornece um exemplo prático de como gerenciar usuários, autenticação e operações de banco de dados utilizando tecnologias modernas.

## 🚀 Tecnologias Utilizadas

- **.NET Core** - Framework principal para desenvolvimento
- **Entity Framework Core** - ORM para manipulação de banco de dados
- **ASP.NET Identity** - Gerenciamento de usuários e autenticação
- **SQLite** - Banco de dados utilizado

## 📂 Estrutura do Projeto

```
CRUD-Auth/
│── Controllers/       # Controladores para gerenciar requisições HTTP
│── Models/            # Modelos de dados
│── Data/              # Configuração do banco de dados e migrações
│── Services/          # Serviços para lógica de negócio
│── Middleware/        # Middleware de autenticação
│── Program.cs         # Configuração e inicialização do app
│── appsettings.json   # Configurações da aplicação
```

## 🔑 Funcionalidades

✔️ Cadastro e login de usuários
✔️ Controle de acesso com roles
✔️ CRUD completo de entidades

## 🛠️ Como Executar o Projeto

### 1️⃣ Clonar o Repositório
```bash
git clone https://github.com/fbarnabe-dev/CRUD-Auth.git
cd CRUD-Auth
```

### 2️⃣ Configurar o Banco de Dados
Atualize o **appsettings.json** com a string de conexão correta.

```json
"ConnectionStrings": {
  "DefaultConnection": "Server=(localdb)\\mssqllocaldb;Database=CrudAuthDb;Trusted_Connection=True;"
}
```

Se estiver usando **Entity Framework Core**, aplique as migrações:
```bash
dotnet ef database update
```

### 3️⃣ Rodar a Aplicação
```bash
dotnet run
```

## ✨ Contribuição
Sinta-se à vontade para abrir **Issues** ou enviar **Pull Requests**!

---

Feito com ❤️ por [Felipe Barnabé](https://github.com/fbarnabe-dev) 🚀
