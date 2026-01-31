# 📊 Projeto de Análise de Dados — Alura Store

## 📌 Descrição do Projeto

Este projeto tem como objetivo auxiliar o **Senhor João**, proprietário da rede fictícia **Alura Store**, a tomar uma decisão estratégica sobre qual loja de sua rede deve ser vendida para viabilizar o início de um novo empreendimento.

A partir da análise de dados de vendas, desempenho e avaliações de **quatro lojas fictícias**, o projeto busca identificar aquela que apresenta **menor eficiência geral**, utilizando métricas quantitativas e visualizações de dados para embasar a recomendação final.

---

## 🎯 Propósito da Análise

O propósito desta análise é:

* Comparar o desempenho das lojas com base em dados reais simulados
* Identificar padrões de faturamento, vendas e satisfação dos clientes
* Avaliar a eficiência de cada loja de forma objetiva
* Apoiar a tomada de decisão do Senhor João com base em evidências

A análise considera múltiplos indicadores para evitar conclusões baseadas em uma métrica isolada.

---

## 🧠 O que será analisado

Durante o desenvolvimento do projeto, serão avaliadas as seguintes informações:

* Faturamento total de cada loja
* Categorias de produtos mais e menos vendidas
* Produtos mais e menos vendidos
* Avaliação média dos clientes
* Frete médio por loja

Esses indicadores são analisados de forma conjunta para identificar pontos fortes e fracos de cada unidade.

---

## 🛠️ O que você vai ver:

Neste projeto, haverá:

* Carregamento e manipulação de arquivos CSV utilizando a biblioteca **Pandas**
* Limpeza, organização e exploração de dados
* Criação de visualizações com a biblioteca **Matplotlib**
* Análise de métricas de desempenho comercial
* Interpretação de dados para tomada de decisão
* Comunicação clara de resultados por meio de gráficos e texto analítico

---

## 📈 Visualizações e Insights

Para facilitar a interpretação dos resultados, foram criadas **visualizações gráficas**, respeitando o mínimo de **três tipos diferentes de gráficos**, escolhidos conforme o tipo de dado analisado.

### Exemplos de gráficos utilizados:

* **Gráfico de barras** para comparação do faturamento entre as lojas
* **Gráfico de linhas** para análise da distribuição de categorias de produtos
* **Gráfico lollipop** para comparação do preço médio de frete por loja
* Outros gráficos auxiliares, conforme necessário

### Principais insights obtidos:

* As lojas apresentam faturamentos semelhantes, porém uma delas se mantém consistentemente abaixo das demais
* Lojas com maior diversidade de categorias e produtos líderes tendem a apresentar melhor desempenho
* A satisfação dos clientes varia entre as lojas e impacta diretamente o potencial de crescimento
* Um frete mais baixo nem sempre se traduz em melhor desempenho financeiro

---

## ▶️ Instruções para Executar o Projeto

### 1. Clone o repositório

```bash
git clone https://github.com/seu-usuario/alura-store-analise.git
```

### 2. Instale as dependências

Certifique-se de ter o Python instalado (versão 3.8 ou superior) e execute:

```bash
pip install -r requirements.txt
```

### 3. Execute o notebook

Abra o arquivo abaixo em um ambiente Jupyter (Jupyter Notebook, JupyterLab ou Google Colab):

```text
notebooks/analise_alura_store.ipynb
```

Execute as células em ordem para reproduzir toda a análise e os gráficos apresentados.

---

## 🧾 Recomendação Final

Com base na análise conjunta de faturamento, categorias de produtos, produtos mais e menos vendidos, avaliações dos clientes e frete médio, a recomendação final é que o Senhor João venda a **Loja 4**. Essa unidade apresentou menor faturamento, desempenho inferior em categorias e produtos líderes, além de não converter vantagens operacionais, como frete mais baixo, em melhor desempenho financeiro.

As demais lojas demonstraram maior potencial de crescimento e desempenho mais consistente, tornando-se mais vantajosas de serem mantidas.

---

## 🚀 Tecnologias Utilizadas

* Python
* Pandas
* Matplotlib
