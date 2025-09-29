# Gestão de Vendas

Projeto criado para a elaboração de uma planilha de **Gestão de Vendas** no Excel/Planilhas Google, com o objetivo de demonstrar conhecimento em funções, análises e automatizações.

## Objetivo
Construir uma planilha fictícia de **Gestão de Vendas** que utilize diversas funcionalidades do Excel para:

- Controlar vendas de produtos.  
- Calcular comissões de vendedores.  
- Analisar o desempenho geral de vendas.  
- Gerar relatórios e visualizações com gráficos e tabelas dinâmicas.  

## Estrutura do Projeto
O projeto está dividido em **5 abas principais**, cada uma focada em uma habilidade específica do Excel.  
Até o momento, foram concluídas as **três primeiras abas**:  

---

### 1. Aba "Dados de Vendas"
Responsável pelo armazenamento dos dados brutos de vendas.  

**Campos incluídos:**  
- Data da Venda  
- ID da Venda  
- Vendedor  
- Produto  
- Quantidade Vendida  
- Preço Unitário  
- Desconto Aplicado (automático)  
- Valor Total (automático)  

**Funcionalidades aplicadas:**  
- Formatação de datas, moedas e números.  
- Uso da função SE para aplicar descontos automaticamente (ex.: acima de 10 unidades, desconto de 5%).  
- Cálculo automático do valor total da venda.  

---

### 2. Aba "Comissões"
Responsável pelo cálculo das comissões dos vendedores.  

**Campos incluídos:**  
- ID da Venda  
- Vendedor  
- Valor Total da Venda  
- Comissão (%)  
- Comissão Final  

**Funcionalidades aplicadas:**  
- PROCV para buscar o valor total da venda na aba *Dados de Vendas*.  
- SE para definir a comissão:  
  - Vendas acima de R$ 1.000 → comissão de 10%  
  - Vendas até R$ 1.000 → comissão de 5%  
- Cálculo automático da comissão final.  

---

### 3. Aba "Resumo de Vendas por Vendedor"
Consolida e resume as vendas de cada vendedor.  

**Campos incluídos:**  
- Vendedor  
- Total de Vendas  
- Comissão Total  
- Total de Vendas por Produto  

**Funcionalidades aplicadas:**  
- Lista única de vendedores (UNIQUE / Remover duplicatas).  
- SOMASES para calcular:  
  - Total de vendas por vendedor.  
  - Comissão total por vendedor.  
  - Total de vendas por produto.  
- Criação de Tabela Dinâmica para consolidar resultados.  
- Criação de Gráfico de Barras para visualizar o desempenho de cada vendedor.  

---

## Próximos Passos
As próximas abas a serem implementadas são:  

4. Análise de Vendas por Produto → Tabela Dinâmica, Lucro e Gráfico de Pizza.  
5. Relatório de Performance → Dashboard com gr
