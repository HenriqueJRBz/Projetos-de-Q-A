# 🧪 Projeto de QA – Testes de API (ShopSmart / FakeStore API)

## 📌 Sobre o Projeto
Este projeto tem como objetivo demonstrar habilidades práticas na área de **QA / Tester**, com foco em **testes de API REST**. Os testes foram realizados sobre uma **API fictícia de e-commerce**, simulando cenários reais do mercado.

A API utilizada foi a **FakeStore API**, amplamente usada para estudos e treinamentos de testes de software.

🔗 API base utilizada: https://fakestoreapi.com

---

## 🎯 Objetivos
- Validar endpoints REST de um sistema fictício de e-commerce
- Praticar testes funcionais de API
- Aplicar conceitos de QA utilizados no mercado
- Criar um projeto profissional para portfólio no GitHub

---

## 🧠 Escopo de Testes
Os testes cobrem as seguintes funcionalidades:

- 📦 Listagem de produtos
- 🔍 Consulta de produto por ID
- 👤 Criação de usuários
- 🔐 Autenticação (login)
- 🛒 Criação de carrinho
- ❌ Validações de erros (IDs inexistentes, login inválido, etc.)

---

## 🧪 Tipos de Testes Realizados
- Testes funcionais de API
- Testes positivos e negativos
- Validação de status code
- Validação de contrato da resposta (JSON)
- Validação de regras de negócio

---

## 🛠️ Ferramentas Utilizadas
- **Postman** – Testes manuais de API
- **Newman** – Execução automatizada da coleção Postman
- **Python** – Automação de testes
- **Pytest** – Framework de testes
- **Git / GitHub** – Versionamento e portfólio

---

## 📂 Estrutura do Projeto
```text
qa-api-project/
│
├── postman/
│   └── ShopSmart.postman_collection.json
│
├── tests/
│   ├── test_login.py
│   ├── test_products.py
│   └── test_carts.py
│
├── README.md
└── requirements.txt
```

---

## 🔗 Principais Endpoints Testados

### 📦 Produtos
- `GET /products`
- `GET /products/{id}`

### 👤 Usuários
- `POST /users`

### 🔐 Autenticação
- `POST /auth/login`

### 🛒 Carrinho
- `POST /carts`

---

## ▶️ Como Executar os Testes

### 🔹 Testes Manuais (Postman)
1. Importar a coleção localizada na pasta `postman/`
2. Configurar a variável de ambiente com a URL base da API
3. Executar os endpoints manualmente

### 🔹 Testes Automatizados (Python)

1. Clonar o repositório:
```bash
git clone https://github.com/seu-usuario/qa-api-project.git
```

2. Instalar dependências:
```bash
pip install -r requirements.txt
```

3. Executar os testes:
```bash
pytest
```

---

## 📄 Exemplos de Casos de Teste

**CT-API-01 – Listar produtos**
- Método: GET
- Endpoint: /products
- Resultado esperado: Status 200 e lista de produtos válida

**CT-API-02 – Login inválido**
- Método: POST
- Endpoint: /auth/login
- Resultado esperado: Status 401

---

## 📈 Resultados Esperados
- APIs respondendo conforme esperado
- Erros tratados corretamente
- Contrato da API respeitado

---

## 👨‍💻 Autor
Projeto desenvolvido para fins de estudo e portfólio na área de **Qualidade de Software (QA / Tester)**.

---

## 🚀 Próximos Passos
- Adicionar testes de contrato com JSON Schema
- Integrar com CI/CD (GitHub Actions)
- Relatórios automatizados de testes
- Testes de performance (JMeter / k6)

---

📌 *Projeto fictício sem fins comerciais, utilizado apenas para aprendizado.*

