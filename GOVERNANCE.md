# ⚖️ Modelo de Governança JusTech

A governança é o coração da nossa DAO. Utilizamos um sistema híbrido para garantir agilidade e segurança.

## Processo de Proposta (JIP - JusTech Improvement Proposal)

### Fase 1: Temperatura (Discord)
Qualquer ideia deve ser discutida primeiro no canal `#governance-chat` do Discord. É uma fase informal para receber feedback inicial.

### Fase 2: Rascunho & Discussão (Forum)
Se a ideia tiver apoio, o autor deve criar um tópico no Discourse seguindo o template padrão:
*   **Título**: JIP-001: [Nome da Proposta]
*   **Resumo**: O que é?
*   **Motivação**: Por que precisamos disso?
*   **Especificação**: Detalhes técnicos/orçamentários.
*   **Orçamento**: Quantos $JUS ou USDC são necessários?

### Fase 3: Votação (Snapshot)
Se o tópico no fórum ficar ativo por 5 dias e tiver feedback positivo, ele vai para votação no Snapshot.
*   **Duração**: 72 horas.
*   **Quorum Mínimo**: 5% do supply circulante deve votar.
*   **Maioria**: > 50% dos votos "Sim".

### Passos Pós-Aprovação
1.  Se aprovado, o Tesouro Multi-Sig (gerido por 5 guardiões eleitos) executa a transferência de fundos.
2.  Um Gerente de Projeto é designado para acompanhar a entrega.

## Guardiões da Multisig
Os guardiões **não decidem** o que fazer com o dinheiro, apenas **executam** o que a comunidade votou. Eles têm a chave de segurança para impedir ataques maliciosos, mas não podem gastar sem votação prévia.
