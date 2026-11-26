# Epic 6: Plano Profissional

**Objetivo:** Implementar funcionalidades para acompanhamento profissional com terapeutas e coaches.

**Valor de Negócio:** Abre mercado B2B e aumenta valor percebido para pacientes em tratamento.

**Dependências:** Epic 1-5

**Stories:**
- [6.1 Vinculaçêo com Profissional](./6.1-vinculacao-profissional.md)
- [6.2 Dashboard do Profissional](./6.2-dashboard-profissional.md)
- [6.3 Relatórios para Profissional](./6.3-relatorios-profissional.md)

**Definition of Done do Epic:**
- [ ] Paciente pode vincular terapeuta
- [ ] Profissional tem dashboard próprio
- [ ] Relatórios exportáveis para sessões
- [ ] Controles de privacidade funcionais

---

## Story 6.1: Vinculaçêo com Profissional (Resumo)

**As a** usuário do plano Profissional,
**I want** vincular minha conta a um terapeuta/coach,
**so that** ele possa me acompanhar.

**Acceptance Criteria:**
1. Fluxo de convite/aceite de vinculaçêo
2. Consentimento explícito sobre dados compartilhados
3. Usuário controla quais dados sêo visíveis
4. Vinculaçêo pode ser revogada a qualquer momento
5. Múltiplos profissionais podem ser vinculados

**Key Tasks:**
- Tabela `professional_links`
- Tela de convite (gerar código)
- Tela de aceite de convite
- Configuraçêo de dados compartilhados
- Notificaçêo ao profissional

---

## Story 6.2: Dashboard do Profissional (Resumo)

**As a** terapeuta/coach,
**I want** ver um painel com dados relevantes dos meus pacientes,
**so that** possa acompanhar e orientar melhor.

**Acceptance Criteria:**
1. Login separado para profissionais
2. Lista de pacientes vinculados
3. Visêo resumida do progresso de cada paciente
4. Acesso a relatórios específicos (conforme consentimento)
5. Nêo é dashboard de cobrança - foco em padrões e insights

**Key Tasks:**
- App web para profissionais (Next.js)
- Autenticaçêo com role `professional`
- Lista de pacientes com status
- Visêo resumida por paciente
- Filtros e busca

---

## Story 6.3: Relatórios para Profissional (Resumo)

**As a** profissional,
**I want** gerar relatórios específicos sobre meu paciente,
**so that** use nas sessões de acompanhamento.

**Acceptance Criteria:**
1. Relatórios focados em padrões, nêo métricas punitivas
2. Insights sobre: energia, adesêo, técnicas eficazes, momentos difíceis
3. Formato adequado para discussêo em sessêo
4. Exportaçêo em PDF
5. Período personalizável
6. Notas do profissional podem ser adicionadas

**Key Tasks:**
- Templates de relatório para profissionais
- Geraçêo de PDF
- Seletor de período
- Campo de notas do profissional
- Histórico de relatórios gerados
