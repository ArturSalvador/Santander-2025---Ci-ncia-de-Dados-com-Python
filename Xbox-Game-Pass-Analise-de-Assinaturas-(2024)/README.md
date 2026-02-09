# 📊 Xbox Game Pass: Data Analysis (2024)

## 📌 Visão Geral
Análise estratégica de **296 registros** de assinaturas realizados entre **janeiro e dezembro de 2024**. O foco do projeto é mensurar a saúde financeira do serviço, o comportamento de retenção (churn/renovação) e o cross-sell de expansões.

---

## 🎯 Key Performance Indicators (KPIs)
O dashboard foi projetado para responder:
* **Faturamento:** Qual o volume total gerado pelos planos anuais?
* **Retenção:** Como a renovação automática impacta a receita?
* **Cross-selling:** Qual a adesão aos add-ons *EA Play* e *Minecraft Season Pass*?

---

## 🗂 Estrutura & Tratamento de Dados
Para garantir a integridade da análise, os dados foram tipados e limpos, com destaque para:
* **Conversão Numérica:** Criação do campo `EA Play Season Pass Price (Num)` para cálculos precisos.
* **Métricas Consolidadas:** Cálculo do `Total Value` integrando plano base + add-ons.
* **Granularidade:** Cada registro representa um cliente único em 2024.

---

## 🖥️ O Dashboard
### 📈 Visualizações Principais
* **Big Numbers:** Contagem total de assinaturas por Add-on.
* **Gráfico de Barras:** Comparativo de planos com vs. sem Renovação Automática.
* **Segmentadores Dinâmicos:** Filtros temporais por Ano, Trimestre e Mês.

### 🧠 Insights Extraídos
* **Previsibilidade:** Avaliação do impacto financeiro da renovação automática.
* **Engajamento:** Taxa de adoção de passes de temporada específicos.
* **Sazonalidade:** Comportamento das assinaturas ao longo dos meses de 2024.

---

## 🛠️ Tecnologias & Ferramentas
* **Análise de Dados:** Python/Pandas ou Excel (Power Query).
* **Visualização:** Power BI / Tableau / Looker Studio.

---
> **⚠️ Limitações:** Análise restrita ao ano de 2024; cada linha representa um usuário único (sem recorrência multi-transacional).
