Projeto desenvolvido durante a formação Power BI Analyst da DIO. O objetivo principal foi pegar num relatório financeiro existente (base *Financial Sample*) e refazer toda a parte visual e de navegabilidade, aplicando conceitos de contraste, alinhamento e experiência do utilizador.

## O que foi alterado no projeto

O relatório original tinha um fundo roxo escuro com excesso de informação numa única tela. A reestruturação dividiu e organizou a análise em 3 páginas principais:

* **Menu de Navegação Lateral:** Adição de uma barra fixa à esquerda com Navegador de Páginas configurado em três estados (padrão, *hover*/focalizar e página selecionada) para facilitar a transição entre as telas.
* **Página 1 - Sales (Visão Geral):** Limpeza dos cartões de topo (mantendo apenas Total de Vendas e Unidades Vendidas com cantos arredondados), ajuste de cores nas barras de segmento para melhorar o contraste no fundo claro e adição de uma matriz trimestral abaixo do gráfico de área.
* **Página 2 - Profit (Detalhamento de Lucro):** Estruturação com filtro por ano em bloco, Árvore de Decomposição (Lucro por Ano e País), Gráfico de Radar por produto, *Treemap* por segmento e gráfico de Cascata (*Waterfall*) por trimestre.
* **Página 3 - Report (Detalhamento de Vendas):** Comparativo direto entre Vendas e Lucro por período e gráfico combinado de colunas e linha (Sales vs. Gross Sales) ordenado de forma crescente.

## Ficheiros

* `sales_report_ux_final.pbix`: Ficheiro do Power BI Desktop com o dashboard completo.
* `/prints`: Capturas de ecrã das 3 páginas do relatório finalizado.
