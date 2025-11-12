AluraStoreBrasil: Análise de Desempenho de Lojas para Tomada de Decisão
Este projeto contém o notebook de análise de dados desenvolvido para o Desafio Alura (Data Science), cujo objetivo é avaliar o desempenho de quatro lojas (Loja 1, Loja 2, Loja 3 e Loja 4) do Sr João e recomendar qual delas deve ser vendida para liberar capital para um novo investimento.
________________________________________
1. O Propósito da Análise Realizada
O objetivo principal desta análise é fornecer ao Sr. João uma recomendação embasada em dados sobre qual das quatro lojas (Loja 1, Loja 2, Loja 3 e Loja 4) deve ser vendida.
Para isso, o projeto se concentra em avaliar e comparar as lojas com base em indicadores-chave de performance (KPIs) comerciais e operacionais, como:
•	Faturamento Total e Participação no faturamento consolidado.
•	Ticket Médio e Volume de Vendas.
•	Média de Avaliação de Clientes (Satisfação).
•	Custo Médio do Frete (Eficiência Logística).
•	Mix de Produtos (Vendas por Categoria e Produtos Mais Vendidos).
A meta final é identificar a loja cuja venda causará o menor impacto na receita consolidada e na operação das demais lojas do grupo.
________________________________________
2. Estrutura do Projeto e Organização dos Arquivos
A estrutura do projeto é simples e focada no ambiente de notebooks, como o Google Colab.
Arquivo/Recurso	Descrição
AluraStoreBrasil.ipynb	O notebook principal (Google Colab/Jupyter) que contém todo o código de importação, análise de dados, cálculos de KPIs e geração de gráficos.
DESAFIO01 ALURA_VENDA_LOJA_RELATORIO_FINAL.docx	O relatório final (mencionado pelo usuário) que resume as descobertas e apresenta a recomendação final, com justificativas de pontos fortes e fracos por loja.
Dados (Externos)	Os dados das quatro lojas são importados diretamente de arquivos CSV hospedados no GitHub (Alura), não sendo necessário incluir arquivos .csv locais no repositório.
________________________________________
3. Exemplos de Gráficos e Insights Obtidos
A análise gerou diversos gráficos e insights cruciais que apontam para a decisão final:
Gráficos Chave
•	Faturamento Total por Loja: Gráfico de barras que mostra o valor absoluto da receita de cada unidade. * Participação Percentual no Faturamento Total: Gráfico de pizza que visualiza a contribuição de cada loja para a receita total. * Valor do Ticket Médio por Loja: Gráfico de barras que compara a receita média por transação (venda) entre as lojas. * Média da Avaliação de Compra por Loja: Gráfico de barras que compara a satisfação média dos clientes.
Principais Insights
Indicador	Destaque	Loja com Pior/Melhor Performance	Conclusão
Faturamento Total	Maior e Menor receita 	Melhor: Loja 1 (R$ 1.534.509,12) / Pior: Loja 4 (R$ 1.384.497,58)	Loja 4 é a candidata com menor impacto na receita consolidada.
Percentual de Participação	Maior e Menor % de particpação	Melhor: Loja 1 (26,1%) / Pior: Loja 4 (23,6%)	Loja 4 é a candidata com menor percentual de participação na  receita consolidada.
Ticket Médio	Receita média por transação 	Melhor: Loja 1 (R$ 650,49) / Pior: Loja 4 (R$ 587,15)	Loja 4 demonstra menor eficiência em converter vendas em maior receita.
Média Avaliação	Satisfação do Cliente 	Melhor: Loja 3 (4,05) / Pior: Loja 1 (3,98)	As diferenças são mínimas; a satisfação não é um fator decisivo para a venda.
Frete Médio	Custo operacional 11	Melhor (Menor Custo): Loja 4 (R$ 31,28) / Pior (Maior Custo): Loja 1 (R$ 34,69)	Loja 4 tem uma vantagem logística, o que é um ponto positivo a ser considerado na reestruturação pós-venda.

Recomendação Final
A loja recomendada para a venda é a Loja 4.
•	Justificativa Principal: Possui o menor faturamento e o menor ticket médio. Vender a loja com a menor contribuição financeira garante que a perda de receita consolidada seja a mínima possível.
•	Fator de Mitigação: As principais categorias de produtos da Loja 4 (Móveis e Eletrônicos) são fortes em todas as outras lojas do grupo, o que sugere que a demanda pode ser absorvida pelas unidades remanescentes.
________________________________________
4. Instruções para Executar o Notebook
Para replicar a análise, siga os passos abaixo:
Pré-requisitos
•	Um navegador web e acesso ao Google Colab (ambiente recomendado) ou um ambiente Jupyter Notebook local.
•	Python 3.x instalado.
•	As bibliotecas pandas e matplotlib instaladas.
Execução no Google Colab (Recomendado)
1.	Acesse o Google Colab.
2.	Faça o upload do arquivo AluraStoreBrasil.ipynb para o seu ambiente Colab (ou crie um novo notebook e copie o código).
3.	Execute as células em ordem sequencial.
Execução em Ambiente Local (Jupyter/IDE)
1.	Certifique-se de que as bibliotecas necessárias estão instaladas:
Bash
pip install pandas matplotlib
2.	Abra o arquivo AluraStoreBrasil.ipynb no seu Jupyter Notebook ou IDE compatível.
3.	Execute as células do notebook em sequência, da primeira à última.
Observação
O notebook se encarrega de importar automaticamente os dados das quatro lojas diretamente dos seguintes URLs do GitHub:
•	loja_1.csv: https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_1.csv
•	loja_2.csv: https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_2.csv
•	loja_3.csv: https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_3.csv
•	loja_4.csv: https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_4.csv

