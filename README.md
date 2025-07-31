## 📊 Dashboard de Performance Comercial – BrasAlto

Este projeto simula um dashboard de vendas para a empresa fictícia **BrasAlto**, focada no monitoramento da performance comercial nas regiões **Sul** e **Sudeste** do Brasil. A ferramenta foi construída no Excel com uso de Power Query, Tabelas Dinâmicas e segmentações para facilitar a análise mensal por vendedor, canal, produto e status da venda.

### 🗂 Arquivos no Repositório

| Arquivo                               | Descrição                                                                                                                    |
| ------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------- |
| `Base_Vendas_BrasAlto_Simulada.xlsx`  | Base de dados com todos os registros de vendas simuladas. É o **data source** conectado via Power Query.                     |
| `Dashs_Vendas_BrasAlto_Simulada.xlsm` | Dashboard principal com todos os **cálculos, visualizações e interações**, além de segmentações por data, vendedor e região. |

---

## 🔍 Funcionalidades do Dashboard

* **Filtro por mês e ano da venda**
* **Definição dinâmica da meta mensal (por campo editável)**
* **Comparativo da meta atingida por vendedor**
* **Vendas por canal (atacado, varejo, etc.)**
* **Status das vendas (pago, cancelado, pendente)**
* **Distribuição de vendas por região e por produto**
* Indicadores principais como:

  * Valor bruto total vendido
  * Vendas líquidas (após descontos)
  * Total de pedidos

---

## 🧪 Dados Simulados

* Período: Janeiro a Abril de 2024
* Vendedores: Ana, Bruno, Carlos, Juliana, Rafaela, Tiago
* Canais de Venda: Atacado, Varejo, Marketplace, E-commerce
* Produtos: Barrinha de Frutas, Bebida Funcional, Shot Imunológico, Snack Proteico, Suplemento Natural
* Status: Pago, Cancelado, Pendente
  
---

## 🛠 Como Reproduzir

1. **Baixe os dois arquivos**:

   * `Base_Vendas_BrasAlto_Simulada.xlsx`
   * `Dashs_Vendas_BrasAlto_Simulada.xlsm`

2. **Mantenha ambos na mesma pasta local** (garante que o Power Query encontre a fonte).

3. Abra o arquivo `Dashs_Vendas_BrasAlto_Simulada.xlsm`.

4. Se solicitado, ative o conteúdo e **habilite macros**.

5. Use os filtros na lateral esquerda (Data da Venda e Vendedor) e edite a meta mensal diretamente no campo acima do dashboard.

---

## 💡 Observações

* A coluna de **Porcentagem Atingida da Meta** é limitada a 0–100% para garantir clareza visual.
* Todos os cálculos são realizados dinamicamente com base na meta definida e na tabela de vendas.
* O design do dashboard foi pensado para facilitar o uso por usuários não técnicos, como supervisores comerciais e analistas.

---

## 📎 Tecnologias Utilizadas

* Microsoft Excel (Power Query, Tabelas Dinâmicas, Macros)
* VBA mínimo para interatividade (se aplicável)
* Design responsivo para dashboards
