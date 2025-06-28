# Desafio Alura Store: Análise de Dados de Vendas

## Visão Geral do Projeto

Este projeto faz parte do desafio "Praticando Python para Data Science: Challenge Alura Store", proposto pela Alura na trilha de Data Science do programa ONE (Oracle Next Education). O objetivo principal é realizar uma análise abrangente dos dados de vendas de uma rede de lojas fictícia (Alura Store) para extrair insights valiosos que possam apoiar decisões de negócio, como a identificação da loja com melhor ou pior desempenho, produtos de destaque, categorias mais vendidas e aspectos relacionados a frete e satisfação do cliente.

## Análises Realizadas

O notebook `AluraStoreBr.ipynb` contém a implementação de diversas análises exploratórias e quantitativas, incluindo:

* **Análise de Faturamento:** Cálculo e comparação do faturamento total de cada loja.
* **Vendas por Categoria de Produto:** Identificação das categorias de produtos mais e menos vendidas em cada loja, com visualizações para comparar o desempenho entre as lojas.
* **Média de Avaliação de Clientes:** Cálculo da média das avaliações de compra para cada loja, fornecendo um indicativo da satisfação do cliente.
* **Produtos Mais e Menos Vendidos:** Determinação dos produtos que mais e menos contribuíram para as vendas em cada loja.
* **Frete Médio:** Análise do custo médio de frete por loja, um fator importante para logística e precificação.
* **Recomendação de Negócio:** Síntese dos insights para fundamentar uma recomendação sobre qual loja deve ser vendida, considerando todos os fatores analisados.

## Tecnologias Utilizadas

* **Python:** Linguagem de programação principal.
* **Pandas:** Biblioteca para manipulação e análise de dados.
* **Matplotlib:** Biblioteca para criação de gráficos e visualizações de dados.
* **Seaborn:** Biblioteca para visualização de dados baseada em Matplotlib, oferecendo gráficos estatísticos mais atraentes.
* **Jupyter Notebook:** Ambiente interativo para desenvolvimento e execução do código, permitindo combinar código, visualizações e texto explicativo.

## Instalação e Dependências

Para executar este projeto, você precisará ter o Python instalado em seu ambiente. Recomenda-se o uso de um ambiente virtual para gerenciar as dependências.

1.  **Clone o repositório (se aplicável) ou baixe o arquivo `AluraStoreBr.ipynb`:**
    ```bash
    git clone <URL_DO_SEU_REPOSITORIO>
    cd <nome_do_repositorio>
    ```
2.  **Crie e ative um ambiente virtual (opcional, mas recomendado):**
    ```bash
    python -m venv venv
    # No Windows:
    .\venv\Scripts\activate
    # No macOS/Linux:
    source venv/bin/activate
    ```
3.  **Instale as dependências:**
    ```bash
    pip install pandas matplotlib seaborn jupyter
    ```

## Como Executar o Projeto

Após a instalação das dependências, siga os passos abaixo para executar e explorar o projeto:

1.  **Inicie o Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```
2.  **Abra o Notebook:** No seu navegador, que será aberto automaticamente, navegue até o diretório onde você salvou o arquivo `AluraStoreBr.ipynb` e clique nele para abri-lo.
3.  **Execute as Células:** Você pode executar as células individualmente (clicando na célula e pressionando `Shift + Enter`) ou executar todas as células em sequência (menu `Cell` -> `Run All`). As análises e visualizações serão geradas conforme o código é executado.

## Estrutura do Projeto

* `AluraStoreBr.ipynb`: O notebook principal contendo todo o código de análise, visualizações e conclusões.
* `dados_vendas.csv` (assumindo que há um arquivo de dados): O arquivo CSV contendo os dados brutos de vendas que são utilizados no notebook.

## Resultados e Insights Chave

As análises resultaram em insights importantes sobre o desempenho das lojas:

* A **Loja 1** demonstrou ser a de maior faturamento.
* A categoria de **Móveis** é consistentemente a mais vendida em todas as lojas.
* A **Loja 3** e **Loja 2** apresentaram as maiores médias de avaliação dos clientes.
* A **Loja 4** possui o **menor frete médio**, mas também o **menor faturamento**.

Com base nesses e outros dados detalhados no notebook, uma recomendação foi formulada sobre qual loja seria mais estratégica para uma possível venda.

## Conclusão / Recomendação Final (Extraído do Projeto)

Considerando o faturamento, custos de frete, avaliações e desempenho de produtos e categorias, a **Loja 4** é recomendada para venda. Embora tenha um frete médio baixo, seu faturamento consistentemente menor indica que pode ser a unidade com menor retorno sobre o investimento, permitindo que o Senhor João concentre recursos nas lojas mais lucrativas.

---

**Autor:** [DevNovaes](https://github.com/euvnovaes)

**Contato:** [Linkedin](linkedin.com/in/novaesvinicius)
