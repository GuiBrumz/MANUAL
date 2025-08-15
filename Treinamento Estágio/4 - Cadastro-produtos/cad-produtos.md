# 📋 Manual do Sistema de Cadastro e Gestão de Produtos

Este manual descreve todas as funcionalidades do módulo de **Cadastro e Gestão de Produtos**, incluindo formação de preço, estoques, vínculos como similares, agregados, relacionados, preços escalonados e configurações avançadas.

---

## 🛠 Cadastro de Produto

- **Código**: Identificador único do produto.
- **Descrição**: Nome para exibição.
- **Unidade**: UN, KG, LT, etc.
- **Grupo / Subgrupo / Marca**: **Campos obrigatórios** para salvar o produto.
- **Preço de Custo**: Valor de compra.
- **Margem de Lucro**: Percentual aplicado sobre o custo.
- **Preço de Venda**: Calculado automaticamente.

💡 **Dica**: Sempre preencha todos os campos obrigatórios antes de salvar.

---

## 📦 Estoque

- Visualização das quantidades em estoque.
- Movimentações de entrada e saída.
- Filtros por produto, código ou categoria.
- Definição de **estoque mínimo** para cada produto.
- Possibilidade de **notificar** quando o estoque está próximo ou abaixo do mínimo.  
  **Para habilitar:**  
  `Parâmetros > Movimentações de Produtos > Notificar Estoque Mínimo`  
  As notificações serão exibidas no **Master PDV**.

---

## 🎯 Grade de Produtos

**Função**:  
Utilizada por empresas que trabalham com confecções e calçados para organizar variações de cores e tamanhos.

**Exemplo de Uso**:
- Produto **Regata** → Grade: Branca P, Branca M, Branca G, Branca GG, Azul P, Azul M...
- Produto **Tênis** → Grade: 38, 39, 40, 41, 42 em diferentes cores.

---

## 🏷 Formação de Preço

- Informe **Preço de Custo**.
- Defina **Margem de Lucro**.
- O sistema calcula automaticamente o **Preço de Venda**.

---

## 🔄 Produtos Similares

Permite vincular produtos diferentes que podem substituir-se na venda.

---

## ➕ Produtos Agregados

Permite que ao vender um produto, outro seja automaticamente sugerido ou adicionado.

---

## 🔗 Produtos Relacionados

Relaciona produtos que costumam ser comprados juntos, mas sem adição automática.

---

## 📇 Mais Códigos de Barras

Permite cadastrar códigos de barras adicionais para o mesmo produto.

---

## 📊 Preço Escalonado

Define preços diferentes para quantidades diferentes do mesmo produto.

---

## 💰 Royalties

Configura a porcentagem de royalties sobre o valor de venda.

---

## 🖼 Imagem do Produto

**Para habilitar a exibição de imagens**:  
`Parâmetros > Venda > Exibir Imagem > Grupo de Produtos ou Produtos`

---

## ⚖ Regras de Tributação

- Após a venda do produto no dia, **não é possível alterar a tributação** desse produto.  
  Essa regra garante a integridade fiscal e evita divergências em relatórios.

---

## 🔧 Equipamentos no Cadastro de Cliente

- Para adicionar o campo **Equipamentos** no cadastro de cliente:  
  `Parâmetros > Ordem de Serviço > Veículo ou Equipamento`

---

## 📌 Observações Finais

- Todas as alterações devem ser salvas antes de sair da tela.
- Utilize filtros e buscas para localizar rapidamente os produtos.
- Mantenha preços e estoques sempre atualizados para evitar divergências no caixa.

---