Sistema de Investimento Simulado no S&P 500 com Previsões de Preços

 Sobre o projeto

Este projeto foi desenvolvido no âmbito da unidade curricular de Laboratórios de Inteligência Artificial e Ciência de Dados, durante o terceiro ano da licenciatura em Inteligência Artificial e Ciência de Dados.

O objetivo é explorar a aplicação de técnicas de aprendizagem automática à previsão de preços de ações e avaliar a sua utilização numa estratégia simulada de investimento no mercado bolsista.

Utilizando a biblioteca yfinance, foram recolhidos dados históricos das empresas do índice S&P 500, abrangendo o período de 2010 a 2024. 

Os dados incluem informações como preços de abertura e fecho, bem como eventos relacionados com as ações, nomeadamente splits.

Com base nestes dados, foram desenvolvidos e comparados dois modelos de aprendizagem automática:

Random Forest: um modelo baseado numa combinação de árvores de decisão, utilizado para identificar padrões nos dados históricos.

MLP (Multi-Layer Perceptron): uma rede neuronal artificial utilizada para aprender relações entre as variáveis e estimar preços futuros.

Ambos os modelos têm como objetivo prever o preço de fecho do dia seguinte para as empresas do S&P 500.

 Simulação de investimentos

As previsões produzidas pelos modelos são posteriormente utilizadas numa simulação de investimentos mensais em ações. 

Para explorar diferentes resultados possíveis, é aplicado o método de Monte Carlo, permitindo analisar vários cenários de investimento simulados.

Esta abordagem combina previsão de preços, aprendizagem automática e simulação estocástica para estudar como modelos preditivos podem ser integrados num processo de apoio à decisão financeira.

 Tecnologias utilizadas

Python — desenvolvimento e implementação dos modelos.

yfinance — recolha de dados históricos do mercado bolsista.

Random Forest — previsão através de aprendizagem automática.

MLP (rede neuronal) — modelação de padrões nos dados históricos.

Simulação de Monte Carlo — exploração de cenários de investimento.

 Objetivos de aprendizagem

Este projeto permitiu aplicar conhecimentos de Inteligência Artificial e Ciência de Dados a um problema financeiro real, explorando diferentes modelos preditivos e a utilização das suas previsões numa simulação de investimento.

Representa uma abordagem prática à ligação entre análise de dados históricos, previsão de séries temporais e simulação de estratégias financeiras.
