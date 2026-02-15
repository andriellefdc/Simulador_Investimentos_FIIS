# 📊 Simulador de Investimentos em Fundos Imobiliários (FIIs)

Origem: Bootcamp SOA / DIO - Excel+AI.

Este projeto representa meu primeiro contato prático com a construção de simuladores financeiros em Excel, consolidando os conceitos estudados em uma das etapas do bootcamp Excel + AI, fornecidos pela parceria Santader Open Academy e a DIO.

## 📌 Sobre o Projeto

Este projeto consiste no desenvolvimento de uma ferramenta de simulação de investimentos em Fundos Imobiliários (FIIs) utilizando Excel.

O objetivo é permitir que o usuário simule cenário imediato, curto, medio e longo prazo com base em:

- Valor de aporte mensal
- Tempo de investimento
- Taxa de rendimento mensal
- Perfil de Investidor

A planilha automatiza cálculos financeiros relevantes, como patrimônio acumulado, lucro total e estimativa de dividendos mensais, auxiliando na tomada de decisão baseada em projeções.


## 🎯 Objetivos Técnicos do Projeto

- Criar uma ferramenta funcional de simulação financeira
- Aplicar conceitos de matemática financeira no Excel
- Estruturar dados com planilhas de apoio
- Automatizar cálculos usando funções financeiras
- Documentar o projeto utilizando GitHub como portfólio técnico


## 🧠 Conceitos e Técnicas Aplicadas

📈 Simulação de Cenários Futuros

A planilha permite projeções para diferentes horizontes temporais (2, 5, 10, 20 e 30 anos), demonstrando o efeito dos rendimentos de acordo com sua taxa.


🧮 Conceitos Básicos de Matemática Financeira

- Rendimento mensal
- Cálculo de dividendos
- Lucro acumulado
- Indicadores entre capital investido e patrimônio final


🔢 Funções Utilizadas

- VF() para cálculo de valor futuro
- PROCV() para busca de percentuais por perfi
- Concatenação em fórmulas para criação de chaves dinâmicas
- Operações matemáticas estruturadas
- Cálculos percentuais automatizados


🗂 Uso de Planilha de Apoio

Foi criada uma planilha auxiliar contendo:
- Perfil do investidor
- Tipo de FII
- Percentual sugerido

Essa estrutura permite:
- Separação lógica entre dados e cálculos
- Manutenção facilitada
- Escalabilidade do modelo


🏷 Nomeação de Intervalos

Foram utilizados nomes definidos como:
- Aporte
- Perfil
- Qtd_Anos
- Rendimento_Carteira
- Salario
- Sugestao _Investimento
- Taxa _Rendimento
- Valor_Investido
- Taxa_Mensal
- Patrimonio

Isso melhora:
- Legibilidade das fórmulas
- Organização do modelo
- Manutenção futura


🧩 Uso de Variáveis Globais

As células principais de entrada funcionam como variáveis globais, permitindo simulação dinâmica sem necessidade de alterar fórmulas.
Trazendo mais dinamismo ao nosso relatorio.


🎛 Validação de Dados

Foi aplicada validação de dados para:
- Seleção de perfil do investidor

Permitindo assim:
- Controle de entradas
- Eliminacao de erros de preenchimento
- Integridade dos dados


🎨 Uniformidade Visual

O projeto prioriza:
- Padronização de cores
- Separação clara entre entrada e resultado
- Organização em blocos lógicos
- Destaque visual para indicadores principais
- Clareza e usabilidade


📊 Visualização Gráfica

Inclui gráfico de pizza simples demonstrando a distribuição percentual dos investimentos por tipo de FII de acordo com o perfil investidor selecionado.

Isso permite:
- Visualização rápida da alocação em cada tipo de FII
- Interpretação intuitiva da estratégia de variação da carteira


## 📂 Estrutura do Repositório
``` markdown
📁 simulador-fii-excel
 ├── 📄 Simulador_Investimentos_FIIS.xlsx
 ├── 📄 README.md
 └── 📁 images
     ├── 📷 Dashboard_Principal_Investimentos_15022026_01.png
     ├── 📷 Dashboard_Planilha_Apoio_15022026_02.png
```    


## 🚀 Como Utilizar

1. Baixe o arquivo Excel.

2. Defina:
- Valor mensal a investir
- Tempo de investimento
- Taxa de rendimento
- Perfil do investidor

3. Automaticamente e dinamicamente temos os resultados para analise de:
- Total investido
- Patrimônio acumulado
- Lucro
- Dividendos mensais
- Distribuição por tipo de FII

## 📈 Resultado do Projeto

A ferramenta proporciona uma visão clara da evolução patrimonial ao longo do tempo, combinando:

- Utilização de matemática financeira
- Organização estrutural de dados
- Automação com funções financeiras
- Visualização gráfica
- Normalização de dados

O modelo foi estruturado com foco em clareza, escalabilidade, flexibilidade e aplicação prática.

## 🧩 Aprendizados

- Aplicação prática de funções financeiras no Excel
- Estruturação de dados em planilhas auxiliares
- Uso de validação para controle de entradas
- Construção de modelo de simulação parametrizado
- Documentação técnica para portfólio no GitHub

## 👩‍💻 Autora

Andrielle Cunha - Intusiasta de Dados
