README oficial do repositório SGHSS-VidaPlus# SGHSS – VidaPlus

Sistema de Gestão Hospitalar e de Serviços de Saúde

## 📌 Sobre o projeto

O **VidaPlus** é um Sistema de Gestão Hospitalar e de Serviços de Saúde (SGHSS), desenvolvido como projeto acadêmico com o objetivo de aplicar conceitos de análise, modelagem, desenvolvimento e testes de sistemas computacionais.

O sistema permite o gerenciamento de usuários, pacientes e consultas médicas, oferecendo uma solução simples, funcional e segura para simular um ambiente hospitalar real.

Este projeto foi desenvolvido utilizando arquitetura em camadas e padrão de API REST.

---

## 🎯 Funcionalidades

✅ Cadastro e autenticação de usuários (JWT)
✅ Cadastro de pacientes
✅ Agendamento de consultas
✅ Listagem de pacientes
✅ Listagem de consultas
✅ Controle de acesso
✅ Segurança de dados (bcrypt + JWT)

---

## 🛠️ Tecnologias Utilizadas

* Python 3.x
* Flask
* Flask SQLAlchemy
* Flask JWT Extended
* SQLite
* HTML / CSS / JavaScript (Front-end básico)
* Postman (testes)
* Git / GitHub (versionamento)

---

## 📁 Estrutura do Projeto

```
SGHSS-VidaPlus/
│
├── src/
│   └── app.py
│
├── tests/
│   └── test_endpoints.py
│
├── docs/
│   └── swagger.json
│
├── requirements.txt
├── README.md
└── database.db
```

---

## 🚀 Como executar o projeto

### 1️⃣ Clonar o repositório

```bash
git clone https://github.com/seunome/SGHSS-VidaPlus.git
cd SGHSS-VidaPlus
```

### 2️⃣ Criar ambiente virtual (opcional)

```bash
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate    # Windows
```

### 3️⃣ Instalar dependências

```bash
pip install -r requirements.txt
```

### 4️⃣ Executar a aplicação

```bash
python src/app.py
```

O servidor será iniciado em:

```
http://localhost:5000
```

---

## 🔑 Principais Endpoints

### Cadastro de usuário

```
POST /auth/register
```

### Login

```
POST /auth/login
```

### Criar paciente

```
POST /pacientes
```

### Listar pacientes

```
GET /pacientes
```

### Agendar consulta

```
POST /consultas
```

### Listar consultas

```
GET /consultas
```

> ⚠️ A maioria dos endpoints requer autenticação via **Bearer Token (JWT)**.

---

## 🔐 Segurança

O projeto utiliza:

* JWT (JSON Web Token) para autenticação
* Bcrypt para criptografia de senhas
* Estrutura preparada para HTTPS em produção
* Controle de acesso por perfil

Atendendo às diretrizes da **LGPD (Lei Geral de Proteção de Dados)**.

---

## 🧪 Testes

Os testes foram realizados via:

* Postman (requisições manuais e automatizadas)
* Pytest (estrutura pronta)
* Testes de integração

Todos os principais fluxos foram validados com sucesso ✅

---

## 📘 Documentação

O código completo está neste repositório, enquanto o **relatório técnico completo em PDF** contém:

* Introdução
* Requisitos
* UML e DER
* Arquitetura
* Plano de Testes
* Conclusão
* Link deste repositório (GitHub)

---

## 👨‍🎓 Autor

Aluno: Samuell Trabulsi Tavares 
Curso: ANÁLISE E DESENVOLVIMENTO DE SISTEMAS 
Instituição: UNINTER
Semestre: 2025/1

---

## ✅ Status do projeto

✔ Concluído
✔ Funcional
✔ Pronto para avaliação
✔ Pronto para entrega
