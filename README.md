# Dashboard de Comportamento do Cliente - Análise de Varejo

Este repositório contém um projeto completo de análise de dados focado no comportamento de compra dos consumidores, utilizando um conjunto de dados com 3.900 registros e 18 colunas. O fluxo de trabalho abrange desde o tratamento de dados com **Python**, análise estruturada via **SQL** até a visualização estratégica no **Power BI**.

## 📌 Visão Geral do Projeto
O objetivo principal é identificar tendências, melhorar o engajamento do cliente e otimizar estratégias de marketing e produtos para uma empresa líder no varejo. A análise foca em entender como fatores como descontos, avaliações e assinaturas impulsionam as decisões de consumo.

## 📊 Visualização do Dashboard
Abaixo está a representação visual dos KPIs e métricas de comportamento:

![Dashboard de Comportamento do Cliente](<img width="1451" height="791" alt="image" src="https://github.com/user-attachments/assets/63a0d48c-738e-4dc5-b716-57c36d4651f8" />)
*(Dica: Faça o upload da imagem para o GitHub e substitua o link acima)*

## 🛠️ Tecnologias e Processos

### 1. Preparação de Dados (Python)
* **Limpeza:** Tratamento de valores nulos na coluna de avaliação através da mediana por categoria.
* **Padronização:** Renomeação de colunas para *snake_case* e remoção de redundâncias.
* **Engenharia de Recursos:** Criação de faixas etárias e cálculo de frequência de compra.

### 2. Análise de Negócios (SQL)
Os dados foram integrados ao PostgreSQL para responder a perguntas estratégicas:
* **Receita por Gênero:** O público masculino gerou \$157.890, enquanto o feminino gerou \$75.191.
* **Segmentação:** Identificação de 3.116 clientes no segmento "Fiel" (Loyal).
* **Ticket Médio:** Comparação entre frete Padrão (\$58,46) e Expresso (\$60,48).

### 3. Visualização (Power BI)
* **Status de Assinatura:** 27% dos clientes são assinantes.
* **Avaliação Média:** A nota média de satisfação geral é de 3,75.
* **Categorias Principais:** Vestuário (Clothing) é a categoria com maior volume de vendas.

## 💡 Recomendações de Negócio
* **Fidelização:** Criar recompensas para migrar clientes "Recorrentes" para o nível "Fiel".
* **Marketing Direcionado:** Focar esforços no grupo "Jovem Adulto", que representa a maior contribuição de receita (\$62.1
