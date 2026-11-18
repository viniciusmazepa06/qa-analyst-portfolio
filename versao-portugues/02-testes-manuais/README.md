# Testes manuais

Esta seção demonstra uma abordagem estruturada de testes manuais usando uma aplicação de e-commerce fictícia e independente.

## Abordagem de testes

- Analisar requisitos e critérios de aceite antes da execução.
- Cobrir fluxos positivos, negativos, limites e alternativas.
- Priorizar jornadas críticas e riscos de maior impacto.
- Registrar pré-condições, dados, passos e resultados esperados.
- Reunir evidências claras e documentar defeitos reproduzíveis.

## Exemplos de cobertura

| Funcionalidade | Validações |
|---|---|
| Login | Credenciais válidas, senha incorreta e campos vazios |
| Catálogo | Exibição de produtos, busca, filtros e detalhes |
| Carrinho | Adicionar, remover, alterar quantidade e calcular total |
| Finalização da compra | Campos obrigatórios, validação de endereço e resumo do pedido |
| Sessão | Navegação, encerramento e comportamento após expiração |

## Exemplo de cenário

**ID:** CT-LOGIN-001  
**Título:** Realizar login com credenciais válidas  
**Prioridade:** Alta  
**Pré-condições:** Existe uma conta de teste ativa.

**Passos:**
1. Acessar a página de login.
2. Informar um e-mail válido.
3. Informar a senha correspondente.
4. Acionar a opção de entrar.

**Resultado esperado:** O usuário é autenticado e direcionado à página prevista após o login.

**Status da execução:** Não executado — caso de teste ilustrativo.
