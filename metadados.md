# 📚 Metadados – Super Brinquedos

## 🗂️ Tabela: dim_produto

| Campo | Descrição |
|-------|------------|
| dim_produto_id | Identificador único do produto |
| nome_produto | Nome ou informação relacionada ao produto |
| categoria | Categoria geral do produto |
| subcategoria | SubCategoria geral do produto |

## 🗂️ Tabela: dim_vendedor

| Campo | Descrição |
|-------|------------|
| dim_vendedor_id | Identificador único do vendedor |
| nome_vendedor | Nome do vendedor |
| genero_vendedor | Atributo do vendedor |

## 🗂️ Tabela: fato_vendas

| Campo | Descrição |
|-------|------------|
| data_venda | Data da venda |
| dim_produto_id | Identificador único do produto |
| dim_vendedor_id | Identificador único do vendedor |
| quantidade | Quantidade de unidades vendidas |
| valor_total | Valor total da venda (R$) |
| custo_venda | Custo da venda para a empresa |
