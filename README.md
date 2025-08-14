
# 📊 Challenge Alura Store 1: Análise de Desempenho de Lojas

Análise de dados realizada como parte do desafio promovido pela Oracle Next Education (ONE) em parceria com a Alura.

## 🚀 Tecnologias Utilizadas

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626.svg?style=for-the-badge&logo=Jupyter&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![Seaborn](https://img.shields.io/badge/Seaborn-88d498?style=for-the-badge&logo=seaborn&logoColor=white)

---

## 🎯 Propósito da Análise

O objetivo desta análise é avaliar o desempenho de quatro lojas da rede Alura Store para identificar a unidade com menor eficiência. A recomendação final servirá de base para a decisão estratégica do Sr. João sobre qual loja vender para investir em um novo negócio.

Para isso, a análise se aprofunda nas seguintes métricas:
-   Faturamento total de cada loja.
-   Categorias mais populares.
-   Média de avaliação dos clientes.
-   Produtos mais e menos vendidos.
-   Custo médio do frete.

---

## 📂 Estrutura do Projeto

A organização dos arquivos no repositório é a seguinte:

-   `analise_lojas.ipynb`: O notebook Jupyter contendo todo o código da análise e a geração dos gráficos.
-   `/dados/`: Pasta contendo o(s) arquivo(s) de dados (`.csv`) utilizados na análise.
-   `/imgs/`: Pasta com as imagens dos gráficos gerados e exportados pelo notebook, que são utilizadas neste README.

---

## 📊 Gráficos e Insights Obtidos

A análise comparativa entre as quatro lojas revelou diferenças significativas de desempenho, destacando a Loja 4 como a de menor performance.

### Faturamento e Frete Médio

![Faturamento e frete médio por loja](https://github.com/NiveskZ/challenge-alura-store/blob/main/imgs/faturamento-freteMedio-bar.png?raw=true)

-   **Faturamento Total:**
    -   Loja 1: R$ 1.534.509,12
    -   Loja 2: R$ 1.488.459,06
    -   Loja 3: R$ 1.464.025,03
    -   Loja 4: R$ 1.384.497,58
-   **Frete Médio:**
    -   Loja 1: R$ 34,69
    -   Loja 2: R$ 33,62
    -   Loja 3: R$ 33,07
    -   Loja 4: R$ 31,28

**Insight:** A Loja 1 lidera em faturamento, enquanto a Loja 4 apresenta uma receita consideravelmente inferior às demais, sendo a única abaixo de R$ 1,4 milhão.

### Desempenho por Categoria de Produto

![Unidades vendidas por categoria](https://github.com/NiveskZ/challenge-alura-store/blob/main/imgs/linhas-unidade-categoria.png?raw=true)

**Insight:** Enquanto as lojas 1, 2 e 3 mostram bom desempenho em categorias específicas (compensando quedas em umas com altas em outras), a Loja 4 consistentemente performa abaixo da média em quase todas as categorias, com uma queda especialmente acentuada em eletrodomésticos.

### Análise da Receita Diária

![Distribuição da receita em número de dias](https://github.com/NiveskZ/challenge-alura-store/blob/main/imgs/hist-distribuicao-diaria.png?raw=true)

**Insight:** O histograma mostra que a Loja 4 concentra a grande maioria de seus dias com uma receita diária abaixo de R$ 2.000, muito mais do que as outras lojas. Isso indica que, ao contrário das outras, ela não consegue compensar dias de baixa com picos de vendas em datas especiais.

---

## 🏁 Conclusão

Feita a análise e através da visualização de dados, **a recomendação é a venda da Loja 4**. Ela possui o menor desempenho geral, com um faturamento muito inferior e sem nenhuma categoria de destaque que compense suas deficiências. Além disso, sua distribuição de receita ao longo do tempo e o desempenho regional são consistentemente piores que os das outras três lojas, indicando que sua venda teria o menor impacto negativo na rede.

---

## 🚀 Instruções para Executar o Notebook

Para reproduzir esta análise em sua máquina local, siga os passos abaixo:

### Pré-requisitos

-   Python 3.x
-   As seguintes bibliotecas Python instaladas:
    -   `pandas`
    -   `matplotlib`
    -   `seaborn`

### Passos para Execução

1.  **Clone este repositório:**
    ```bash
    git
