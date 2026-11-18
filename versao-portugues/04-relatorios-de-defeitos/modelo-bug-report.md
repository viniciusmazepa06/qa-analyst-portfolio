# Modelo de Relatório de Defeito (Bug Report)

Utilize este modelo para registrar defeitos de forma clara, objetiva e reproduzível.

## [ID-DO-BUG] Título curto e objetivo

- **Ambiente:** [Navegador / Sistema operacional / versão / ambiente]
- **Funcionalidade:** [Funcionalidade afetada]
- **Severidade:** [Crítica / Alta / Média / Baixa]
- **Prioridade:** [Urgente / Alta / Média / Baixa]
- **Status:** [Novo / Em andamento / Corrigido / Reteste / Fechado]
- **Data do registro:** [AAAA-MM-DD]

### Descrição
Descreva o problema observado e seu impacto para o usuário ou para o fluxo de negócio.

### Pré-condições
Informe configurações ou dados necessários antes de reproduzir o problema.

### Passos para reproduzir
1. [Primeira ação]
2. [Segunda ação]
3. [Ação que provoca o problema]

### Resultado esperado
Descreva o comportamento correto.

### Resultado atual
Descreva o comportamento observado.

### Evidências
- Captura de tela ou gravação: [Anexar ou inserir link]
- Logs ou detalhes relevantes: [Adicionar quando disponíveis]

### Observações
Informe frequência, alternativas temporárias, casos relacionados e contexto adicional.

---

## Exemplo ilustrativo

**ID:** BUG-CARRINHO-001  
**Título:** Subtotal do carrinho não é atualizado após alteração da quantidade  
**Severidade:** Alta  
**Prioridade:** Alta

**Descrição:** Neste exemplo simulado, a quantidade do produto é alterada, mas o subtotal exibido permanece igual.

**Passos para reproduzir:**
1. Adicionar um produto disponível ao carrinho.
2. Aumentar sua quantidade.
3. Conferir o subtotal.

**Resultado esperado:** O subtotal reflete a quantidade atual multiplicada pelo preço unitário.

**Resultado atual:** O subtotal permanece com o valor anterior.

**Evidência:** Não disponível — exemplo ilustrativo, não é um defeito observado em sistema real.
