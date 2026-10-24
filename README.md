# techchellenge-olist
Projeto FIAP - Pós Tech Data Analytcs - 1º Bimestre

# Análise de Dados e Business Intelligence — E-commerce Olist

## 📌 Sobre o projeto

Este projeto tem como objetivo analisar o desempenho comercial, a eficiência logística, a satisfação dos clientes e o perfil de pagamentos do e-commerce Olist, utilizando o **Brazilian E-Commerce Public Dataset by Olist**.

A proposta foi transformar dados transacionais em informações relevantes para a tomada de decisão, conectando indicadores operacionais e comerciais a oportunidades de melhoria e recomendações estratégicas.

O projeto reúne diferentes entregáveis que se complementam: um dashboard interativo desenvolvido no Power BI, uma documentação técnica, um relatório executivo e uma apresentação em vídeo direcionada a acionistas e investidores.

## 🎯 Objetivos

- Avaliar o desempenho comercial e a evolução dos pedidos e da receita.
- Identificar a concentração de receita entre as categorias de produtos.
- Analisar os indicadores logísticos, os prazos de entrega e os atrasos.
- Investigar a relação entre a experiência de entrega e a satisfação dos clientes.
- Compreender o perfil de pagamentos e sua relação com o ticket médio.
- Desenvolver projeções de pedidos e receita a partir do comportamento histórico.
- Traduzir os resultados em insights e recomendações para apoiar decisões de negócio.

## 📊 Principais indicadores e análises

### 1. Desempenho comercial

Análise do volume de pedidos, da receita e do ticket médio, considerando a evolução histórica do negócio e a participação das principais categorias de produtos.

**Destaques da análise:**
- Aproximadamente 99 mil pedidos no período analisado.
- Receita total de aproximadamente R$ 15,84 milhões, incluindo produtos e frete.
- Ticket médio de R$ 159,33.
- As quatro principais categorias representam aproximadamente 47% da receita de produtos.

### 2. Previsão de pedidos e receita

Desenvolvimento de projeções para os 12 meses seguintes ao período histórico utilizado no modelo, com o objetivo de estimar a evolução da demanda e da receita.

A previsão utiliza o método de suavização exponencial de Holt com tendência amortecida, considerando o nível recente da série e sua tendência, com redução gradual da influência dessa tendência ao longo do horizonte projetado.

Também foi aplicado um ajuste específico para novembro, com base no comportamento histórico observado em torno da Black Friday.

As projeções são estimativas estatísticas destinadas ao planejamento e não representam resultados efetivamente realizados ou garantidos.

### 3. Eficiência logística

Avaliação do desempenho das entregas, considerando os prazos, a proporção de pedidos entregues no prazo e a distribuição dos atrasos entre as regiões brasileiras.

**Destaques da análise:**
- 93,2% dos pedidos entregues chegaram dentro do prazo.
- O prazo médio de entrega foi de aproximadamente 12 dias.
- O Nordeste apresentou a maior proporção de atrasos entre as regiões analisadas.

A análise também explora a relação entre os atrasos e o tempo total de entrega, permitindo identificar pontos de atenção para a operação logística.

### 4. Satisfação dos clientes

Investigação das avaliações dos consumidores e de sua relação com o desempenho das entregas.

**Destaques da análise:**
- Nota média de avaliação de 4,1.
- Aproximadamente 77% das avaliações correspondem a notas 4 ou 5.
- As entregas realizadas após o prazo apresentam avaliações médias inferiores às entregas realizadas antes ou dentro do prazo.

Esses resultados evidenciam a relevância de acompanhar a experiência de entrega como parte da análise da satisfação dos consumidores.

### 5. Perfil de pagamentos

Análise das modalidades de pagamento, da distribuição entre compras à vista e parceladas e da relação entre o número de parcelas e o ticket médio.

**Destaques da análise:**
- Aproximadamente 51,5% dos pedidos utilizaram pagamento parcelado.
- As compras parceladas apresentaram ticket médio superior ao das compras à vista.
- O ticket médio varia entre as faixas de parcelamento analisadas.

Os resultados ajudam a compreender o comportamento de compra dos consumidores e oferecem subsídios para avaliar oportunidades comerciais relacionadas às modalidades de pagamento.

As relações observadas são descritivas e não demonstram, isoladamente, que uma modalidade de pagamento cause aumento no valor das compras.

## 🛠️ Ferramentas e tecnologias

- **Power BI:** desenvolvimento do dashboard, visualização dos indicadores e exploração dos resultados.
- **DAX:** criação de medidas e cálculos para análise dos dados.
- **Power Query:** preparação e transformação dos dados.
- **Python:** processamento analítico e desenvolvimento das projeções de séries temporais.
- **GitHub:** versionamento e organização dos arquivos e entregáveis do projeto.

## 📁 Entregáveis

O repositório reúne quatro entregáveis principais:

### Dashboard Power BI
Painel interativo que consolida os indicadores e permite explorar o desempenho comercial, a logística, a satisfação dos clientes e o perfil de pagamentos.

### Documentação técnica
Material que registra os procedimentos técnicos, as transformações, os cálculos e as metodologias utilizadas no desenvolvimento das análises.

### Relatório executivo
Documento que organiza os principais resultados, interpretações, pontos de atenção e recomendações de negócio em uma narrativa voltada à tomada de decisão.

### Apresentação em vídeo
Apresentação dos resultados e dos principais insights do projeto, estruturada para comunicar as análises de forma objetiva a um público executivo, incluindo acionistas e investidores.

## 💡 Principais aprendizados

O desenvolvimento do projeto permitiu explorar como diferentes dimensões de um negócio de e-commerce podem ser analisadas de forma integrada.

Entre os principais pontos identificados estão a concentração da receita em determinadas categorias, a relação entre o desempenho logístico e a satisfação dos clientes e as diferenças de ticket médio entre os perfis de pagamento.

A análise também demonstra como técnicas de previsão podem complementar a leitura dos dados históricos e contribuir para o planejamento, desde que suas premissas e limitações sejam consideradas.

Mais do que apresentar indicadores isolados, o projeto busca conectar os resultados a questões relevantes para o negócio, apoiando uma visão integrada do desempenho comercial e operacional.

## 📚 Fonte dos dados

**Brazilian E-Commerce Public Dataset by Olist**

Base pública de dados de e-commerce que reúne informações sobre pedidos, produtos, clientes, pagamentos, entregas e avaliações.

Fonte: [Kaggle — Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

## ⚠️ Considerações

As análises foram desenvolvidas com base nos dados históricos disponibilizados pelo conjunto de dados público. Os indicadores e as conclusões estão condicionados à cobertura e às características dessa base.

As projeções representam estimativas construídas a partir do histórico disponível e devem ser interpretadas como apoio ao planejamento, não como garantia de desempenho futuro.

As associações identificadas entre variáveis representam padrões observados nos dados e não estabelecem, por si só, relações de causalidade.

---

**Projeto de Análise de Dados e Business Intelligence — E-commerce Olist**