## Leonardo Zarelli

**Transição de Engenharia de Dados para Risco Quantitativo.** Base construída em dados de produção — modelagem de banco, pipelines, dashboards para +300 empresas. Hoje aplicando método científico a séries financeiras: validação fora da amostra, controle de overfitting e teste de significância estatística.

---

### 🔬 Pesquisa em andamento — validação de estratégia quantitativa

Sistema próprio de pesquisa em Python, construído aplicando o material do **Marcos López de Prado** (*Advances in Financial Machine Learning* / ORIE 5256, Cornell).

**Métodos implementados do zero:**
- **Validação Cruzada Purgada** com embargo — remove do treino os eventos cuja janela de resultado encosta no bloco de teste, eliminando vazamento temporal
- **MDA (Mean Decrease Accuracy)** com colunas de ruído aleatório como régua de calibração — indicador que ranqueia abaixo do ruído não é sinal
- **Sharpe Ratio Deflacionado** (Bailey & López de Prado, 2014) — corrige por assimetria, curtose e número de tentativas testadas
- **Monte Carlo de sequência** — mede risco de caminho embaralhando a ordem dos trades
- Rotulagem por **barreira tripla** e simulação de carteira sem sobreposição de posições

**Escala do teste:** 611 ativos · 61.676 trades fora da amostra · configuração congelada antes de rodar · dois timeframes.

**O que mais importa nesse trabalho:** o método derrubou cinco hipóteses minhas — inclusive a que eu considerava a descoberta principal, que se revelou artefato de um único ativo quando testada em dados virgens. O Sharpe Ratio Deflacionado foi auditado contra 500 simulações sob hipótese nula (média 0,510 para 0,50 esperado; 4,0% de falso positivo no limiar de 95%).

> Código ainda privado — em preparação para publicação da camada de validação.

---

### 📚 Formação em andamento

- **CPA (ANBIMA)** — certificação em curso
- **Matemática e estatística** — retomada estruturada do zero, base para finanças quantitativas
- **López de Prado — Lecture 1 (ORIE 5256, Cornell)** — concluída, com glossário técnico próprio construído em paralelo
- **AZ-104 (Azure Administrator)** — trilha de infraestrutura em andamento

---

### 🧰 Base técnica

| Área | Stack |
|---|---|
| **Dados** | Python, SQL, PostgreSQL, ETL, modelagem de dados |
| **Quant / ML** | scikit-learn, pandas, NumPy, validação fora da amostra, controle de overfitting |
| **Cloud** | Azure (ARM templates, Entra ID, governança de identidade) |
| **Automação** | n8n, integração de sistemas sem API disponível |

---

### 💼 Experiência prática

Ciclo completo de dados em produção:
- Modelagem e manutenção de banco de dados (PostgreSQL)
- Pipelines de tratamento de dados em Python, incluindo fontes sem API disponível
- Consultas SQL para KPIs de faturamento, recorrência e conversão
- Dashboards analíticos consumidos por times de negócio
- Automação de processos operacionais (onboarding, alimentação de sistema)

---

### 📂 Repositórios

- **[azure-infrastructure-enterprise-labs](https://github.com/zarelli1/azure-infrastructure-enterprise-labs)** — laboratórios de identidade, governança e automação de ciclo de vida no Entra ID
- **[azure-arm-multienv-portfolio](https://github.com/zarelli1/azure-arm-multienv-portfolio)** — templates ARM para deploy multi-ambiente parametrizado
- **[leonardozarelli-portfolio](https://github.com/zarelli1/leonardozarelli-portfolio)** — portfólio pessoal

---

### 🌍 Disponibilidade

🇮🇹 **Cidadão italiano** (cidadania reconhecida) — aberto a oportunidades no Brasil e na Europa, com foco em Suíça / Ticino.

📫 **[LinkedIn](https://www.linkedin.com/in/leonardo-zarelli/)**
