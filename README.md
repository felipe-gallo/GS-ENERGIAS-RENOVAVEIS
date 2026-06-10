# EcoSpace Monitoramento

## Descrição

O EcoSpace Monitoramento é um sistema desenvolvido em Python para simular o monitoramento de uma missão espacial experimental. O projeto analisa informações relacionadas à temperatura, energia, potência, comunicação e captação de energia solar, permitindo acompanhar as condições operacionais da missão.

O sistema foi desenvolvido com foco em energias renováveis e sustentabilidade, utilizando estruturas de programação para realizar análises automáticas, gerar recomendações e auxiliar na tomada de decisões durante a operação da missão.

---

## Integrantes 
 Felipe Gallo RM: 569680 
 Jun Uehara RM: 570537 

---
## Objetivo

Desenvolver uma solução capaz de monitorar e analisar dados de uma missão espacial experimental, aplicando conceitos de energia, potência, energias renováveis e sustentabilidade.

---

## Funcionalidades

* Cadastro de dados da missão.
* Monitoramento de temperatura.
* Monitoramento do nível de energia.
* Monitoramento da potência consumida.
* Monitoramento da comunicação.
* Monitoramento da captação de energia solar.
* Análise automática das condições da missão.
* Geração de recomendações automáticas.
* Relatório de sustentabilidade.
* Histórico de leituras registradas.
* Visualização gráfica dos dados.

---

## Conceitos Utilizados

### Estruturas de Dados

Foi utilizada uma lista para armazenar o histórico das leituras realizadas durante a missão. Cada leitura é armazenada em um dicionário contendo todas as informações monitoradas.

### Estruturas de Decisão

Foram utilizados comandos `if`, `elif` e `else` para analisar os dados inseridos pelo usuário e determinar a situação da missão.

Exemplo:

* Temperatura baixa → condição segura.
* Temperatura média → atenção.
* Temperatura alta → risco de superaquecimento.

### Repetição

Foi utilizado o comando `while` para manter o menu principal em execução até que o usuário escolha encerrar o sistema.

Também foi utilizado o comando `for` para percorrer o histórico de leituras e gerar análises completas.

### Funções

O sistema foi dividido em funções para facilitar a organização do código.

Principais funções:

* Inserir dados.
* Analisar leituras.
* Exibir status atual.
* Gerar análise completa.
* Exibir gráficos.
* Gerar relatório de sustentabilidade.
* Executar o menu principal.

### Tomada de Decisão Automatizada

O sistema utiliza regras simples para avaliar os dados da missão e apresentar recomendações automáticas.

Exemplos:

* Energia baixa → recomendar economia de energia.
* Comunicação com falha → indicar necessidade de verificação.
* Potência elevada → recomendar redução de consumo.
* Baixa energia solar → recomendar melhoria na captação solar.

### Visualização de Dados

Foi utilizada a biblioteca Matplotlib para criar gráficos que permitem visualizar a evolução dos indicadores monitorados.

---

## Bibliotecas Utilizadas

* Matplotlib

---

## Estrutura Geral do Projeto

O sistema é dividido em:

1. Apresentação do projeto.
2. Criação do histórico de leituras.
3. Inserção de dados.
4. Análise inteligente.
5. Consulta do status atual.
6. Análise completa da missão.
7. Geração de gráficos.
8. Relatório de sustentabilidade.
9. Menu principal.

---

## Resultado Esperado

Ao executar o sistema, o usuário poderá registrar dados da missão e receber uma análise automática sobre o estado operacional dos sistemas monitorados.

Além disso, será possível acompanhar gráficos, consultar o histórico de registros e visualizar relatórios relacionados à sustentabilidade e ao uso de energias renováveis.

---

## Autor

Projeto desenvolvido para fins acadêmicos utilizando Python e Google Colab.
