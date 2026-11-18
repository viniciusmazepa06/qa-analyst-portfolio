# Casos de Teste — SauceDemo

**Status inicial de todos os casos:** Não executado.

| ID | Módulo | Cenário | Resultado esperado | Prioridade |
|---|---|---|---|---|
| SD-001 | Login | Login com usuário padrão e senha válida | Acesso à página de produtos | Alta |
| SD-002 | Login | Login com senha incorreta | Acesso negado e mensagem de erro | Alta |
| SD-003 | Login | Enviar formulário sem usuário | Login não realizado e validação apresentada | Média |
| SD-004 | Login | Login com usuário bloqueado | Acesso negado com mensagem apropriada | Alta |
| SD-005 | Catálogo | Abrir catálogo após autenticação | Produtos e informações principais exibidos | Alta |
| SD-006 | Ordenação | Ordenar produtos por preço crescente | Produtos apresentados do menor para o maior preço | Média |
| SD-007 | Carrinho | Adicionar um produto ao carrinho | Produto adicionado e contador atualizado | Alta |
| SD-008 | Carrinho | Remover produto do carrinho | Produto removido e contador atualizado | Alta |
| SD-009 | Carrinho | Abrir carrinho após adicionar produto | Produto e preço correspondem ao item selecionado | Alta |
| SD-010 | Checkout | Avançar sem preencher primeiro nome | Avanço bloqueado com validação | Alta |
| SD-011 | Checkout | Avançar sem preencher sobrenome | Avanço bloqueado com validação | Alta |
| SD-012 | Checkout | Avançar sem preencher código postal | Avanço bloqueado com validação | Alta |
| SD-013 | Pedido | Revisar resumo antes de concluir | Itens e valores correspondem ao carrinho | Alta |
| SD-014 | Pedido | Finalizar compra válida | Mensagem de confirmação é exibida | Alta |
| SD-015 | Sessão | Realizar logout pelo menu | Retorno à tela de login | Média |

## Procedimento detalhado — SD-001

**Título:** Login com credenciais válidas  
**Pré-condição:** Usuário de demonstração disponível.  
**Dados:** `standard_user` / `secret_sauce`

1. Acessar https://www.saucedemo.com/.
2. Preencher o campo Username com `standard_user`.
3. Preencher o campo Password com `secret_sauce`.
4. Acionar Login.

**Resultado esperado:** A página de produtos é exibida e o usuário está autenticado.

**Resultado atual:** A preencher após execução.  
**Status:** Não executado.  
**Evidência:** A adicionar após execução.

## Procedimento detalhado — SD-014

**Título:** Finalizar compra com dados válidos  
**Pré-condições:** Usuário autenticado e pelo menos um produto no carrinho.  
**Dados:** QA / Tester / 00000

1. Abrir o carrinho.
2. Acionar Checkout.
3. Preencher primeiro nome, sobrenome e código postal.
4. Avançar para a revisão.
5. Conferir os itens e valores.
6. Acionar Finish.

**Resultado esperado:** A aplicação apresenta a confirmação de conclusão do pedido.

**Resultado atual:** A preencher após execução.  
**Status:** Não executado.  
**Evidência:** A adicionar após execução.
