# 📋 Parâmetros do Sistema - Empresa

Este documento descreve os **parâmetros específicos da empresa** dentro do sistema, organizados por abas e funcionalidades. Serve como guia para configuração e utilização.

---

## 1. Movimentação de Produtos

Local: **Utilitários → Parâmetros do Sistema → Parâmetros Específicos da Empresa → Movimentação de Produtos**

### ⚙️ Configurações principais:
- **Parcelamento de IPI**: definir se será na primeira parcela ou em todas.
- **Estoque mínimo**: avisar ao atingir ou passar o estoque mínimo.
- **Preço dos produtos**: buscar tabela de preço ou definir manualmente.
- **Estoque negativo**: permitir ou não vendas com saldo negativo.
- **Cálculo de custo**:
  - Calcular no lançamento da nota de compra.
  - Considerar ICMS para empresas do regime normal ou Simples.
  - Não considerar IPI se necessário.
  - Atualização de preços de custo e venda no cadastro (geralmente desmarcado para supermercados).
- **Origem da comissão**: selecionar se será por vendedor ou tabela de preço.
- **Cálculo do custo médio**: baseado em custo ou custo com impostos.
- **Média de vendas**: exibir média dos últimos X meses (padrão: 3 meses).
- **Controle de lotes**:
  - Utilizar sempre o lote mais antigo ou selecionar manualmente.
  - Acrescentar número e validade dos lotes ao nome do produto.
  - Alterar nomenclatura para outros ramos (ex.: número de série).
- **Cálculo do saldo de estoque**:
  - Considerar pedidos de compra, venda, ordem de serviço e transferência.
- **Controle de grades**: ativar para produtos com cores e tamanhos diferentes.
- **Produtos controlados**: habilitar licenciamento se necessário.

---

## 2. Venda

Local: **Utilitários → Parâmetros do Sistema → Parâmetros Específicos da Empresa → Venda**

### ⚙️ Configurações principais:

#### 2.1 Modelos de Nota
- Modelos disponíveis: 55 (NF-e), 01 (nota fiscal comum), 65 (cupom eletrônico), etc.
- **Série e numeração**: fornecido pelo escritório de contabilidade.
- Modelo padrão: selecionado automaticamente em vendas e devoluções.

#### 2.2 Observações e PDV
- Observação padrão: texto que aparecerá automaticamente em vendas.
- Cliente padrão: geralmente consumidor final (código 1).
- Exibição de imagem: por produto ou grupo.
- Código fiscal padrão e CFOP: configurável para vendas.
- Mensagem promocional: texto exibido no rodapé do cupom fiscal.

#### 2.3 Cupom Fiscal
- Venda rápida: F6 fecha venda direto na forma de pagamento.
- Solicitar CPF/CNPJ: opcional, a partir de valor configurado.
- Ignorar "X" como multiplicador: evita conflito com códigos alfanuméricos.
- Desconto máximo: configurável por vendedor ou produto.
- Impressão de carnê ou contrato de venda a prazo: opcional.
- Preenchimento automático da data/hora da saída.
- Rodapé do cupom: até 6 opções personalizáveis.

#### 2.4 TEF
- Bloqueio de clientes inadimplentes: bloquear ao selecionar ou na venda.
- Bloqueio de produtos inativos.
- Identificação de veículo: placa e quilometragem no cupom fiscal.
- Integração com balança e leitor de código de barras.
- Controle de grades: etiquetas, cor, tamanho e código do produto.

---

## 3. Geral

Local: **Utilitários → Parâmetros do Sistema → Parâmetros Específicos da Empresa → Geral**

### ⚙️ Configurações principais:
- Máscaras para quantidade e valor.
- Busca por código de barras.
- Consulta automática nos cadastros.
- Paginação das consultas.
- Exclusão automática de logs.
- Código padrão do sistema: alfanumérico.
- Impressora padrão do sistema.
- Quantidade de registros e manutenção de logs (ex.: 60 registros por 90 dias).
- Backup do sistema: lembrete automático.

---

## 4. Emissão de NFe

Local: **Utilitários → Parâmetros do Sistema → Parâmetros Específicos da Empresa → Emissão de NFe**

### ⚙️ Configurações principais:
- Habilitar emissão de NF-e, NFC-e ou NFS-e.
- Agrupar produtos/serviços por referência ou quantidade.
- Enviar nome resumido do produto (cadastrado no produto).
- Exigir dados obrigatórios:
  - Cadastro de clientes (CPF, telefone, endereço, etc.)
  - Cadastro de produtos (NCM, código do produto, etc.)
- Remetente isento de ICMS interestadual: marcar se aplicável.
- Impressão da nota:
  - Tipo: retrato ou paisagem.
  - Contingência: habilitar para emissão offline.
- Configuração do caminho de arquivos PEf (Master NFe): onde os arquivos da nota são gerados e buscados.
- Notas de serviço: definir local padrão (emitente ou tomador).
- Cupom eletrônico: habilitar NFC-e para consumo.
- Reimpressão de notas: IP e porta de comunicação necessários.
- Envio de informações adicionais: vendedor, origem da venda, pedido de distribuição, CNPJ/CPF do autorizador.

---

## 5. Frente Eletrônica de Fundos (TEF)

Local: **Utilitários → Parâmetros do Sistema → Parâmetros Específicos da Empresa → Frente Eletrônica de Fundos**

### ⚙️ Configurações principais:
- Habilitar TEF para transações com cartão.
- Selecionar driver e gerenciador padrão.
- Configurar bandeira do cartão (Banrisul, CECAP, etc.).
- Lançamento de valores:
  - Receitas/Entradas.
  - Código da loja.
  - Movimento de caixa ou contas a receber.
- Cada gerenciador possui configurações específicas: seguir documentação do fornecedor.