# Dashboard de Calibração de Sensores

Este projeto consiste em um dashboard desenvolvido no Power BI para análise de curvas de calibração de sensores, permitindo comparar valores reais e valores medidos, além de avaliar a precisão dos sensores de forma visual e interativa.

---

# Objetivo

O dashboard foi desenvolvido com o objetivo de:

- Analisar o desempenho de sensores calibrados;
- Comparar valores reais e valores medidos;
- Identificar erros médios nas medições;
- Avaliar a precisão média dos sensores;
- Facilitar a interpretação dos dados através de visualizações interativas.

---

# Tecnologias Utilizadas

- Power BI
- DAX
- Excel

---

# Funcionalidades

## Filtro Interativo por Sensor
Permite selecionar individualmente cada sensor para análise específica.

## Cards Dinâmicos
O dashboard apresenta indicadores automáticos:

- Erro Médio
- Precisão Média
- Quantidade de Medições
- Status do Sensor

## Gráfico de Dispersão
Compara:

- Valor Real
- Valor Medido

Além disso, possui linha de tendência para auxiliar na análise da calibração.

## Análise de Erro
Gráfico complementar exibindo o erro médio do sensor selecionado.

## Insight Automático
Sistema de interpretação automática baseado na precisão média do sensor.

---
# Status do Sensor

Classificação automática baseada na precisão média:

| Precisão Média | Status |
|---|---|
| >= 95% | Excelente |
| >= 90% | Bom |
| >= 80% | Regular |
| < 80% | Ruim |

# Métricas Utilizadas

## Erro

```text
| Valor Medido - Valor Real |

```

# Aprendizados

Durante o desenvolvimento deste projeto foram trabalhados conceitos como:

- Visualização de dados;
- Modelagem de dashboards;
- Criação de métricas em DAX;
- Interatividade no Power BI;
- Design de dashboards;

# Autor
Fernanda Pinheiro
- Interpretação analítica de dados.
