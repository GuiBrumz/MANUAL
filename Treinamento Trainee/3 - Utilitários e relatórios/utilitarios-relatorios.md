# 📊 Sistema de Relatórios e Utilitários

Este documento reúne as informações sobre os **utilitários e relatórios** disponíveis no sistema, detalhando funcionalidades, menus e principais operações.

---

## 1. 🛠️ Utilitários

### 1.1 Contagem e Ajuste de Estoque
Menu: **Utilitários → Contagem Ajuste de Estoque**

**Funcionalidades:**
- **Contagem:** Lista os itens com suas quantidades atuais.
- **Ajuste:** Permite dar entrada ou saída de produtos no estoque.
- **Leitor de código de barras:** Facilita a contagem rápida.
- **Relatórios gerados:**
  - Diferença entre contagem e estoque atual.
  - Quantidades não contadas (apresentadas como 0).
- **Implantação:**
  - Aplicação das quantidades contadas.
  - Possibilidade de filtrar por grupo, subgrupo ou marca.
  - Zerar estoques não contados, se desejado.
- **Importação:**
  - De coletores de dados ou outros dispositivos.
  - Pode importar saldos positivos, negativos ou zerados.
- **Backup e restauração:** Possível salvar e restaurar todo o inventário.

---

## 2. 📑 Gerador de Consultas e Relatórios
Menu: **Utilitários → Gerador de Consultas e Relatórios**

**Funcionalidades:**
- Criação de relatórios específicos conforme solicitação do cliente.
- Relatórios **padrão:** Cadastros, Vendas, Financeiro.
- **Tipos de relatório:**
  - Consulta
  - Relatório em caracteres
  - Relatório gráfico
- **Configurações:**
  - Nome, tamanho do relatório e da fonte.
  - Cabeçalho e SQL para configuração.
  - Seleção de tabelas e campos.
  - Definição de ordenação, filtros e intervalos.
- **Relatórios gráficos:** Requer montagem via SQL, mais complexo, tratado em vídeo específico.
- **Exportação/Importação:** Permite transferir relatórios entre bases de clientes.

---

## 3. 🗂️ Relatórios de Cadastros

### 3.1 Produtos
Menu: **Relatórios → Cadastros → Produtos**

**Principais relatórios:**
- **Lista de Preços:**  
  - Simples ou composto, formato caractere ou gráfico.  
  - Pode mostrar imagens dos produtos.  
  - Filtros: Grupo, Marca, Subgrupo, Itens ativos, Itens com saldo.  
  - Ordenação: Código ou nome.  
  - Quebra por grupo, subgrupo ou marca.
- **Posição de Estoque:**  
  - Quantidades em estoque, saldo atual, saldo mínimo, ponto de pedido.  
  - Considera pedidos de compra, estoque negativo, ativos e saldo positivo.  
- **Registro de Inventário:**  
  - Baseado em custo médio, último custo ou custo com impostos.  
  - Permite verificar valores de estoque para contabilidade.
- **Última Venda:** Relatório de vendas recentes.
- **Composição de Lotes:** Controle de validade e quantidade por lote.
- **Tributação:** Estoque por tipo de tributação (PIS, Cofins, CEST).

### 3.2 Cadastros Complementares
Menu: **Relatórios → Cadastros Complementares**

- Grupos, subgrupos, marcas, códigos fiscais.
- Relatórios detalhando os itens cadastrados.

### 3.3 Clientes e Fornecedores
Menu: **Relatórios → Cadastros → Clientes e Fornecedores**

- **Filtros:** Estado, cidade, vendedor, atividade, período, intervalo de clientes.
- **Relatórios:**
  - Sintético: Código, nome, fantasia, telefone e fax.
  - Analítico: Todas as informações detalhadas.
  - Ficha de crediário.
  - Relacionamento com cliente (previsões de compra).
  - Aniversariantes e clientes sem compras.
  - Pontuação de clientes.

### 3.4 Tabelas de Preços
Menu: **Relatórios → Cadastros → Tabelas de Preços**

- Visualização de todos os produtos cadastrados em uma tabela específica.
- Filtros: Grupo, Subgrupo, Marca, saldo e ativos.
- Quebra por grupo ou nome.

---

## 4. 💰 Relatórios Financeiros

### 4.1 Contas a Pagar
Menu: **Relatórios → Financeiro → Contas a Pagar**

- **Tipos:**
  - Por vencimento ou data do documento.
  - Pagamentos no período.
  - Sintéticos (resumo) ou detalhados.
- **Filtros:** Fornecedor, categoria, subcategoria.
- Identificação de boletos não recebidos.

### 4.2 Boletos e Duplicatas
Menu: **Relatórios → Financeiro → Boletos e Duplicatas**

- Geração e impressão de boletos.
- **Opções:**
  - Por nota fiscal, documento ou intervalo.
  - Boletos cumulativos (várias notas em um boleto).
  - Layouts de impressão variados.
  - Multa, protesto e cobrança com registro.
  - Envio de boletos por e-mail.
- Geração de remessas para transmissão bancária.
- Configuração prévia necessária no **Configurador de Documentos**.

---

## 5. 📌 Relatórios Configurados
Menu: **Relatórios → Configurados**

- Relatórios gerados a partir do **Gerador de Relatórios**.
- Disponíveis para uso pelo cliente.
- Totalmente personalizados conforme solicitação.

---

