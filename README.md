# Simulação de Dados para o projeto Impacto Análise de Vendas

Este script em Python gera datasets simulados de uma loja fictícia de eletrônicos, considerando produtos, concorrência, promoções mensais e dados financeiros detalhados. Ele é ideal para fins de análise com ferramentas como Power BI, Excel, Python ou SQL.

---

## Funcionalidades

- Geração de uma base de produtos com preço de venda, custo, ICMS e margem de lucro
- Simulação de preços da concorrência com variação de ±5%
- Simulação de vendas mensais com sazonalidade em datas promocionais (Carnaval, Dia dos Namorados, Black Friday, Natal)
- Cálculo detalhado de Receita Bruta, Impostos, Custo Total e Lucro Líquido
- Exportação dos dados em arquivos `.csv`

---

## Arquivos Gerados

- `produtos.csv`: Informações sobre produtos, categorias, custos e preços.
- `concorrencia.csv`: Preços simulados em lojas concorrentes.
- `vendas_mensais.csv`: Vendas mensais com aplicação de promoções.
- `financeiro.csv`: Análise financeira por produto e mês.

---

## Estrutura dos Dados

### Exemplo de colunas no `financeiro.csv`:

- `ProdutoID`
- `Mes`
- `PrecoVenda`
- `UnidadesVendidas`
- `CampanhaAtiva`
- `DescontoAplicado`
- `Custo`
- `ICMS`
- `ReceitaBruta`
- `Impostos`
- `CustoTotal`
- `LucroLiquido`
- `BaseCalculoICMS`

---

## Como Executar

1. Certifique-se de ter o Python 3 e o `pandas`/`numpy` instalados:
```bash
pip install pandas numpy
