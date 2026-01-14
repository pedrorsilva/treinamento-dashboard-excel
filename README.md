# Dashboard de Vendas (Treinamento)

## 📊 Visão geral

Este repositório contém um **dashboard de vendas em Excel** desenvolvido **exclusivamente para fins de treinamento e estudo**, sem qualquer vínculo com dados reais de clientes ou resultados comerciais.

O objetivo é praticar organização, modelagem e visualização de dados, usando um cenário simulado de assinaturas de serviços com diferentes planos e add-ons.

## 🎯 Objetivos do projeto

- Demonstrar como estruturar dados de assinaturas/vendas em uma base única.   
- Criar um dashboard em Excel com foco em análise por **Subscription Type**.   
- Utilizar recursos nativos do Excel (tabelas, fórmulas, gráficos e detalhamentos) em um contexto guiado de treinamento.   
- Servir como material de apoio para estudo de dashboards e construção de relatórios gerenciais.   

> **Importante:** Todos os dados presentes no arquivo são **fictícios** e foram gerados apenas para aprendizagem. 

## 📁 Estrutura dos arquivos

| Arquivo                     | Descrição                                                                                 |
|-----------------------------|-------------------------------------------------------------------------------------------|
| `DashboardTreinamento.xlsx` | Arquivo Excel com base de dados, abas de apoio e dashboard de vendas para treinamento.  |

Dentro do arquivo Excel existem, entre outras, as seguintes abas principais: 

- **Assets**: paleta de cores e referências visuais utilizadas no dashboard.
- **Bases**: planilha contendo dados fictícios.
- **Cálculos**: planilha com os cálculos e tabelas dinâmicas aplicadas aos dados existentes
- **Dashboard**: página principal com os indicadores consolidados para análise por período e por plano.   

## 📊 Dados utilizados (simulados)

A base representa um conjunto fictício de assinantes com as seguintes informações principais: 

- `Subscriber ID`: identificador do assinante.  
- `Name`: nome do assinante.  
- `Plan`: tipo de plano (Standard, Core, Ultimate etc.).   
- `Start Date`: data de início da assinatura, distribuída ao longo de 2024.   
- `Subscription Type`: periodicidade (Monthly, Quarterly, Annual).   
- `EA Play Season Pass` e `Minecraft Season Pass`: indicação se o cliente possui esses add-ons e seus respectivos valores.   
- `Coupon Value` e `Total Value`: valores de cupom/desconto e valor total da assinatura.   

Esses dados permitem: 

- Somar valores por plano, período e tipo de assinatura.  
- Detalhar segmentos específicos (por exemplo, “Soma de EA Play Season Pass - Plan: Standard, Subscription Type: Annual”).   

## 🧪 Natureza de treinamento

Este dashboard é um **artefato de treinamento**, não um produto de BI oficial: 

- Todos os dados são **simulados** e não representam clientes reais.   
- A estrutura pode ser modificada livremente para testes, estudos e experimentos.  
- É adequado para:
  - estudar fórmulas de agregação (SUMIF, SUMIFS, COUNTIF etc.);  
  - criar e ajustar gráficos e painéis;  
  - testar novas visões de negócio sem qualquer risco operacional.   

Caso deseje evoluir o projeto, é possível incluir no futuro: 

- Gráficos adicionais.  
- Novas abas de cálculo para análise mensal ou anual.  
- Versões com dados importados de sistemas reais (mantendo este arquivo como ambiente de laboratório).  

