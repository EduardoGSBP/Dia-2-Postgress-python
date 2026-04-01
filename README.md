# 🚀 Data Pipeline com Python, SQLAlchemy e PostgreSQL

Pipeline de dados desenvolvido com foco em **engenharia de dados aplicada**, abordando desde a ingestão até a persistência eficiente em banco relacional, com implementação de **cargas incrementais** e manipulação de múltiplos formatos de dados.

---

## 📖 Visão Geral

Este projeto simula um cenário real de engenharia de dados, onde é necessário:

- Integrar diferentes fontes de dados
- Garantir eficiência na carga (evitando reprocessamento desnecessário)
- Trabalhar com dados em múltiplos formatos
- Estruturar um pipeline organizado, escalável e reutilizável

A solução foi construída utilizando **Python + PostgreSQL**, com abstração de acesso ao banco via **SQLAlchemy**.

---

## 🎯 Objetivos do Projeto

- Desenvolver um pipeline de dados robusto e reutilizável  
- Implementar estratégias de **carga incremental**  
- Integrar consultas SQL ao fluxo em Python  
- Trabalhar com diferentes formatos de dados (entrada e saída)  
- Aplicar boas práticas de organização e versionamento  

---

## 🧰 Stack Tecnológica

- **Python** (Pandas)
- **SQLAlchemy**
- **PostgreSQL**
- **SQL**

---

## ⚙️ Principais Funcionalidades

### 🔗 Conexão com Banco de Dados

- Conexão com PostgreSQL via SQLAlchemy  
- Configuração reutilizável  
- Estrutura pronta para expansão  

---

### 🔄 Carga Incremental de Dados

- Carga incremental baseada em **ano**  
- Refatoração do código para reutilização  
- Carga incremental dos **últimos 3 meses**  
- Otimização de performance e redução de reprocessamento  

---

### 📥 Integração SQL + Python

- Execução de queries SQL dentro do Python  
- Importação de arquivos `.sql`  
- Conversão para DataFrames  

---

### 💾 Manipulação de Dados

**Leitura:**
- JSON  
- CSV  
- Parquet  
- Excel  

**Escrita:**
- JSON  
- CSV  
- Parquet  
- Excel  
