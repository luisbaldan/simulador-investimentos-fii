# Simulador de Investimentos em Fundos Imobiliários (FIIs)

## 📌 Sobre o projeto

Este projeto foi desenvolvido como parte de um desafio da DIO, com o objetivo de criar uma ferramenta em Excel para simulação de investimentos em Fundos de Investimento Imobiliário (FIIs).

A solução foi desenvolvida do zero, utilizando a planilha de referência disponibilizada no desafio apenas como orientação para compreender os requisitos.

O objetivo foi transformar os cálculos financeiros em uma experiência mais simples e intuitiva, semelhante a um pequeno aplicativo.

## 🎯 Objetivo

Permitir que o usuário:

- identifique seu perfil de investidor;
- defina seu objetivo financeiro;
- informe o investimento inicial;
- informe seus aportes mensais;
- escolha o prazo da simulação;
- visualize premissas de rentabilidade;
- receba uma sugestão de distribuição de carteira;
- simule a evolução do patrimônio;
- estime os dividendos mensais;
- compare os resultados com sua meta financeira;
- visualize um relatório final preparado para impressão ou PDF.

## 🧩 Estrutura do projeto

O simulador está organizado em etapas:

1. **Rosto** – apresentação e início do simulador.
2. **Perfil do Investidor** – identificação do perfil por meio de perguntas e pontuação.
3. **Objetivo do Investimento** – definição do objetivo e dos valores da simulação.
4. **Premissas da Simulação** – definição das premissas de rentabilidade e Dividend Yield de acordo com o perfil.
5. **Carteira Sugerida** – distribuição percentual entre diferentes categorias de FIIs.
6. **Simulação** – cálculo dos resultados financeiros.
7. **Resultado** – apresentação resumida dos resultados.
8. **IMPRIMIR** – relatório final estruturado para impressão ou geração de PDF.
9. **Variáveis** – tabelas auxiliares utilizadas nos cálculos.

## 📊 Principais cálculos

O projeto utiliza funções financeiras e de referência do Excel para realizar os cálculos.

Entre os principais resultados estão:

- patrimônio acumulado;
- total investido;
- rendimentos acumulados;
- dividendos mensais estimados;
- comparação com a meta financeira definida pelo usuário.

O cálculo do patrimônio acumulado utiliza o conceito de **valor futuro (VF/FV)**, considerando o investimento inicial, os aportes mensais, o prazo e a rentabilidade mensal estimada.

## 📈 Perfis de investidor

O perfil é determinado a partir de um sistema de pontuação baseado nas respostas do usuário:

- **Conservador**
- **Moderado**
- **Agressivo**

Cada perfil possui premissas diferentes de rentabilidade e Dividend Yield para fins de simulação.

## 🏢 Carteira sugerida

A distribuição da carteira considera diferentes categorias de FIIs:

- Papel
- Tijolo
- Híbridos
- FOFs
- Desenvolvimento
- Hotelaria

As porcentagens são utilizadas exclusivamente para fins educacionais dentro da simulação.

## 🛠️ Tecnologias utilizadas

- Microsoft Excel
- Fórmulas financeiras do Excel
- Funções de busca e referência
- Validação de dados
- Hiperlinks para navegação
- Proteção de planilhas
- Formatação e organização de relatórios

## 🔐 Usabilidade

O arquivo foi estruturado para facilitar a utilização por pessoas que não possuem conhecimento avançado de Excel.

As planilhas possuem navegação entre as etapas e proteção das células, mantendo editáveis apenas os campos necessários para preenchimento.

## ⚠️ Aviso importante

Este projeto possui **finalidade exclusivamente educacional**.

As rentabilidades, Dividend Yields, distribuições de carteira e demais premissas utilizadas são hipotéticas e foram definidas para fins de simulação.

Os resultados apresentados não representam garantia de rentabilidade futura e **não constituem recomendação ou orientação de investimento**.

## 👨‍💻 Projeto

Desenvolvido como projeto prático para o desafio da **DIO**.
