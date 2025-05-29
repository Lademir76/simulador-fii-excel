# 📊 Simulador de Investimentos em Fundos Imobiliários (FIIs)

Este projeto tem como objetivo oferecer uma ferramenta prática, desenvolvida em Excel, para simular investimentos em Fundos Imobiliários. A planilha permite ao usuário visualizar o crescimento do patrimônio ao longo do tempo, com base em aportes mensais, taxa de rendimento e tempo de investimento.

## 🧠 Objetivos

- Simular o crescimento de um investimento em FIIs.
- Calcular o total investido, patrimônio acumulado e dividendos mensais.
- Ajudar investidores a tomarem decisões mais informadas.

## 🛠️ Funcionalidades

- Inserção de **aporte mensal**, **tempo de investimento** e **taxa de rendimento mensal**.
- Cálculo automático de:
  - Total investido
  - Patrimônio acumulado
  - Dividendos mensais
- Gráficos de evolução do patrimônio e dos dividendos.
- Interface amigável e personalizável.

## 📈 Fórmulas Utilizadas

A planilha utiliza fórmulas financeiras do Excel para simular o crescimento do investimento e o recebimento de dividendos. Abaixo estão as principais fórmulas aplicadas:

### 1. Valor Futuro (VF)
Calcula o valor acumulado ao final do período de investimento, considerando aportes mensais e uma taxa de rendimento constante.

=VF(taxa; períodos; -aporte)

### 2. Total Investido
Soma de todos os aportes mensais realizados durante o período.

=aporte * períodos

### 3. Dividendos Mensais
Simula o valor recebido mensalmente com base no patrimônio acumulado e na taxa de dividendos dos FIIs.

=patrimônio * tx_dividendos

### 4. Evolução Mensal do Patrimônio
Atualiza o valor do patrimônio mês a mês com base no rendimento e no novo aporte.

=valor_mês_anterior * (1 + tx )  + aporte

## 📂 Estrutura do Projeto

📁 simulador-fii-excel
├── Simulador_FII.xlsx
├── README.md
└── images/
    ├── grafico1.png
    └── grafico2.png

## 🚀 Como Usar

1. Baixe o arquivo `Simulador_FII.xlsx`.
2. Abra no Excel.
3. Preencha os campos de entrada (aporte, tempo, tx ).
4. Veja os resultados e gráficos atualizarem automaticamente.

## 🧾 Licença

Este projeto é de uso livre para fins educacionais.

## ✍️ Autor

Desenvolvido por Lademir Bechara
 ### Projeto realizado como parte do desafio da DIO - Digital Innovation One.

