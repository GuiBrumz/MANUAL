# 📦 Manual de Movimentações: Compras, Vendas e Devoluções

Este documento reúne os principais procedimentos e orientações para utilização dos módulos de **Compras** e **Vendas/Devoluções** no sistema, incluindo campos obrigatórios, regras fiscais e funcionalidades adicionais.

---

## 🛒 Compras

### Fluxo de Entrada de Nota
- Lançar conforme a **nota fiscal de compra do fornecedor**.
- Conferir CFOP (Código Fiscal) com o **escritório contábil**.
- Utilizar a **chave NFe (55)** ou **CTe (57)** para notas eletrônicas.

### CFOP e Chave Eletrônica
- CFOP deve ser validado com o contador.
- Chaves eletrônicas são usadas para identificar notas de forma única.

### Campos de Impostos
- **ICMS, IPI, Substituição Tributária**: definidos nas tributações do produto.
- **Red. ICMS, ICMS, IPI**: na aba **Produtos**.
- **PIS e Cofins**: configurados em `Cadastros > Complementares > Sped PIS/Cofins`.
- **MVA**: vem automaticamente do cadastro do produto.

### Configurações Complementares
- Cadastro de produtos, fornecedores e parâmetros fiscais deve estar atualizado antes do lançamento.

---

## 💰 Movimentações de Compras

### Lançamento da Nota
- Informar todos os campos obrigatórios antes de confirmar.
- Vincular a nota ao fornecedor correto.

### Rateio de Custos (Frete, Seguro)
- Distribuir proporcionalmente os valores de frete e seguro entre os produtos.

### Tratamento de Tributos
- Calcular ICMS, IPI, ST, PIS, Cofins conforme a configuração do produto e operação.

### Controle por Grade e Lote/Série
- Produtos de vestuário e calçados: cadastrar cores e tamanhos (ex.: branca P/M/G/GG).
- Lotes e séries: controlar validade e rastreabilidade.

### Parcelamento e Contas a Pagar
- Configurar parcelas conforme a negociação com o fornecedor.
- Possibilidade de habilitar alerta de estoque mínimo.

---

## 📤 Movimentações de Vendas e Devoluções

### Gerar NF a partir de Cupom Fiscal
1. Selecionar o cupom fiscal.
2. Ir em **Opções > Gerar NF a partir de cupom fiscal**.
3. Confirmar cliente e gerar NF.

### Gerar Devolução a partir de Nota
1. Selecionar a nota.
2. **Opções > Gerar devolução**.
3. Informar código de devolução e CFOP.
4. Definir itens e quantidades a devolver.
5. Gerar NF de devolução.

### Gerar NF a partir de XML
1. **Opções > Gerar NF a partir de XML**.
2. Selecionar arquivo.
3. Conferir produtos e CST.
4. Importar e ajustar CFOP, se necessário.

### Impressão em Sequência
- Permite gerar/imprimir diversas notas em sequência informando intervalo de controle.

### Relatórios e Laudos
- Emitir relatório da nota.
- Imprimir laudos em casos de produtos avariados.

### Clonar Nota
- **Opções > Clonar Nota** para duplicar todos os dados e facilitar emissão recorrente.

### Pré-visualizar DANFE
- Ver a nota antes de transmitir à Receita Federal.

---

