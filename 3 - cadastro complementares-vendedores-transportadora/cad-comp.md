# 📋 Cadastros Complementares

Este documento descreve as funcionalidades de **Cadastros Complementares** do sistema, incluindo grades de cores, padronizados, formas de pagamento, indexadores, tipos de pagamento, grupos, vendedores e transportadores.

---

## 🎨 1. Grades de Cores
**Menu:** Cadastros Complementares > Grades de Cores  
**Função:** Cadastrar cores para produtos com variações (ex.: confecções, calçados).

**Cadastro:**  
- Clique em **Novo**  
- Informe o **nome da grade** e a **cor**  
- Clique em **Gravar**  

**Uso:**  
- No cadastro de produtos → aba **Estoque** → selecione **Grade** → escolha cor e tamanho.

---

## ⚙️ 2. Padronizados
**Menu:** Cadastros Complementares > Padronizados  
**Função:** Criar conjuntos de produtos que compõem um item principal (ex.: motor de carro, materiais de construção).

**Cadastro:**  
1. Clique em **Novo**  
2. Informe o **nome do padronizado**  
3. Adicione os produtos que compõem o conjunto e informe as **quantidades**  
4. Clique em **Gravar**

**Uso:**  
- Disponível em **Ordem de Serviço** e **Pedidos de Venda**  
- Selecionar padronizado → sistema adiciona automaticamente os produtos relacionados  
- Permite ajustes de quantidades e edição do padronizado.

---

## 💰 3. Formas de Pagamento
**Menu:** Cadastros Complementares > Formas de Pagamento  
**Função:** Define formas de pagamento, incluindo juros, descontos, parcelas mínimas e acréscimos.

**Cadastro:**  
- Novo → informe **descrição** da forma de pagamento  
- Configure **coeficiente** (juros/desconto) e **valor de acréscimo** (opcional)  
- Configure **parcelas mínimas, dias fixos, pré-fixados ou limite**  
- Defina **categoria** e **subcategoria financeira**  
- Clique em **Gravar**  

**Uso:**  
- Geração automática de parcelas no sistema de vendas  
- Controle de entrada e vencimentos em contas a receber.

---

## 📈 4. Indexadores
**Menu:** Cadastros Complementares > Indexadores  
**Função:** Atualiza preços automaticamente com base em índices externos (ex.: joalherias).

**Cadastro:**  
- Novo → informe o **nome do indexador**  
- Selecione **base de cálculo** (custo, venda ou venda indexada)  
- Clique em **Gravar**  

**Uso:**  
- No cadastro de produtos, vincule o indexador  
- Informe o **fator de indexação**  
- Atualize valores diariamente para ajustar custo e venda automaticamente.

---

## 💳 5. Tipos de Pagamento
**Menu:** Cadastros Complementares > Tipos de Pagamento  
**Função:** Define como o cliente fará o pagamento (à vista, a prazo, cartão de crédito/débito).

**Cadastro:**  
- Novo → informe o **nome do tipo de pagamento**  
- Configure **posição da impressora fiscal**, categoria/subcategoria, histórico padrão  
- Informe **cliente padrão** e bandeira (para cartões)  
- Clique em **Gravar**

**Uso:**  
- Tipos de pagamento aparecem em PDV, contas a receber e finalização de vendas.

---

## 🗂️ 6. Grupos
**Menu:** Cadastros Complementares > Grupos  
**Função:** Organiza produtos, serviços, pedidos e ordens de serviço.

**Cadastro:**  
- Novo → informe **nome** e **referência**  
- Configure onde aparecerá (produtos, pedidos, OS, etc.)  
- Opcional: adicionar **imagem representativa**  
- Clique em **Gravar**

**Uso:**  
- Exibição de imagens do grupo em vendas e consulta de produtos, se habilitado nos parâmetros.

---

## 👤 7. Vendedores
**Menu:** Cadastros > Vendedores  
**Função:** Cadastro de vendedores e colaboradores, incluindo controle de **comissões** e **metas**.

**Cadastro:**  
- Novo → informe **nome, endereço, e-mail**, comissão sobre vendas (à vista ou a prazo)  
- Configure **dia pré-fixado**, categoria e subcategoria para contas a pagar  
- Associe vendedor como **fornecedor** para controle de comissões  
- Configure **metas** e **tabelas de preços** acessíveis  
- Clique em **Gravar**

**Uso:**  
- Comissões calculadas automaticamente  
- Controle de descontos máximos por vendedor  
- Metas e tabelas de preços vinculadas ao vendedor.

---

## 🚚 8. Transportadores
**Menu:** Cadastros > Transportadores  
**Função:** Cadastro de transportadoras para envio de produtos.

**Cadastro:**  
- Novo → informe **nome, endereço, cidade, telefone, e-mail, CNPJ/CPF, inscrição estadual**  
- Marque opção de **Inativo** se necessário  
- Aba **Placas**: informe **placas** e **seguros**  
- Clique em **Gravar**

**Uso:**  
- Disponível em movimentações de vendas e cadastro de clientes  
- Permite seleção de transportador e placa vinculada no processo de venda.

---
