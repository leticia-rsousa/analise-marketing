## Análise de Dados de Marketing
**Descrição Geral** 📄<br>
Este projeto apresenta uma **análise estatística de dados para a área de marketing**, utilizando **Python** e bibliotecas de manipulação e visualização de dados. O sistema gera dados fictícios de usuários e interações, realiza **análises estatísticas, cálculos de métricas de engajamento e segmentações**, e produz **gráficos interativos** para facilitar a interpretação dos resultados. O projeto demonstra conceitos de **ciência de dados aplicada ao marketing, visualização de dados e exploração de métricas para tomada de decisão**.

---
**Objetivo** 🎯 <br> 
O objetivo principal do projeto é fornecer uma **ferramenta prática para análise de dados de marketing**, permitindo explorar padrões de comportamento de usuários, identificar clientes de alto valor, analisar métricas de engajamento e segmentar públicos.

---
**Tecnologias Utilizadas** 💻 <br>
* ***Python*** - linguagem principal.
* ***Pandas*** - manipulação de dados em DataFrames.
* ***NumPy*** - operações matemáticas e geração de números aleatórios.
* ***Matplotlib / Seaborn*** - criação de gráficos e visualizações.

---
**Arquitetura e Estrutura do Código** 🧱 <br><br>
***1. Script Principal (analise_marketing.py)*** <br>
Responsável por:
* ***Geração de dados fictícios de usuários e interações no site.*** 
* ***Cálculo de métricas como visitas, tempo no site, itens no carrinho e valor de compra.***
* ***Análises estatísticas básicas (média, mediana, desvio padrão, máximos e mínimos).***
* ***Segmentação de usuários (ex.: clientes de alto valor, visitantes que não compraram).***
* ***Criação de gráficos de distribuição e mapa de calor de correlação para visualização dos resultados.***

---
**Conceitos e Funcionalidades Demonstradas** 🔍 <br><br>
✅ ***Manipulação de dados:*** <br>
Uso de **Pandas e NumPy** para gerar, organizar e processar os dados de usuários e métricas de marketing.

✅***Visualização de dados:*** <br>
Criação de histogramas, gráficos de barras e mapas de calor com **Matplotlib e Seaborn** para análise de padrões e correlações.

✅***Análise estatística:*** <br>
Cálculo de **média, mediana, desvio padrão, valores extremos e correlação entre variáveis**.

✅***Segmentação de usuários:*** <br>
Identificação de **clientes de alto valor e visitantes sem conversão**, permitindo insights sobre comportamento e engajamento.

---
**Como Executar o Projeto** ▶️ <br><br>
***1. Instale as dependências (recomendado via requirements.txt):*** <br>
```pip install -r requirements.txt```

***2. Execute o script principal:*** <br>
```python analise_marketing.py```

***3. Siga as instruções no terminal e visualize os gráficos gerados.*** <br>

***Exemplo de Uso:*** <br>
```
Saída:
Shape da matriz de dados: (500, 4)

--- ANÁLISE ESTATÍSTICA GERAL ---
Média de Visitas: 24.5
Média de Tempo no Site: 32.1 min
Média de Itens no Carrinho: 2.3
Média de Valor de Compra: R$79.5

--- ANÁLISE: CLIENTES DE ALTO VALOR ---
Número de clientes de alto valor: 50

--- ANÁLISE: VISITANTES QUE NÃO COMPRAM ---
Número de visitantes que não compraram: 120

Mapa de calor da matriz de correlação exibido.
```

---
**Conclusão** 📌 <br>
Este projeto demonstra como realizar **análises de dados voltadas ao marketing**, integrando **manipulação de dados, cálculos estatísticos e visualizações gráficas**. Ele serve como um exemplo prático de **exploração de métricas, segmentação de usuários e interpretação de padrões de comportamento**, permitindo gerar insights valiosos para decisões estratégicas.
