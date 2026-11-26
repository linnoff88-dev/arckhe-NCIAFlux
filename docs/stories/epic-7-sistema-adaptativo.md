# Epic 7: Sistema Adaptativo + Cloud (v1.4)

**Objetivo:** Implementar infraestrutura cloud com Supabase, sistema adaptativo que aprende com o usuário, gamificaçêo TDAH-friendly e chat social.

**Valor de Negócio:** Transforma o app de ferramenta local para plataforma conectada. Usuários Plus ganham sync multi-device, sistema que se adapta ao seu perfil, e conexêo com outros usuários para accountability.

**Dependências:** Epics 1-6 (base local funcionando)

**Filosofia Central:**
> "Nêo é o usuário que configura o app. É o app que se configura ao usuário."

**Stories:**

## Fase 1: Infraestrutura Cloud
- [7.1 Supabase Auth e Setup](./7.1-supabase-auth.md)
- [7.2 Sync Offline-First](./7.2-sync-offline-first.md)
- [7.3 Importaçêo em Massa](./7.3-importacao-massa.md)

## Fase 2: Sistema Adaptativo
- [7.4 Perfil TDAH e Ferramentas de Avaliaçêo](./7.4-perfil-tdah.md)
- [7.5 Coleta de Padrões](./7.5-coleta-padroes.md)
- [7.6 Motor de Adaptaçêo](./7.6-motor-adaptacao.md)
- [7.7 Relatório Pessoal](./7.7-relatorio-pessoal.md)
- [7.8 Liberaçêo Progressiva de Features](./7.8-liberacao-progressiva.md)

## Fase 3: Gamificaçêo TDAH
- [7.9 Gamificaçêo Básica](./7.9-gamificacao-basica.md)
- [7.10 Sistema de XP e Níveis](./7.10-xp-niveis.md)
- [7.11 Conquistas e Streaks Gentis](./7.11-conquistas-streaks.md)

## Fase 4: Social
- [7.12 Chat 1:1 (Accountability Partner)](./7.12-chat-1a1.md)
- [7.13 Chat em Grupo (Comunidades)](./7.13-chat-grupo.md)

**Definition of Done do Epic:**
- [ ] Login com Google/Email funcionando via Supabase
- [ ] Dados sincronizam entre dispositivos
- [ ] Importaçêo de CSV/ICS/JSON funciona
- [ ] Questionário TDAH completo com resultado
- [ ] Sistema detecta padrões de uso
- [ ] Adaptações automáticas ativas (ex: esconder tarefas quando overwhelm)
- [ ] Relatório Pessoal exibe mapa de energia e recomendações
- [ ] Features liberadas progressivamente por estabilidade
- [ ] Celebrações e XP funcionando
- [ ] Streaks nêo punem por falhas
- [ ] Chat 1:1 entre usuários funciona
- [ ] Chat em grupo funciona
- [ ] Testes de integraçêo do fluxo completo passando

**Documentaçêo de Referência:**
- [docs/v1.4-adaptive-system.md](../v1.4-adaptive-system.md)

---

*Gerado seguindo BMad Method v4.44.3*
