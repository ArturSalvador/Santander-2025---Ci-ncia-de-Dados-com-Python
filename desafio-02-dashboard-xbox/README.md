📊 Xbox Game Pass – Análise de Assinaturas (2024)
📌 Objetivo

Este projeto analisa assinaturas do Xbox Game Pass no período de 15/01/2024 a 16/12/2024, utilizando 296 registros, onde cada linha representa um cliente.
O objetivo é avaliar faturamento, renovações automáticas e a adesão aos add-ons EA Play Season Pass e Minecraft Season Pass.

🗂 Estrutura dos Dados

Principais campos utilizados:

Plan

Start Date

Auto Renewal

Subscription Price

EA Play Season Pass

EA Play Season Pass Price (Num)

Minecraft Season Pass

Minecraft Season Pass Price

Total Value

Foi criada a coluna EA Play Season Pass Price (Num) para garantir tipagem numérica correta nas análises.

🎯 Perguntas de Negócio

O dashboard responde às seguintes questões:

Qual o faturamento total dos planos anuais?

Qual o faturamento total separado por assinaturas com e sem renovação automática?

Quantas assinaturas de EA Play Season Pass foram vendidas?

Quantas assinaturas de Minecraft Season Pass foram vendidas?

📊 Componentes do Dashboard

Big Numbers

Total Subscriptions EA Play Season Pass

Total Subscriptions Minecraft Season Pass

Gráfico de Barras

Total de assinaturas do Xbox Game Pass

Separado por Auto Renewal (Yes / No)

Segmentadores de Dados

Ano

Trimestre

Mês

Todos os indicadores são filtrados dinamicamente pelo período selecionado.

🧠 O que a análise permite avaliar

Impacto financeiro da renovação automática

Adoção dos add-ons (EA Play e Minecraft)

Comportamento das assinaturas ao longo do tempo

🚧 Limitações

Cada registro representa um cliente, não múltiplas transações.
Os dados referem-se apenas ao ano de 2024.
