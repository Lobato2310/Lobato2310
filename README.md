# Olá, eu sou Lucas Lobato 👋

**Python | Dados | SQL | Análises e Gestão**

---

### 🎯 Objetivo Profissional

Atuar nas áreas de Dados. Meu foco é utilizar a combinação de **+5 anos na Gestão de Negócios e Operações Comerciais** com a **Tecnologia** para construir pipelines de dados defensivos, arquiteturas analíticas e soluções orientadas a IA que reduzam custos e tragam clareza decisória para os stakeholders.

---

### 👤 Sobre Mim & Trajetória

- 🎓 **Formação:** Bacharel em Ciência da Computação (último semestre).
- 💼 **Diferencial Comercial:** Atuação sólida em gestão de negócios e operações comerciais. Entendo o impacto financeiro de cada indicador e traduzo regras de negócio complexas em requisitos técnicos.
- 🛠️ **Foco Técnico:** Limpeza defensiva de dados ruidosos, pipeline ETL/ELT, modelagem preditiva, automação com Web Scraping e dashboards executivos.

---

### 🛠️ Tech Stack & Ferramentas

#### Linguagens & Manipulação de Dados
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Polars](https://img.shields.io/badge/Polars-CD7F32?style=for-the-badge&logo=polars&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

#### Engenharia, Bancos de Dados & ORM
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=for-the-badge&logo=duckdb&logoColor=black)
![Google BigQuery](https://img.shields.io/badge/Google_BigQuery-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71108?style=for-the-badge&logo=sqlalchemy&logoColor=white)

#### Machine Learning, IA & Automação
![Scikit-Learn](https://img.shields.io/badge/Scikit_Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=for-the-badge&logo=selenium&logoColor=white)
![Scrapy](https://img.shields.io/badge/Scrapy-60A839?style=for-the-badge&logo=scrapy&logoColor=white)
![BeautifulSoup](https://img.shields.io/badge/BeautifulSoup-00599C?style=for-the-badge&logo=python&logoColor=white)

#### Visualização de Dados & BI
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)

#### Ambiente & Ferramentas
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)

---

### 📌 Projetos em Destaque

#### 🛡️ [Data Quality Pipeline & Analytics para Fintech](https://github.com/Lobato2310/fintech_datascience)
* **Problema de Negócio:** Bases financeiras com **205.842 inconsistências** em 500.000 transações (datas em múltiplos formatos, ruídos de moeda e transações órfãs) gerando relatórios distorcidos.
* **Abordagem Técnica:** Implementação de um pipeline de **engenharia defensiva** em Python. Tratamento não-destrutivo aplicando *flags de inconsistência*, carga tipada no **PostgreSQL via SQLAlchemy 2.0** e execução de queries analíticas portáveis em **DuckDB**.
* **Resultado:** Preservação de 100% da volumetria dos dados, correção de bugs graves em renda de clientes e construção de dashboards executivos em Plotly imunes a dados inconsistentes.

#### 🏥 [Predição de Readmissão Hospitalar](https://github.com/Lobato2310/datascience_playground)
* **Problema de Negócio:** Readmissões hospitalares não planejadas dentro de 30 dias aumentam os custos de saúde e sobrecarregam leitos de UTI.
* **Abordagem Técnica:** Pipeline de Machine Learning em **Scikit-Learn** treinado com dados clínicos. Otimização de hiperparâmetros via `RandomizedSearchCV` focando no equilíbrio entre Precisão e Recall (**F1-Score**) para minimizar falsos negativos.
* **Resultado:** Aplicação implantada e rodando no **Streamlit Cloud**, permitindo a triagem em tempo real de pacientes com alto risco de retorno para planejamento de alta médica.

#### 📊 [Análise de Inadimplência no Brasil](https://github.com/Lobato2310/analise-inadimplencia-brasil)
* **Problema de Negócio:** Necessidade de mapear a deterioração do crédito e identificar gargalos regionais de inadimplência (PF vs PJ).
* **Abordagem Técnica:** Web scraping automatizado via **Selenium** consumindo o sistema de dados abertos do Banco Central. Consolidação e modelagem em **SQL no BigQuery** utilizando *Window Functions* e CTEs, e visualização em **Power BI**.
* **Resultado:** Identificação de que a taxa de inadimplência de Pessoas Físicas é **2.4x maior** que Pessoas Jurídicas, além do mapeamento de região mais inadimplente.

#### 🗂️ [TaskFlow Pro — Gestão Corporativa](https://github.com/Lobato2310/task-list)
* **Problema de Negócio:** Falta de rastreabilidade e centralização no acompanhamento do fluxo operacional de equipes corporativas.
* **Abordagem Técnica:** Desenvolvimento em **Django** integrado ao **HTMX** para reatividade contínua sem recarregar a página. Sistema de permissões por perfil (Colaborador, Gestor, Admin), auditoria de histórico com `django-simple-history` e dashboard analítico em **Plotly**.
* **Resultado:** Aplicação reativa completa com isolamento de dados por usuário, histórico imutável para auditorias e visões temporais do progresso da equipe.

---

### 📚 Aprendizado Contínuo & Próximos Passos

- 📝 **Atualmente Estudando e Praticando:**
  - Validação avançada e testes automatizados de dados com Python.
  - Engenharia de Prompts e chamadas de API REST para integração de Agentes de IA e LLMs em sistemas analíticos.
- 🎓 **Próxima Especialização / Certificação:**
  - [Certificado Profissional IBM Generative AI Engineering](https://www.coursera.org/professional-certificates/ibm-generative-ai-engineering) *(Coursera)* — Foco no desenvolvimento de aplicações avançadas de IA Generativa, frameworks de agentes e integração de modelos.

---

### 📊 Estatísticas do GitHub

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Lobato2310&show_icons=true&theme=dark&include_all_commits=true&count_private=true" alt="Lucas Lobato's GitHub Stats" height="175"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Lobato2310&layout=compact&theme=dark" alt="Top Languages" height="175"/>
</p>

---

### 📬 Conecte-se comigo

<p align="left">
  <a href="https://www.linkedin.com/in/lucas-lobato-tech" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:lucaslobsouza@gmail.com">
    <img src="https://img.shields.io/badge/Email-333333?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
</p>
