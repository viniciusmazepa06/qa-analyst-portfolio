# Checklist de Testes de Regressão

Utilize este checklist após uma alteração para verificar se os principais fluxos existentes continuam funcionando.

> Adapte a lista ao impacto da mudança. Um item só deve ser marcado como aprovado após execução e registro de evidência.

## Autenticação
- [ ] Login com credenciais válidas
- [ ] Login com credenciais inválidas
- [ ] Validação de campos obrigatórios
- [ ] Logout encerra a sessão do usuário

## Catálogo de produtos
- [ ] Lista de produtos é carregada corretamente
- [ ] Detalhes do produto exibem as informações esperadas
- [ ] Busca retorna resultados relevantes
- [ ] Busca sem resultados apresenta mensagem adequada

## Carrinho
- [ ] Adicionar produto ao carrinho
- [ ] Alterar quantidade do produto
- [ ] Remover produto do carrinho
- [ ] Subtotal e total são recalculados
- [ ] Carrinho permanece consistente durante a navegação

## Finalização da compra
- [ ] Campos obrigatórios são validados
- [ ] Dados inválidos são rejeitados com mensagem clara
- [ ] Resumo do pedido corresponde aos itens do carrinho
- [ ] Usuário não avança sem preencher informações obrigatórias

## Resumo da execução

| Campo | Valor |
|---|---|
| Build / versão | A preencher |
| Ambiente | A preencher |
| Data da execução | A preencher |
| Responsável | A preencher |
| Aprovados | A preencher |
| Reprovados | A preencher |
| Bloqueados | A preencher |
| Defeitos relacionados | A preencher |

**Importante:** Não marque itens não executados como aprovados. Registre bloqueios e defeitos separadamente.
