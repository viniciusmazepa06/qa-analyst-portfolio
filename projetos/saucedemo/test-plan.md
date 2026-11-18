# Plano de Testes — SauceDemo

## 1. Identificação

- Projeto: QA Practice — SauceDemo
- Aplicação: https://www.saucedemo.com/
- Modalidade: Testes funcionais manuais
- Abordagem: Caixa-preta
- Status: Preparação da execução

## 2. Objetivos

- Verificar os fluxos essenciais de compra.
- Validar respostas a entradas válidas e inválidas.
- Confirmar atualização de informações do carrinho e do pedido.
- Registrar resultados reproduzíveis e evidências.
- Identificar defeitos observados, sem presumir falhas.

## 3. Itens de teste

1. Autenticação
2. Catálogo e detalhes de produtos
3. Ordenação de produtos
4. Carrinho
5. Formulário de checkout
6. Revisão do pedido
7. Confirmação e logout

## 4. Tipos de teste

- Funcional positivo
- Funcional negativo
- Validação de campos
- Navegação
- Regressão básica do fluxo de compra

## 5. Dados de teste

A aplicação disponibiliza contas próprias para demonstração. Para o fluxo principal, utilizar `standard_user` com a senha pública `secret_sauce`. Para o cenário de conta bloqueada, utilizar `locked_out_user` com a mesma senha pública. Não utilizar dados pessoais reais.

Para o formulário de checkout, utilizar dados fictícios, por exemplo:
- Primeiro nome: QA
- Sobrenome: Tester
- Código postal: 00000

## 6. Critérios de entrada

- Aplicação acessível.
- Navegador atualizado.
- Casos de teste revisados.
- Ambiente e data registrados.

## 7. Critérios de saída

- Todos os casos planejados executados ou justificados como bloqueados.
- Resultados atuais registrados.
- Evidências associadas aos casos relevantes.
- Defeitos reproduzíveis documentados.
- Resumo final atualizado.

## 8. Riscos e limitações

- O ambiente é uma demonstração pública e pode mudar ou ficar indisponível.
- Comportamentos de contas especiais podem ser intencionais e precisam ser avaliados conforme o objetivo do cenário.
- Não há requisito formal do produto fornecido; resultados devem ser comparados ao comportamento esperado descrito neste exercício.

## 9. Entregáveis

Plano, casos de teste, log de execução, relatórios de defeito e evidências.
