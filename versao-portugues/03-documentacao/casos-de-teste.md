# Casos de Teste — Aplicação de E-commerce Simulada

> Os casos abaixo são ilustrativos. Ainda não foram executados em uma aplicação real.

| ID | Funcionalidade | Cenário | Resultado esperado | Prioridade |
|---|---|---|---|---|
| CT-LOGIN-001 | Login | Entrar com credenciais válidas | Usuário autenticado | Alta |
| CT-LOGIN-002 | Login | Entrar com senha incorreta | Acesso negado e mensagem clara | Alta |
| CT-LOGIN-003 | Login | Enviar campos obrigatórios vazios | Validação dos campos apresentada | Média |
| CT-CARRINHO-001 | Carrinho | Adicionar produto disponível | Produto aparece com dados corretos | Alta |
| CT-CARRINHO-002 | Carrinho | Aumentar quantidade | Quantidade e subtotal atualizados | Alta |
| CT-CARRINHO-003 | Carrinho | Remover produto | Produto removido e valores recalculados | Média |
| CT-COMPRA-001 | Compra | Continuar com campos obrigatórios preenchidos | Usuário avança para revisão do pedido | Alta |
| CT-COMPRA-002 | Compra | Enviar formulário com campo obrigatório vazio | Envio bloqueado e campo identificado | Alta |
| CT-BUSCA-001 | Busca | Pesquisar produto existente | Produtos correspondentes são exibidos | Média |
| CT-BUSCA-002 | Busca | Pesquisar produto sem correspondência | Mensagem de nenhum resultado é exibida | Baixa |

## Caso detalhado

### CT-CARRINHO-001 — Adicionar produto disponível ao carrinho

- **Prioridade:** Alta
- **Tipo:** Funcional
- **Pré-condições:** O produto está disponível para compra.
- **Dados de teste:** Qualquer produto marcado como disponível.

**Passos**
1. Acessar o catálogo de produtos.
2. Selecionar um produto disponível.
3. Abrir a página de detalhes.
4. Acionar a opção de adicionar ao carrinho.
5. Abrir o carrinho de compras.

**Resultado esperado**

O produto selecionado aparece no carrinho com nome, preço unitário e quantidade inicial corretos.

**Status da execução:** Não executado.
