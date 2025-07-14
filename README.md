# 🛒 Microserviços para E-commerce com Docker

Este repositório contém uma aplicação de **e-commerce** composta por três **microserviços**: produtos, pedidos e pagamentos. Cada serviço é desenvolvido em uma linguagem diferente (**Node.js**, **Python** e **PHP**) e todos são orquestrados via **Docker Compose**, utilizando também **Redis** e **MySQL** como serviços auxiliares.

---

## 🧱 Descrição dos Serviços

- **api-produtos** (Node.js / Express):  
  Fornece uma lista de produtos disponíveis.

- **api-pedidos** (Python / Flask):  
  Cria pedidos, consulta produtos, armazena pedidos no MySQL e utiliza Redis para cache.

- **api-pagamentos** (PHP):  
  Processa pagamentos de pedidos existentes.

---

## 🚀 Como Executar

**Pré-requisitos:**

- [Docker](https://www.docker.com/)  
- [Docker Compose](https://docs.docker.com/compose/)

**Passos:**

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/ecommerce-microservices.git
cd ecommerce-microservices

# Suba os serviços
docker-compose up --build
```
## 🌐 Portas Disponíveis

- 🛍️ **Produtos**: [http://localhost:3001/products](http://localhost:3001/products)  
- 📦 **Pedidos**: [http://localhost:3002/order](http://localhost:3002/order)  
- 💳 **Pagamentos**: [http://localhost:3003/payment](http://localhost:3003/payment)

---

Desenvolvido com 💙 por Isabela
