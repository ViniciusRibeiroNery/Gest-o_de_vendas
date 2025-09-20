# Gest-o_de_vendas
Projeto criado para  a elaboração de uma planilha de gestão de vendas criada no planilhas/excel para demonstrar conhecimento em funções, análises e automações.

# Projeto Excel: Gestão de Vendas

Este projeto é uma planilha de **Gestão de Vendas** criada para demonstrar habilidades práticas no Excel, desde funções básicas até análises e automações. A planilha permite controlar vendas de produtos, calcular comissões de vendedores e analisar o desempenho geral das vendas.

---

## Estrutura do Projeto

O projeto está dividido em **5 abas principais**, cada uma focando em uma funcionalidade específica do Excel. Até o momento, as etapas concluídas são as duas primeiras abas:

### 1. Aba "Dados de Vendas"
Esta aba armazena os dados brutos de vendas.

**Campos incluídos:**
- Data da Venda
- ID da Venda
- Vendedor
- Produto
- Quantidade Vendida
- Preço Unitário
- Desconto Aplicado (calculado automaticamente)
- Valor Total (calculado automaticamente)

**Funcionalidades aplicadas:**
- Formatação de data, moeda e números.
- Uso da função `SE` para aplicar descontos automaticamente.  
  - Exemplo: se a quantidade vendida for maior que 10, aplica-se um desconto de 5%.
- Cálculo do Valor Total da Venda:
  ```excel
  =Quantidade * Preço Unitário - Desconto

