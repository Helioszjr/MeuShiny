# MeuShiny
Análise da diversidade genética utilizando marcadores RAPD e SSR

ACESSE O LINK: https://heliojunior.shinyapps.io/shiny/

**Para marcadores RAPD**
✅ 1) Escolha e envie o arquivo Excel com os dados da matriz binario. **Exemplo da montagem da tabela se encontra abaixo.**

| Genótipo | 500 pb | 600 pb | 1100 pb | 1200 pb | 500 pb.1 | 
| -------- | ------ | ------ | ------- | ------- | -------- |
|    G1    | 0      | 1      | 1       | 1       | 0        |
|    G2    | 0      | 1      | 1       | 1       | 1        |
|    G3    | 1      | 0      | 1       | 0       | 0        |
|    G4    | 1      | 0      | 1       | 0       | 0        |
|    G5    | 0      | 0      | 0       | 0       | 1        |

•	Clique no botão "Browse..." (ou "Escolher arquivo" dependendo do navegador). 
✅ 2) Selecione o Método de Distância
•	jaccard → Distância Jaccard

✅ 3) Escolha o Método de Agrupamento 
•	average → Média das distâncias (UPGMA)

✅ 4) Defina o Número de Grupos (Clusters)
•	3 → O app vai formar 3 clusters/grupos.
•	4 → O app vai formar 4 clusters/grupos. **ESCOLHA ESSA OPÇÃO**

✅ 5) Rodar a Análise
Clique no botão "Rodar Análise".

• Dendrograma
• Gráfico de agrupamento
• Tabela de pertencimento dos indivíduos aos clusters
• Distâncias entre os grupos

**Para marcadores SSR**
✅ 1) Escolha e envie o arquivo Excel com os dados genotipados. **Exemplo da montagem da tabela se encontra abaixo.**

| Genótipo | SSR1   |   SSR2 | SSR3    |  SSR4   |   SSR5   |
| -------- | ------ | ------ | ------- | ------- | -------- |
|    G1    |   22   |   31   |   18    |   33    |    22    |
|    G2    |   43   |   25   |   15    |   45    |    51    |
|    G3    |   11   |   44   |   55    |   55    |    23    |
|    G4    |   31   |   55   |   51    |   16    |    44    |
|    G5    |   18   |   35   |   22    |   45    |    11    |

•	Clique no botão "Browse..." (ou "Escolher arquivo" dependendo do navegador).
✅ 2) Selecione o Método de Distância
euclidean → Distância Euclidiana

✅ 3) Escolha o Método de Agrupamento
•	average → Média das distâncias (UPGMA)

✅ 4) Defina o Número de Grupos (Clusters)
•	3 → O app vai formar 3 clusters/grupos.
•	4 → O app vai formar 3 clusters/grupos. ESCOLHA ESSA OPÇÃO

✅ 5) Rodar a Análise
Clique no botão "Rodar Análise".
O aplicativo irá processar os dados e mostrar os seguintes resultados (depende da implementação):

• Dendrograma
• Gráfico de agrupamento
• Tabela de pertencimento dos indivíduos aos clusters
• Distâncias entre os grupos

