# Projeto prático de QA — SauceDemo

**Aplicação:** [SauceDemo / Swag Labs](https://www.saucedemo.com/)  
**Tipo:** Testes funcionais manuais (caixa-preta)  
**Status:** Preparação da execução  
**Versões:** [Português](README.pt-BR.md) | [English](README.en.md)

## Objetivo

Planejar e executar testes manuais em uma aplicação de e-commerce de demonstração, cobrindo autenticação, catálogo, ordenação, carrinho e finalização de compra.

## Ambiente de teste

- Aplicação: https://www.saucedemo.com/
- Navegador: registrar durante a execução
- Sistema operacional: registrar durante a execução
- Data e hora: registrar durante a execução
- Conta principal de demonstração: `standard_user`
- Senha pública da demonstração: `secret_sauce`

As credenciais acima são disponibilizadas para uso no site público de demonstração. Não utilize senhas pessoais ou credenciais de outros serviços.

## Escopo

**Dentro do escopo**
- Login válido e inválido
- Tratamento de usuário bloqueado
- Exibição e ordenação de produtos
- Adição e remoção de itens do carrinho
- Validação de campos obrigatórios no checkout
- Revisão e conclusão do pedido
- Logout

**Fora do escopo**
- Pagamentos reais
- Dados pessoais reais
- Testes de carga ou segurança
- Integrações externas não disponibilizadas pela demonstração

## Estratégia

1. Revisar os cenários e resultados esperados.
2. Executar cada caso no ambiente público.
3. Registrar resultado atual, status e evidência.
4. Abrir relatório apenas para comportamento efetivamente observado e reproduzível.
5. Consolidar resultados e limitações.

## Documentos

- [Plano de testes](test-plan.md)
- [Casos de teste](test-cases.md)
- [Registro de execução](test-execution.md)
- [Modelo de relatório de defeito](bug-reports/bug-report-template.md)
- [Índice de defeitos](bug-reports/README.md)
- [Evidências](evidence/README.md)

## Integridade dos resultados

Os casos começam com status **Não executado**. Nenhum resultado, defeito ou evidência será apresentado como real antes da execução. Comportamentos conhecidos ou intencionais da conta de demonstração não serão classificados automaticamente como defeitos.

## Resultado final

A preencher após a execução real dos casos de teste.
