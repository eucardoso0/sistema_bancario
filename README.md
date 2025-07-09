# 🏦 Sistema Bancário — Projeto de Análise de Dados com Python + MySQL + Power BI

Este projeto simula a construção de um sistema bancário com foco em extração, tratamento e visualização de dados. A base de dados foi criada manualmente no MySQL, manipulada com Python e visualizada com Power BI.

---

## 📌 Etapas do Projeto

### 1. 🛠️ Modelagem e Criação do Banco de Dados (MySQL)
- O banco `sistema_bancario` foi criado manualmente no MySQL
- Tabelas criadas:
  - `clientes` — dados pessoais
  - `contas` — tipo, saldo e limite
  - `transacoes` — depósitos, saques e transferências
  - `emprestimos` — valor, status e parcelas
- As tabelas foram populadas com dados simulados (sem erros)

---

### 2. 🔄 Extração e Transformação (Python)

- Conexão com o banco via `mysql.connector`
- Exportação das tabelas individuais para `.csv`
- Criação de uma tabela unificada via `JOIN`
- Tratamentos aplicados:
  - Conversão de datas
  - Cálculo da idade dos clientes
  - Extração de ano e mês das transações
  - Classificação de valores (`categoria_valor`)


---

### 3. 📊 Análise e Visualização no Power BI

No Power BI, foi realizada a importação dos dados tratados e criados os seguintes **gráficos e análises**:

- **💳 Total de Empréstimos por Status**  
- **📈 Valor Total de Empréstimos por Quantidade de Parcelas**
- **🏦 Tipos de Conta (Pizza)**
- **💸 Transações por Tipo (Horizontal)**
- **📋 Lista de Clientes com CPF e Saldo**

## 🧰 Tecnologias Utilizadas

| Ferramenta | Uso |
|------------|-----|
| **MySQL** | Modelagem e armazenamento dos dados |
| **Python + Pandas** | Extração, transformação e exportação |
| **Power BI** | Visualização interativa |
| **Git + GitHub** | Versionamento e documentação |

---
## 📎 Licença

Projeto livre para fins educacionais.

