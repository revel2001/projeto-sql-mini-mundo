# projeto-sql-mini-mundo# 
💻 Projeto SQL – Criação e Manipulação de Dados em Banco Relacional  
**Mini-mundo: Sistema de Vendas**

Este repositório contém a implementação completa de um banco de dados relacional baseado em um mini-mundo previamente modelado. Inclui scripts SQL de criação, manipulação e consulta, testados em MySQL Workbench (compatível com PostgreSQL mediante pequenas adaptações).

---

# 🎯 Objetivos do Projeto

### Taxonomia de Bloom — Nível Aplicar & Criar
- Aplicar comandos SQL (INSERT, SELECT, UPDATE, DELETE) em um banco real.
- Criar scripts completos, modularizados e versionados.

### Taxonomia de Fink
- **Aplicação:** uso de MySQL Workbench ou PGAdmin para execução real dos scripts.  
- **Integração:** junção entre modelagem lógica, restrições, normalização e DML.  
- **Aprendendo a aprender:** tratamento de erros SQL, depuração, mensagens do SGBD.

---

# 🛠️ Ambiente Utilizado

Você pode executar este projeto em:
- **MySQL Workbench (recomendado)**  
- **PostgreSQL + PGAdmin**

### Criando o banco:
```sql
CREATE DATABASE projeto_vendas;
USE projeto_vendas;
```

---

# 📂 Estrutura do Repositório

```
/projeto-sql-mini-mundo/
│
├── README.md
├── 01_create_tables.sql
├── 02_insert_data.sql
├── 03_select_queries.sql
├── 04_update_commands.sql
└── 05_delete_commands.sql
```

---

# 📄 Scripts Disponíveis

### 1. **01_create_tables.sql**
Criação das tabelas conforme o modelo lógico:
- cliente  
- produto  
- pedido  
- item_pedido  

### 2. **02_insert_data.sql**
Povoamento inicial com dados coerentes com o mini-mundo.

### 3. **03_select_queries.sql**
2–5 consultas SQL usando:
- SELECT
- WHERE
- ORDER BY
- JOIN
- LIMIT

### 4. **04_update_commands.sql**
Três atualizações (UPDATE) respeitando integridade e chaves.

### 5. **05_delete_commands.sql**
Três exclusões (DELETE) com condições.

---

# ▶️ Como Executar

1. Abra Workbench ou PGAdmin.
2. Crie o banco de dados:
   ```sql
   CREATE DATABASE projeto_vendas;
   USE projeto_vendas;
   ```
3. Execute **nesta ordem**:
   - 01_create_tables.sql  
   - 02_insert_data.sql  
   - 03_select_queries.sql  
   - 04_update_commands.sql  
   - 05_delete_commands.sql  

---

# ✔️ Requisitos Atendidos

- Scripts completos (INSERT, SELECT, UPDATE, DELETE)  
- Ambiente real de execução  
- Versionamento Git  
- Coerência com modelo lógico  
- README detalhado  
- Repositório funcional e público  

---
