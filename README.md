# NeuroFluxo Mentes Brilhantes

<div align="center">

**v1.3** | Produtividade que entende vocÃª

Sistema de organizaÃ§Ã£o pessoal baseado em neurociÃªncia para pessoas com TDAH.

[![Version](https://img.shields.io/badge/Version-1.3-purple)](https://github.com/inematds/NCIAFlux)
[![Next.js](https://img.shields.io/badge/Next.js-14-black?logo=next.js)](https://nextjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0-blue?logo=typescript)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-3.4-38B2AC?logo=tailwind-css)](https://tailwindcss.com/)
[![Vercel](https://img.shields.io/badge/Deploy-Vercel-black?logo=vercel)](https://vercel.com/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

[**Demo ao Vivo**](https://ncia-flux.vercel.app) | [**DocumentaÃ§Ã£o**](docs/)

</div>

---

## Sobre o Projeto

NCIAFlux (NeuroFluxo) Ã© um aplicativo web projetado especificamente para pessoas com TDAH. Diferente de apps genÃ©ricos de produtividade, o NeuroFluxo entende que cada pessoa tem seu prÃ³prio ritmo e adapta suas ferramentas ao perfil cognitivo do usuÃ¡rio.

### Por que "Mentes Brilhantes"?

Porque acreditamos que cÃ©rebros neurodivergentes nÃ£o sÃ£o defeituosos - sÃ£o diferentes. E com as ferramentas certas, podem brilhar.

### Diferenciais

- **Cronotipos**: Descubra seu perfil de produtividade (LeÃ£o, Urso, Lobo, Golfinho)
- **Brain Dump**: Capture pensamentos sem julgamento, organize depois
- **Planner Adaptativo**: Check-in de humor/energia que adapta o dia
- **Rotinas Condicionais**: Regras "se/entÃ£o" para dias diferentes
- **Modo Crise**: Suporte imediato quando vocÃª trava
- **Sem PressÃ£o**: Acompanhamento gentil, celebraÃ§Ãµes e micro-recompensas

---

## Autismo e TDAH em NÃºmeros (2026)

Este projeto existe porque **milhÃµes de pessoas** precisam de ferramentas que entendam como seus cÃ©rebros funcionam.

### Brasil

| CondiÃ§Ã£o | Estimativa 2026 | Fonte |
|----------|-----------------|-------|
| **Autismo (TEA)** | 2,4 - 2,6 milhÃµes | IBGE Censo 2022 (~1,2% da populaÃ§Ã£o) |
| **TDAH** | ~11 milhÃµes | Estudos epidemiolÃ³gicos (~7,6% crianÃ§as/adolescentes) |

> O Censo 2022 foi o **primeiro levantamento oficial brasileiro** a incluir dados sobre autismo.

### Mundo

| CondiÃ§Ã£o | Estimativa 2026 | PrevalÃªncia |
|----------|-----------------|-------------|
| **Autismo (TEA)** | ~65 milhÃµes | 1 em cada 127 pessoas (OMS) |
| **TDAH** | ~94 milhÃµes | ~1,13% da populaÃ§Ã£o (GBD) |

### Por que isso importa?

Apps de produtividade tradicionais sÃ£o feitos para cÃ©rebros neurotÃ­picos. Pessoas com TDAH e autismo frequentemente:
- TÃªm dificuldade com listas rÃ­gidas e horÃ¡rios fixos
- Experimentam paralisia por anÃ¡lise e sobrecarga sensorial
- Precisam de lembretes gentis, nÃ£o cobranÃ§as
- Funcionam melhor com recompensas imediatas e micro-vitÃ³rias

O NeuroFluxo foi projetado **desde o inÃ­cio** para essas necessidades.

---

## Funcionalidades

### v1.0 - Base

| MÃ³dulo | DescriÃ§Ã£o |
|--------|-----------|
| **Landing Page** | ApresentaÃ§Ã£o do produto com CTA |
| **AutenticaÃ§Ã£o** | Login, registro, recuperaÃ§Ã£o de senha |
| **Demo Mode** | Experimente com dados de exemplo |
| **Brain Dump** | Captura de pensamentos com triagem e Top 1 diÃ¡rio |
| **Cronotipos** | QuestionÃ¡rio de descoberta + perfil personalizado |
| **Planner DiÃ¡rio** | Check-in matinal, tarefas por perÃ­odo (manhÃ£/tarde/noite) |
| **Rotinas** | Rotinas matinais e noturnas com passos condicionais |
| **Projetos** | Organize tarefas por projeto com cores e emojis |
| **Tarefas Unificadas** | Lista geral com filtros por status, projeto e perÃ­odo |
| **CalendÃ¡rio** | VisualizaÃ§Ã£o mensal de eventos e tarefas |
| **Notas** | Inbox rÃ¡pido + organizaÃ§Ã£o em pastas |
| **RevisÃµes Semanais** | ReflexÃ£o: vitÃ³rias, desafios, aprendizados |
| **Modo Foco** | TÃ©cnica Pomodoro com pausas guiadas |
| **Modo Crise** | TÃ©cnicas de grounding para momentos difÃ­ceis |
| **RelatÃ³rios** | EstatÃ­sticas de produtividade e padrÃµes |
| **Equipes** | GestÃ£o de equipe (visÃ£o admin) |
| **ConfiguraÃ§Ãµes** | PreferÃªncias, foto, senha |

### v1.1 - Storage Local Aprimorado

| Feature | DescriÃ§Ã£o |
|---------|-----------|
| **Barra de Status** | Humor, energia, foco e tarefas no topo do dashboard |
| **Timer de Foco Integrado** | Escolha tecnica primeiro, depois tarefa para focar |
| **Check-in Acionavel** | Recomendacoes personalizadas apos registrar humor/energia |
| **Modo Crise com Jogos** | Mini-games para acalmar: bolhas, cores, respiracao |
| **Dados Demo** | Dados de exemplo completos para demonstracao |

### v1.2 - Multi-Perfil

| Feature | DescriÃ§Ã£o |
|---------|-----------|
| **Multi-Usuario Local** | Suporte a multiplos perfis no mesmo dispositivo |
| **Storage Prefixado** | Dados isolados por usuario (nciaflux_${userId}_...) |
| **Switcher de Perfis** | Troca rapida entre contas no sidebar |
| **Visao Pessoal/Gestao** | Toggle para managers alternarem entre modos |
| **Menu por Role** | Equipes visivel apenas para gestores/admins |
| **Demo com 3 Perfis** | Teste como Usuario, Gestor ou Admin |
| **Botao Chat IA** | Teaser da versao Pro com chat por texto/voz |
| **Migracao Automatica** | Dados antigos migrados para novo formato |

### v1.3 - Chat com IA (Atual)

| Feature | DescriÃ§Ã£o |
|---------|-----------|
| **Chat por Texto** | Converse com IA para criar tarefas, brain dump, pedir ajuda |
| **Comandos de Voz** | Fale para criar e gerenciar tarefas (Web Speech API) |
| **OpenRouter** | Gateway para escolher entre LLMs (Claude, GPT-4, Mistral) |
| **Tool Use** | IA executa aÃ§Ãµes na app (criar tarefas, ativar modo crise) |
| **Assistente Contextual** | SugestÃµes baseadas no perfil cognitivo e cronotipo |
| **Brain Dump por Voz** | Fale pensamentos, IA organiza automaticamente |
| **Listagem por Chat** | IA lista tarefas, eventos e brain dump do usuÃ¡rio |

---

## Roadmap

### v1.4 - Sistema Adaptativo + Cloud (Plano Plus)

| Feature | DescriÃ§Ã£o |
|---------|-----------|
| **Supabase Auth** | Login com Google/Email, sessÃ£o persistente |
| **Sync Offline-First** | Dados locais + sincronizaÃ§Ã£o quando online |
| **Multi-Device** | Acesse seus dados em qualquer dispositivo |
| **ImportaÃ§Ã£o em Massa** | Importar tarefas, eventos, notas, brain dump (CSV/ICS/JSON) |
| **Sistema Adaptativo** | App detecta padrÃµes e ajusta experiÃªncia automaticamente |
| **Perfil TDAH** | QuestionÃ¡rio de subtipo (hiperativo/desatento/combinado) |
| **Ferramentas de AvaliaÃ§Ã£o** | Refazer questionÃ¡rios, editar perfil manualmente |
| **RelatÃ³rio Pessoal** | Mapa de energia, padrÃµes de humor, recomendaÃ§Ãµes |
| **LiberaÃ§Ã£o Progressiva** | Features liberadas conforme estabilidade do usuÃ¡rio |
| **GamificaÃ§Ã£o BÃ¡sica** | CelebraÃ§Ãµes suaves, streaks gentis (sem puniÃ§Ã£o por falha) |
| **Chat 1:1** | Conversa privada (parceiro accountability) |
| **Chat em Grupo** | Comunidades de apoio |

> DocumentaÃ§Ã£o: [docs/v1.4-adaptive-system.md](docs/v1.4-adaptive-system.md)

### v1.5 - GestÃ£o de Times (Plano Pro)

| Feature | DescriÃ§Ã£o |
|---------|-----------|
| **Criar Times** | Gestor cria equipe e convida membros |
| **Roles** | Admin, Gestor, Membro com permissÃµes diferentes |
| **Dashboard do Gestor** | VisÃ£o geral da equipe (dados anonimizados) |
| **Liberar Features** | Gestor pode habilitar features para membros |
| **RelatÃ³rios de Time** | MÃ©tricas agregadas da equipe |
| **GamificaÃ§Ã£o AvanÃ§ada** | Conquistas, XP, nÃ­veis, desafios (liberado por estabilidade) |

### v1.6 - PWA e NotificaÃ§Ãµes

| Feature | DescriÃ§Ã£o |
|---------|-----------|
| **PWA InstalÃ¡vel** | Instale no celular como app nativo |
| **NotificaÃ§Ãµes Push** | Lembretes de tarefas, rotinas, check-in |
| **Modo Escuro** | Tema escuro para uso noturno |

### v1.7 - Voice Output (TTS)

| Feature | DescriÃ§Ã£o |
|---------|-----------|
| **Text-to-Speech** | Assistente responde por voz (Web Speech API) |
| **Vozes em PT-BR** | Escolha de vozes disponÃ­veis |
| **Auto-Read Modo Crise** | Leitura automÃ¡tica quando sobrecarregado |
| **Controles de Voz** | Ajuste de velocidade e tom |

### v1.8 - Messaging Integration

| Feature | DescriÃ§Ã£o |
|---------|-----------|
| **Telegram Bot** | Interaja com o app via Telegram |
| **WhatsApp** | IntegraÃ§Ã£o via Business API ou web.js |
| **Email** | Resumos e lembretes por email |

> DocumentaÃ§Ã£o: [docs/v1.9-messaging-integration.md](docs/v1.9-messaging-integration.md)

### v1.9 - IntegraÃ§Ãµes Externas

| Feature | DescriÃ§Ã£o |
|---------|-----------|
| **Google Calendar** | Sincronizar eventos com Google Agenda |
| **Apple Calendar** | Sincronizar com calendÃ¡rio Apple |
| **Outlook** | IntegraÃ§Ã£o com Microsoft 365 |
| **ImportaÃ§Ã£o AutomÃ¡tica** | Sync contÃ­nuo de eventos externos |

### v2.0 - IA AvanÃ§ada (Plano Premium)

| Feature | DescriÃ§Ã£o |
|---------|-----------|
| **IA Ilimitada** | Sem limite de mensagens no chat |
| **Resumo DiÃ¡rio** | IA resume seu dia e sugere prÃ³ximos passos |
| **AnÃ¡lise Preditiva** | IA prevÃª dias difÃ­ceis e sugere preparaÃ§Ã£o |

### v2.3 - IntegraÃ§Ã£o com Terapeutas

| Feature | DescriÃ§Ã£o |
|---------|-----------|
| **Vincular Terapeuta** | UsuÃ¡rio convida profissional de saÃºde |
| **RelatÃ³rios ClÃ­nicos** | Exportar humor, energia, padrÃµes para terapeuta |
| **Modo Acompanhamento** | Terapeuta visualiza progresso (com permissÃ£o) |
| **Liberar Features** | Terapeuta pode habilitar features sensÃ­veis |

### v2.5 - Testes e EstabilizaÃ§Ã£o

| Feature | DescriÃ§Ã£o |
|---------|-----------|
| **Testes Automatizados** | Cobertura de testes unitÃ¡rios e E2E |
| **CI/CD Pipeline** | IntegraÃ§Ã£o e deploy contÃ­nuos |
| **Testes de SeguranÃ§a** | Auditoria de seguranÃ§a completa |
| **Testes de Acessibilidade** | WCAG 2.1 compliance |
| **Beta Testing** | Programa de beta testers |

### v3.0 - App Nativo (Plano Empresarial)

| Feature | DescriÃ§Ã£o |
|---------|-----------|
| **App iOS Nativo** | Swift/SwiftUI para melhor performance |
| **App Android Nativo** | Kotlin para melhor performance |
| **Widgets Nativos** | Widgets para tela inicial |
| **Wearables** | Apple Watch e Wear OS |
| **Biometria** | Face ID, Touch ID, impressÃ£o digital |
| **OrganizaÃ§Ãµes** | Admin cria empresas e organizaÃ§Ãµes |
| **API PÃºblica** | IntegraÃ§Ãµes com outros apps |

### Status do Desenvolvimento

```
v1.0 â–ˆâ–ˆâ–ˆâ–ˆâ–ˆâ–ˆâ–ˆâ–ˆâ–ˆâ–ˆâ–ˆâ–ˆâ–ˆâ–ˆâ–ˆâ–ˆâ–ˆâ–ˆâ–ˆâ–ˆ 100% - Base completa
v1.1 â–ˆâ–ˆâ–ˆâ–ˆâ–ˆâ–ˆâ–ˆâ–ˆâ–ˆâ–ˆâ–ˆâ–ˆâ–ˆâ–ˆâ–ˆâ–ˆâ–ˆâ–ˆâ–ˆâ–ˆ 100% - Storage local aprimorado
v1.2 â–ˆâ–ˆâ–ˆâ–ˆâ–ˆâ–ˆâ–ˆâ–ˆâ–ˆâ–ˆâ–ˆâ–ˆâ–ˆâ–ˆâ–ˆâ–ˆâ–ˆâ–ˆâ–ˆâ–ˆ 100% - Multi-perfil
v1.3 â–ˆâ–ˆâ–ˆâ–ˆâ–ˆâ–ˆâ–ˆâ–ˆâ–ˆâ–ˆâ–ˆâ–ˆâ–ˆâ–ˆâ–ˆâ–ˆâ–ˆâ–ˆâ–ˆâ–ˆ 100% - Chat com IA â† ATUAL
â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€
v1.4 â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘   0% - Sistema Adaptativo + Cloud + GamificaÃ§Ã£o
v1.5 â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘   0% - GestÃ£o de Times (Pro)
v1.6 â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘   0% - PWA e NotificaÃ§Ãµes
v1.7 â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘   0% - Voice Output (TTS)
v1.8 â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘   0% - Messaging (Telegram/WhatsApp)
v1.9 â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘   0% - IntegraÃ§Ãµes Externas (CalendÃ¡rios)
v2.0 â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘   0% - IA AvanÃ§ada (Premium)
v2.3 â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘   0% - IntegraÃ§Ã£o Terapeutas
v2.5 â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘   0% - Testes e EstabilizaÃ§Ã£o
v3.0 â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘â–‘   0% - App Nativo (Empresarial)
```

> **Nota:** VersÃ£o atual (v1.3). Demo simula 3 perfis (Usuario/Gestor/Admin) para demonstraÃ§Ã£o.

---

## Screenshots

### Dashboard
```
â”Œâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”
â”‚  Bom dia, JoÃ£o! â˜€ï¸                                      â”‚
â”‚                                                         â”‚
â”‚  â”Œâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â” â”Œâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â” â”Œâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â” â”Œâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”   â”‚
â”‚  â”‚ Tarefas  â”‚ â”‚ Projetos â”‚ â”‚ Rotinas  â”‚ â”‚ Energia  â”‚   â”‚
â”‚  â”‚    12    â”‚ â”‚    4     â”‚ â”‚   85%    â”‚ â”‚   âš¡ 7   â”‚   â”‚
â”‚  â””â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”˜ â””â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”˜ â””â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”˜ â””â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”˜   â”‚
â”‚                                                         â”‚
â”‚  Top 1 de Hoje: Entregar relatÃ³rio mensal              â”‚
â”‚                                                         â”‚
â”‚  PrÃ³ximas Tarefas:                                      â”‚
â”‚  ðŸ”´ ReuniÃ£o com cliente (10h)                          â”‚
â”‚  ðŸŸ¡ Revisar documentaÃ§Ã£o                               â”‚
â”‚  ðŸŸ¢ Responder emails                                   â”‚
â””â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”˜
```

### Planner DiÃ¡rio
```
â”Œâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”
â”‚  ðŸ“… Sexta, 24 de Janeiro                               â”‚
â”‚                                                         â”‚
â”‚  Como vocÃª estÃ¡?  ðŸ˜Š ðŸ˜ ðŸ˜” ðŸ˜¤                          â”‚
â”‚  Energia: â–ˆâ–ˆâ–ˆâ–ˆâ–ˆâ–ˆâ–ˆâ–ˆâ–‘â–‘ 8/10                              â”‚
â”‚  Sono: â­â­â­â­â˜† 4/5                                    â”‚
â”‚                                                         â”‚
â”‚  â˜€ï¸ MANHÃƒ                                              â”‚
â”‚  â”Œâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”        â”‚
â”‚  â”‚ â­ Preparar apresentaÃ§Ã£o         Em Andamentoâ”‚       â”‚
â”‚  â”‚ â˜ Revisar emails                   Pendente â”‚        â”‚
â”‚  â””â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”˜        â”‚
â”‚                                                         â”‚
â”‚  ðŸŒ¤ï¸ TARDE                                              â”‚
â”‚  â”Œâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”        â”‚
â”‚  â”‚ â˜ ReuniÃ£o de equipe               Pendente â”‚        â”‚
â”‚  â””â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”˜        â”‚
â””â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”˜
```

---

## Arquitetura

### Estrutura do Projeto

```
NCIAFlux/
â”œâ”€â”€ apps/
â”‚   â””â”€â”€ web/                      # App Web (Next.js 14)
â”‚       â””â”€â”€ src/
â”‚           â”œâ”€â”€ app/              # App Router
â”‚           â”‚   â”œâ”€â”€ dashboard/    # MÃ³dulos do app
â”‚           â”‚   â”‚   â”œâ”€â”€ brain-dump/
â”‚           â”‚   â”‚   â”œâ”€â”€ calendar/
â”‚           â”‚   â”‚   â”œâ”€â”€ chronotype/
â”‚           â”‚   â”‚   â”œâ”€â”€ notes/
â”‚           â”‚   â”‚   â”œâ”€â”€ planner/
â”‚           â”‚   â”‚   â”œâ”€â”€ projects/
â”‚           â”‚   â”‚   â”œâ”€â”€ review/
â”‚           â”‚   â”‚   â”œâ”€â”€ routines/
â”‚           â”‚   â”‚   â”œâ”€â”€ tasks/
â”‚           â”‚   â”‚   â””â”€â”€ ...
â”‚           â”‚   â”œâ”€â”€ demo/         # Modo demonstraÃ§Ã£o
â”‚           â”‚   â”œâ”€â”€ login/        # AutenticaÃ§Ã£o
â”‚           â”‚   â””â”€â”€ register/
â”‚           â”œâ”€â”€ components/       # Componentes reutilizÃ¡veis
â”‚           â””â”€â”€ lib/              # UtilitÃ¡rios e storage
â”œâ”€â”€ packages/
â”‚   â””â”€â”€ shared/                   # Tipos compartilhados
â”œâ”€â”€ docs/                         # DocumentaÃ§Ã£o
â”‚   â”œâ”€â”€ prd.md                    # Product Requirements
â”‚   â”œâ”€â”€ architecture.md           # Arquitetura tÃ©cnica
â”‚   â””â”€â”€ stories/                  # User Stories
â””â”€â”€ .bmad-core/                   # Framework BMad Method
```

### Tech Stack

| Camada | Tecnologia |
|--------|------------|
| **Framework** | Next.js 14 (App Router) |
| **Linguagem** | TypeScript 5.0 |
| **EstilizaÃ§Ã£o** | Tailwind CSS 3.4 |
| **Storage** | localStorage (hÃ­brido, preparado para backend) |
| **Deploy** | Vercel (auto-deploy via GitHub) |
| **Monorepo** | Turborepo + pnpm |

### Armazenamento

O app usa localStorage com estrutura preparada para migraÃ§Ã£o para backend:

```typescript
// Chaves de storage
nciaflux_user          // Dados do usuÃ¡rio
nciaflux_tasks         // Tarefas unificadas
nciaflux_projects      // Projetos
nciaflux_notes         // Notas
nciaflux_routines      // Rotinas
nciaflux_dayplan       // Plano diÃ¡rio
nciaflux_braindump     // Brain dump
nciaflux_chronotype    // Perfil de cronotipo
nciaflux_reviews       // RevisÃµes semanais
```

---

## Setup Local

### Requisitos

- Node.js 18+
- pnpm 8+

### InstalaÃ§Ã£o

```bash
# Clonar repositÃ³rio
git clone https://github.com/inematds/NCIAFlux.git
cd NCIAFlux

# Instalar pnpm (se necessÃ¡rio)
npm install -g pnpm

# Instalar dependÃªncias
pnpm install

# Rodar em desenvolvimento
pnpm dev:web
```

O app estarÃ¡ disponÃ­vel em `http://localhost:3000`

### Scripts

| Comando | DescriÃ§Ã£o |
|---------|-----------|
| `pnpm dev:web` | Inicia em desenvolvimento |
| `pnpm build` | Build de produÃ§Ã£o |
| `pnpm lint` | Executa linting |

---

## Deploy

O projeto estÃ¡ configurado para deploy automÃ¡tico no Vercel:

1. Push para `main` dispara build
2. Preview deploys em PRs
3. ProduÃ§Ã£o: https://ncia-flux.vercel.app

---

## Planos de Uso

| Plano | Features | Storage | VersÃ£o |
|-------|----------|---------|--------|
| **Free** | Funcionalidades pessoais | Local | v1.2 âœ“ |
| **Team** | + Times + Chat equipe + P2P | Central + P2P | v1.5 |
| **Premium** | + Chat IA + Voz + Sync nuvem | Cloud | v2.0 |
| **Empresarial** | + OrganizaÃ§Ãµes + Apps nativos | Cloud | v3.0 |

### Detalhamento dos Planos

**Free (DisponÃ­vel)**
- Todas as funcionalidades de produtividade pessoal
- Dados salvos localmente no navegador
- Multi-perfil no mesmo dispositivo
- PWA instalÃ¡vel (v1.6)
- NotificaÃ§Ãµes locais (v1.7)
- Sem limite de uso

**Team (v1.5)**
- Tudo do Free +
- CriaÃ§Ã£o e gestÃ£o de times
- Chat entre membros da equipe
- Convites por ID
- Central de descoberta de usuÃ¡rios
- ComunicaÃ§Ã£o P2P apÃ³s conexÃ£o
- Dashboard do gestor (dados anonimizados)

**Premium (v2.0)**
- Tudo do Team +
- Chat com IA por texto e voz
- Assistente contextual inteligente
- Brain dump por voz
- SincronizaÃ§Ã£o na nuvem
- Backup automÃ¡tico
- IntegraÃ§Ã£o com terapeutas (v1.7)

**Empresarial (v3.0)**
- Tudo do Premium +
- Apps nativos iOS e Android
- Widgets e wearables
- CriaÃ§Ã£o de organizaÃ§Ãµes
- API pÃºblica para integraÃ§Ãµes
- Suporte prioritÃ¡rio
- SLA garantido

---

## DocumentaÃ§Ã£o

| Documento | DescriÃ§Ã£o |
|-----------|-----------|
| [PRD](docs/prd.md) | Requisitos do produto |
| [Arquitetura](docs/architecture.md) | Arquitetura tÃ©cnica |
| [Stories](docs/stories/) | User stories |

---

## ContribuiÃ§Ã£o

1. Fork o repositÃ³rio
2. Crie uma branch (`git checkout -b feature/nova-feature`)
3. Use commits convencionais (`feat:`, `fix:`, `docs:`)
4. Abra um Pull Request

---

## LicenÃ§a

MIT

---

<div align="center">

Desenvolvido com assistÃªncia de IA usando o [BMad Method](https://github.com/bmad-method)

**NCIAFlux - NeuroFluxo** | Produtividade que entende vocÃª

</div>

---

Projeto adaptado da comunidade INEMA TDS - Marca Arckhe