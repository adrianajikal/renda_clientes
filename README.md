# **Análise e Modelagem da Renda dos Clientes**
Este projeto tem como objetivo construir um modelo preditivo da renda dos clientes de uma instituição financeira com base em variáveis disponíveis, utilizando técnicas de análise exploratória de dados e modelagem estatística.

## **Descrição do Projeto**
A instituição financeira deseja compreender melhor o perfil de renda de seus novos clientes para ajustar limites de cartões de crédito sem solicitar documentação adicional. Para isso, um estudo foi realizado para coletar dados sobre a renda dos clientes e variáveis relacionadas. O objetivo é construir um modelo preditivo da renda utilizando essas variáveis.

## **Dados**
Os dados estão no arquivo previsao_de_renda.csv e a seguir são algumas variaveis significativas para nossa analise:

- index: Identificador do cliente
- qtd_filhos: Número de filhos
- idade: Idade do cliente
- tempo_emprego: Tempo de emprego do cliente (em anos)
- qt_pessoas_residencia: Número de pessoas na residência
- renda: Renda mensal do cliente
- Análise Realizada
- Carregamento dos Dados

O arquivo CSV foi carregado em um DataFrame do Pandas.

## **Análise Exploratória**

### Matriz de Dispersão: Criada para visualizar a relação entre variáveis quantitativas.

### Matriz de Correlações: Avaliada para identificar correlações entre as variáveis.

### Identificação de Outliers

Utilizou-se gráficos de dispersão para identificar possíveis outliers.

### Transformação Logarítmica

O logaritmo da variável renda foi calculado e a matriz de correlações foi revisada para identificar mudanças nas relações entre variáveis.

**Visualização**

Gráficos de dispersão e heatmaps foram gerados para visualizar correlações e padrões.

**Resultados**
Correlação com tempo_emprego: A transformação logarítmica da renda revelou uma correlação mais clara com o tempo de emprego.
Outras Variáveis: A transformação logarítmica não alterou significativamente a correlação com qtd_filhos, idade e qt_pessoas_residencia.

**Conclusão**
A aplicação do logaritmo na variável renda melhorou a análise ao revelar uma relação mais clara com tempo_emprego. No entanto, para outras variáveis, a transformação não trouxe grandes mudanças. A análise sugere que o tempo de emprego é uma variável importante na predição da renda.
