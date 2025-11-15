# 📊 Excel Dashboard – Xbox Subscription Analysis

Este repositório apresenta um **dashboard interativo em Microsoft Excel** voltado para a análise de assinaturas dos planos Xbox, incluindo produtos adicionais como **EA Play** e **Minecraft Season Pass**. O foco do projeto é transformar uma base de dados estruturada em tabelas em **insights visuais e estratégicos**, aplicando conceitos de análise de dados, métricas de negócio e boas práticas de visualização.

Este projeto foi desenvolvido como parte do desafio  
**"Criando um Dashboard de Vendas do Xbox com Excel"**  
da plataforma **DIO – Digital Innovation One**.

---

## 📊 Objetivo do Projeto

- Analisar o faturamento total por tipo de plano (anual, mensal, trimestral).
- Avaliar o impacto de **auto renovação** nas vendas.
- Medir o desempenho de produtos complementares (EA Play e Minecraft).
- Identificar o **ticket médio**  por tipo de plano.
- Visualizar a evolução mensal das assinaturas.
- Criar um dashboard funcional e visualmente atrativo em Excel.

---

## 📊 Visão Geral da Solução

O dashboard foi desenvolvido considerando:

- **Clareza visual** – gráficos simples e intuitivos.  
- **Interatividade** – uso de segmentações e filtros.  
- **Organização lógica** – agrupamento por métricas e categorias.  
- **Escalabilidade** – fácil substituição da base de dados.  
- **Profissionalismo** – adequado para portfólio e ambientes corporativos.

---
## 📁 Dados Utilizados

A base de dados foi construída em Excel com as seguintes colunas:

| Coluna                         | Descrição |
|-------------------------------|-----------|
| `Subscriber ID`               | Identificador único do assinante |
| `Name`                        | Nome do assinante |
| `Plan`                        | Nome do plano principal contratado |
| `Start Date`                  | Data de início da assinatura |
| `Auto Renewal`                | Indica se a renovação automática está ativada |
| `Subscription Price`          | Valor do plano principal |
| `Subscription Type`           | Tipo de plano (Anual, Mensal, Trimestral) |
| `EA Play Season Pass`         | Indica se o EA Play foi contratado |
| `EA Play Season Pass Price`   | Valor do EA Play |
| `Minecraft Season Pass`       | Indica se o Minecraft Pass foi contratado |
| `Minecraft Season Pass Price` | Valor do Minecraft Pass |
| `Coupon Value`                | Valor de desconto aplicado |
| `Total Value`                 | Valor total pago pelo assinante |

---
## 🧠 Metodologia

Para construção do dashboard, foram aplicados:

### ✔ Preparação dos dados
- Revisão da consistência dos valores.  
- Normalização de tipos de dados (datas, textos, números).    

### ✔ Modelagem e análise
- Construção de **tabelas dinâmicas** para KPIs.  
- Cálculo de métricas como ticket médio, total por categoria e valores acumulados.  

### ✔ Visualização
- Gráficos dinâmicos conectados às tabelas.  
- Segmentações para interatividade por:
  - período  
  - plano  
  - tipo de assinatura  
  - auto renovação  

### ✔ Estruturação final
- Layout organizado em seções: KPIs, gráficos, e filtros.  
- Paleta de cores consistente com o tema Xbox.

---

## 🧰 Ferramentas Utilizadas

- **Microsoft Excel**: Tabelas dinâmicas, segmentações, gráficos e fórmulas.
- **GitHub**: Para versionamento e entrega do projeto.

---

## 📌 Estrutura do Repositório

````bash
📦 subscription-dashboard
├── 📄 README.md
├── 📊 dashboard_xbox.xlsx
└── 📁 assets 
````
---

## 👩‍🎓 Autora
-  **Joana Cristina C. Silva**
- Estudante da plataforma DIO – Digital Innovation One
- Desafio: Criando um Dashboard de Vendas do Xbox com Excel
- 📧 Contato: joanacristinacss@gmail.com

---

## 📜 Licença
Este projeto é apenas para fins acadêmicos e não possui licença comercial

