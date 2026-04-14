# Análise de Risco e Sinistralidade para Insurtech 

# Sobre o Projeto:
Este projeto foi desenvolvido para simular o cenário de uma **Insurtech** (startup de seguros) que precisa precificar seus serviços com base em dados reais de segurança pública do Rio de Janeiro. 

O objetivo principal foi identificar padrões de criminalidade e localizar **outliers** (anomalias) que impactam diretamente no cálculo do valor do seguro (prêmio) e na viabilidade financeira da operação.

# Ferramentas Utilizadas:
* **Linguagem:** Python
* **Bibliotecas:** Pandas, Matplotlib, Seaborn
* **Conceitos:** Estatística Descritiva (Média, Mediana, Assimetria), Detecção de Outliers e Data Storytelling.

# Principais Insights de Negócio:
* **Regionalização de Preços:** Identificamos que a média de roubos no estado é inflada por regiões específicas. Cobrar um valor único estadual geraria perda de competitividade em áreas seguras e prejuízo em áreas críticas.
* **O Caso de Duque de Caxias (059ª DP):** A análise revelou que esta região é um outlier crônico, com picos de violência constantes há quase 15 anos. Estrategicamente, a seguradora deve tratar este CEP com uma tabela de preços diferenciada para não comprometer o caixa da empresa.
* **Tendências Temporais:** Embora a pandemia tenha reduzido os números temporariamente, a tendência de longo prazo ainda mostra um cenário de risco superior ao início da década de 2000.

# Como visualizar:
Basta abrir o arquivo `.ipynb` presente neste repositório para visualizar o código, as limpezas de dados e os gráficos gerados.
