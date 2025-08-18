# Sistema de Gestão - Movimentações e Financeiro

Este documento detalha os módulos de **Movimentações** e **Financeiro** do sistema, com orientações sobre lançamentos, pagamentos, quitações e relatórios.

---

## 🛒 Movimentações de Pedidos

### Pedidos de Compra
- Menu: **Movimentações → Pedidos → Pedidos de Compra**
- Funções:
  - **Novo Pedido**: lançar itens desejados, informar fornecedor, quantidade, valor unitário e tributações.
  - **Previsão de chegada/faturamento**: informar datas estimadas de entrega e faturamento.
  - **Cotação Online**:
    - Gera link para fornecedores cadastrados.
    - Cada fornecedor informa preço dos produtos.
    - Importação automática da cotação para o sistema.
  - **Visualização de estoque e histórico**:
    - Estoque atual, mínimo, reservas, último custo e média de venda.
    - Comparativo de preço em filiais.

### Importação e Sugestão de Compra
- Filtragem por grupo, subgrupo ou estoque mínimo.
- Sugestão baseada na média de vendas dos últimos 3 meses.
- Possibilidade de ajustar percentual adicional (+/-).

### Cotação de Preço
- Permite comparar preços entre fornecedores.
- Opções:
  - Gerar pedido pelo **mais barato de cada fornecedor**.
  - Selecionar um fornecedor específico para todos os produtos.
- Confirmação de exclusão do pedido original antes de gerar novos pedidos.

---

## 💰 Financeiro

### Contas a Receber
- Menu: **Financeiro → Contas a Receber**
- Lançamentos automáticos: vendas a prazo caem automaticamente.
- Lançamentos manuais:
  - Novo → número da nota, cliente, vencimento, valor, categoria, subcategoria, histórico/observações.
- **Marcação especial**:
  - Títulos negociados com banco.
  - Títulos em cartório ou protestados (indicados visualmente no sistema).
- Pagamento:
  - **Por banco**: gera crédito na conta corrente.
  - **Por caixa**: registra movimento de caixa.

- **Múltiplas Contas**:
  - Permite lançar várias parcelas automaticamente.

---

### Contas a Pagar
- Menu: **Financeiro → Contas a Pagar**
- Lançamentos automáticos: compras registradas automaticamente pelo sistema.
- Lançamentos manuais:
  - Novo → fornecedor, número do documento, data, valor, categoria/subcategoria, histórico/observações.
  - Boletos e cheques pré-datados podem ser informados.
- Pagamento:
  - **Por banco**: baixa direto na conta corrente.
  - **Por caixa**: baixa no movimento de caixa.
- **Múltiplas Parcelas**:
  - Permite lançar várias parcelas com intervalo de dias e valores automáticos.

---

### Quitação de Múltiplas Contas
- Menu: **Financeiro → Quitação de Múltiplas Contas**
- Permite dar baixa em contas a receber e a pagar.
- Formas de quitação:
  1. **Documentos selecionados**: quitar um ou mais títulos.
  2. **Por valor limite**: paga parcialmente até atingir o valor informado.
  3. **Por data limite**: quita todas as parcelas até determinada data.
- Recursos:
  - Recibo unificado para múltiplas parcelas.
  - Aplicação de desconto, juros, multa.
  - Exclusão de documento (não remove do contas a receber).

- **Renegociação de dívida**:
  - Inserção de entrada (dinheiro/cartão), número de parcelas, vencimento fixo e juros.
  - Recalcula valor total da dívida considerando juros até o último pagamento.

---

### Arquivo Magnético, Recibos e Cartões
- **Arquivo Magnético**: leitura de retorno de boletos enviados ao banco.
- **Operações com Recibo**: cancelamento e reimpressão de pagamentos feitos por engano.
- **Conciliação de Cartões**:
  - Importação de arquivo de administradora de cartões (TEF).
  - Conferência de valores pagos por cartão.

---

### Movimento Bancário
- Menu: **Financeiro → Movimento Bancário**
- Objetivo: registrar todas entradas e saídas da conta corrente.
- Fontes:
  - Automático: contas a receber/pagar, boletos, tarifas.
  - Manual: novos lançamentos (tarifas, receitas diversas).
- Campos principais:
  - Conta corrente, tipo de documento, número, data, categoria/subcategoria, valor.
- Status de compensação: indica conferência do lançamento.
- Consulta de saldos e lançamentos por conta.

---

## 📊 Dicas Visuais
- **Cores e marcações**:
  - Parcela em cartório: **preto**.
  - Recebimento parcial: **amarelo**.
- **Recibos unificados**: simplificam impressão para múltiplas parcelas.
- **Relatórios e filtros**: essencial para acompanhamento de clientes e fornecedores.

---

> Este README contempla todos os processos principais de movimentação e financeiro do sistema, facilitando treinamento de usuários e registro de boas práticas.

