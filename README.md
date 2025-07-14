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

Desenvolvido com 💙 por Isabela
