# 🎯 Business Analytics – Super Brinquedos

Este projeto foi desenvolvido como parte de um case da iMaps para modernização da plataforma de Business Intelligence da loja Super Brinquedos. O objetivo central é fornecer análises estratégicas para o período do Dia das Crianças, otimizando vendas, margens e a tomada de decisão.

---

## 🧾 Visão Geral

A loja Super Brinquedos, em preparação para a alta temporada, busca entender melhor o comportamento de vendas para definir ações mais assertivas. O projeto visa entregar um painel visual dinâmico com indicadores relevantes para gestores, focando em volume de vendas, margem de lucro e desempenho de produtos e vendedores.

---

## 📁 Estrutura do Repositório
- /scripts/ → Scripts .qvs organizados por etapa (ETL, Métricas, Dashboards)
- /qvd/ → Armazenamento de arquivos intermediários
- /documentacao/ → Dicionário de dados, regras de negócio, plano de ação
- /export/ → Backup do app Qlik (.qvf ou zip)
- /dados/ → Arquivos CSV: fato_vendas, dim_produto, dim_vendedor
- README.md → Este documento
---

## 📊 Indicadores e Análises Entregues

- Produtos campeões de venda
- Produtos com melhor e pior margem
- Evolução de vendas por:
  - Volume
  - Valor R$
  - Margem %
- Mix de produtos ideal: maior valor + margem
- Crescimento de vendas (mensal e acumulado)

---

## 📐 Regras de Cálculo

- Margem = valor_total - custo_venda
- Margem % = (valor_total - custo_venda) / valor_total

## 🛠️ Dados Utilizados
### Os dados foram fornecidos via CSV extraídos do ERP da empresa:
- fato_vendas.csv: volume, valor e custo por venda
- dim_produto.csv: atributos de produtos
- dim_vendedor.csv: atributos de vendedores
