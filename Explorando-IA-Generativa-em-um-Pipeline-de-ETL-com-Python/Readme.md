# 🤖 Pipeline ETL: Simulação de IA Generativa com Python

## 📌 Resumo
Este projeto demonstra a integração de uma **lógica de IA Generativa** dentro de um fluxo de dados **ETL**. O diferencial aqui é a simplicidade: mostramos como enriquecer bases de dados simulando o comportamento de modelos de linguagem (LLMs) sem a necessidade de APIs pagas ou infraestrutura complexa.

---

## 🎯 O que o projeto faz?
1.  **Extrai:** Lê uma base de clientes (`CSV`).
2.  **Transforma:** Aplica uma "IA" baseada em templates dinâmicos e lógica `Random`.
3.  **Enriquece:** Gera mensagens personalizadas de educação financeira para cada cliente.
4.  **Carrega:** Exporta os resultados em um novo arquivo pronto para consumo.

---

## 🔄 Fluxo de Dados (ETL)

| Etapa | Ação | Ferramenta |
| :--- | :--- | :--- |
| **Extract** | Leitura do arquivo `dados_clientes.csv` | `Pandas` |
| **Transform** | Geração de conteúdo contextual via templates | `Python + Random` |
| **Load** | Exportação para `dados_clientes_enriquecidos.csv` | `Pandas` |

### 🔹 O Diferencial: Simulação de IA
A "inteligência" do projeto consiste em um motor de personalização que utiliza o nome do cliente e contextos pré-definidos para criar comunicações únicas, simulando o comportamento de um agente de IA real em escala.

---

## 🛠️ Stack Técnica
* **Linguagem:** Python 3.x
* **Manipulação de Dados:** Pandas
* **Lógica de Sorteio:** Random
* **Ambiente:** Jupyter Notebook

---

## 🚀 Próximos Passos
- [ ] Integração com **OpenAI API** ou **Google Gemini**.
- [ ] Implementação de banco de dados **SQLite/PostgreSQL**.
- [ ] Criação de um dashboard com **Streamlit**.

---
> **Nota Didática:** Este repositório foca na arquitetura do pipeline e na lógica de enriquecimento, sendo ideal para estudos de engenharia de dados inicial.
