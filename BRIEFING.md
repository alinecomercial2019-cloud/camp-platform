# BRIEFING — CAMP Platform
## A Plataforma de Trabalho para Lançamento Pago

---

## Visão do Produto

**O que é:** Uma plataforma de trabalho diário para mentorados do Rise Live — que combina área de estudo com gestão completa de lançamentos, como um ClickUp construído especificamente para a metodologia do Willian Baldan.

**Posicionamento:** Não é uma área de membros. É a ferramenta onde o mentorado vive enquanto está dentro do Rise.

**Promessa:** *"Tudo que você precisa para fazer seu lançamento pago está aqui — aprenda e execute no mesmo lugar."*

---

## Estrutura da Plataforma

### 📚 ÁREA DE ESTUDO
> Onde o membro aprende

- Módulos e aulas organizados pelas fases do lançamento
- Gravações das 12 mentorias em grupo
- Biblioteca de materiais, scripts e templates para download
- Progresso individual por aula e por módulo
- Aulas desbloqueadas conforme avanço no lançamento

---

### 🚀 ÁREA DE PROJETOS & LANÇAMENTOS
> Onde o membro trabalha

**Gestão de Lançamentos (estilo ClickUp):**
- Cria um novo lançamento como um projeto
- Define: nome do produto, nicho, público, data do lançamento, meta de faturamento
- A plataforma gera automaticamente o plano de execução baseado na metodologia Rise

**Kanban do Lançamento:**
```
[ Planejamento ] → [ Captação ] → [ Aquecimento ] → [ Abertura ] → [ Carrinho ] → [ Pós-venda ]
```
- Cada coluna tem tarefas específicas da metodologia
- Tarefas com checklists validados pelo Willian
- Prazo e responsável por tarefa

**Dentro de cada Lançamento:**
- Calendário de datas e deadlines
- Métricas registradas em tempo real (leads, conversões, faturamento)
- Anotações e briefings do produto
- Links importantes (página de vendas, grupo, checkout)
- Histórico de decisões e ajustes

**Histórico e Evolução:**
- Comparativo entre lançamentos anteriores
- Gráfico de evolução (leads, faturamento, conversão)
- O membro vê seu crescimento lançamento a lançamento

---

### 🔗 CONEXÃO ENTRE AS DUAS ÁREAS
> O que nenhuma plataforma tem

- Membro está na etapa **Captação** no projeto → plataforma destaca as aulas de Captação
- Membro conclui uma tarefa → plataforma sugere a aula relacionada
- Membro trava em uma etapa → plataforma mostra a gravação da mentoria sobre aquele tema

---

### 🏠 HOME / PAINEL PRINCIPAL
> Visão geral do dia

- Próxima live + countdown
- Onde estou no lançamento atual (% de progresso)
- Próximas tarefas do projeto
- Últimas aulas não assistidas
- Avisos e novidades da Orbyka

---

### 👥 COMUNIDADE
- Feed de atualizações do Willian
- Mural de resultados dos membros
- Espaço para enviar perguntas antes das mentorias

---

### ⚙️ PAINEL ADMIN (Willian / Orbyka)
- Publica e gerencia conteúdo
- Vê todos os lançamentos dos membros
- Identifica onde os membros estão travando
- Agenda e gerencia as lives
- Métricas de engajamento da plataforma

---

## MVP — Versão 1 (Para lançar primeiro)

> O que precisa existir no dia 1 para já ser revolucionário

| # | Funcionalidade | Motivo |
|---|---|---|
| 1 | Login e autenticação segura | Base de tudo |
| 2 | Home com painel do membro | Primeira impressão |
| 3 | Área de Estudo — módulos e aulas em vídeo | Entrega o conteúdo |
| 4 | Materiais para download | Complementa o estudo |
| 5 | Criar lançamento + Kanban com etapas | O grande diferencial |
| 6 | Checklists por etapa do lançamento | Metodologia na prática |
| 7 | Agenda de lives com link de acesso | Suporte às mentorias |
| 8 | Painel Admin básico (publicar aulas, gerenciar membros) | Operação da Orbyka |

---

## Versão 2 (Após validação do MVP)

| # | Funcionalidade |
|---|---|
| 1 | Registro de métricas por lançamento |
| 2 | Histórico e comparativo entre lançamentos |
| 3 | Conteúdo contextual (aula certa na etapa certa) |
| 4 | Envio de perguntas antes das mentorias |
| 5 | Mural de resultados da comunidade |
| 6 | Gráficos de evolução do membro |
| 7 | Painel Admin avançado com dados dos membros |

---

## Versão 3 (Plataforma completa)

| # | Funcionalidade |
|---|---|
| 1 | Calendário integrado do lançamento |
| 2 | Notificações e lembretes de tarefas |
| 3 | Múltiplos lançamentos simultâneos |
| 4 | Integração com ferramentas externas (Meta Ads, etc.) |
| 5 | Certificado de conclusão |
| 6 | App mobile |

---

## Stack Técnica

| Camada | Tecnologia |
|---|---|
| Frontend | Next.js (React) |
| Banco de dados | Supabase |
| Autenticação | Supabase Auth |
| Storage de vídeos | Bunny.net ou Mux |
| Arquivos/Downloads | Supabase Storage |
| Pagamentos | Stripe ou Hotmart |
| Deploy | Vercel |

---

## Resumo em uma frase

> *O CAMP é o ClickUp do lançamento pago — onde o mentorado aprende, planeja e executa o lançamento inteiro sem sair da plataforma.*
