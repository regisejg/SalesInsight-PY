## SalesInsight PY — Análise e Visualização de Dados de Vendas

Projeto em Python, Pandas e Matplotlib que implementa os 10 requisitos funcionais da atividade.


## Sobre o projeto

Analise e visualizacao de dados de vendas desenvolvida em Python. O projeto carrega, limpa, transforma, agrega e visualiza um dataset de vendas, gerando metricas por periodo, produto, categoria e regiao, alem de uma segmentacao simples de clientes por faixa de gasto.

## O que o projeto analisa 

- Receita total e volume de vendas por mes e por trimestre 
- Top produtos e categorias por receita 
- Desempenho por regiao 
- Segmentacao de clientes por nivel de gasto (Bronze, Prata, Ouro) 
- Relacao entre quantidade vendida e receita por transacao
- Exportacao de relatorios em CSV e JSON e de graficos em PNG

## Conceitos aplicados (Modulo 01 - Semanas 01 a 08)

- Logica de programacao: variaveis, tipos, operadores, condicionais 
- Estruturas de dados: listas, tuplas, dicionarios e compostas 
- Funcoes: parametros, retorno, lambda , ordem superior 
- Leitura e escrita de arquivos CSV e JSON 
- Modulo datetime e conversão de tipos (cast) 
- Pandas:DataFrames, filtros, groupby, transformacoes 
- Matplotlib e Seaborn: linha, barra, dispersao, subplots, export 
- Git e GitHub: branches, commits e GitFlow simplificado

## Arquivos
- `salesinsight.ipynb`: notebook principal, organizado por requisito e com explicações.
- `README.md`: instruções do projeto.
- `vendas.csv`: gerado automaticamente na primeira execução, com dados sintéticos.
- `saidas/`: pasta de saída criada durante a execução, com CSV, JSON e gráficos PNG.

## Requisitos
Python 3.10+ recomendado.

## Executar no Jupyter
1. Abra um terminal na pasta do projeto.
2. Execute `jupyter notebook` ou `jupyter lab`.
3. Abra `salesinsight.ipynb`.
4. Execute as células em ordem, de cima para baixo.

## Saídas

A pasta `saidas/` conterá:
- `metricas_por_mes.csv`
- `segmentacao_clientes.csv`
- `top_produtos.csv`
- `receita_por_categoria.csv`
- `receita_por_regiao.csv`
- `estatisticas_gerais.json`
- `receita_por_mes.png`
- `top_produtos.png`
- `quantidade_vs_receita.png`
- `painel_resumo.png`

## Requisitos funcionais implementados
RF01 dataset;
RF02 inspeção; 
RF03 limpeza; 
RF04 colunas derivadas; 
RF05 agregações; RF06 segmentação; 
RF07 gráficos; 
RF08 funções, classe e função de ordem superior; 
RF09 exportação CSV/JSON; 
RF10 `main()` e ponto de entrada.

## Observações
-Os dados são sintéticos e não representam vendas reais. Cada linha é tratada como um registro de venda. As faixas de receita por item são: Baixa (< R$ 1.000), Média (R$ 1.000 a < R$ 5.000) e Alta (≥ R$ 5.000).
-

