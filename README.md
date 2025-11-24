# 📊 ETL - Students Performance

Este projeto implementa um pipeline completo de **ETL (Extract, Transform, Load)** para análise de desempenho de alunos. Ele faz extração de dados brutos a partir de um arquivo CSV, aplica transformações inteligentes (incluindo normalização, cálculo de média final, classificação e insights automatizados) e salva os resultados em múltiplos formatos.

---

## 🚀 Objetivo do Projeto

Demonstrar habilidades práticas em engenharia de dados utilizando Python e Pandas por meio da construção de um pipeline ETL realista e totalmente funcional, ideal para portfólio e entrevistas técnicas.

---

## 🧠 Tecnologias Utilizadas

* Python 3
* Pandas
* SQLite
* Jupyter Notebook

---

## 📁 Estrutura do Projeto

```
etl-students-performance/
│── data/
│   ├── students_raw.csv
│── output/
│   ├── students_processed.csv
│   ├── students.db
│── src/
│   ├── etl_pipeline.ipynb
│── README.md
```

---

## 🔍 Etapas do Pipeline

### 1️⃣ Extract — Extração dos Dados

O projeto lê um arquivo CSV contendo:

* nome
* disciplina
* média parcial
* faltas

### 2️⃣ Transform — Transformação dos Dados

As transformações incluem:

* Normalização dos nomes
* Tratamento de valores faltantes
* Cálculo da média final
* Classificação do aluno (Aprovado, Recuperação, Reprovado)
* Geração de insights automáticos, como alerta de faltas

### 3️⃣ Load — Carregamento dos Dados

Os dados transformados são exportados para:

* Um arquivo CSV final (`students_processed.csv`)
* Um banco de dados SQLite (`students.db`)

---

## 📌 Como Executar

1. Clone este repositório:

```
git clone https://github.com/seuusuario/etl-students-performance.git
```

2. Instale as dependências:

```
pip install pandas
```

3. Abra o notebook em `src/etl_pipeline.ipynb` e execute as células.

---

## 📈 Resultados

* Pipeline ETL funcional
* Dados limpos e enriquecidos
* Banco de dados pronto para consultas SQL
* Excelente material para demonstrar domínio em pipelines de dados

---

## 🤝 Contribuições

Sugestões e melhorias são sempre bem-vindas!

---

## 📝 Licença

Este projeto está sob a licença MIT.
