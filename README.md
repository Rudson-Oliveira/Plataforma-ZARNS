# Plataforma ZARNS - Portal Academico

> Web App PWA para acompanhamento academico do curso de Medicina - ZARNS/UNESUL/IMEPAC

**[Acessar App](https://rudson-oliveira.github.io/Plataforma-ZARNS/)**

---

## Dados do Aluno

| Campo | Valor |
|-------|-------|
| Nome | Rudson Antonio Ribeiro Oliveira |
| RA | 2226020016 |
| Curso | 61 - Medicina |
| Serie | 8 |
| Periodo | 2026/1 |
| Turma | 60_MED8BI_T8 |
| Status | Ativo |
| Portal | https://portal.clariens.com.br/aluno/ |

---

## Disciplinas Matriculadas (2026/1)

| Codigo | Disciplina | Docente |
|--------|-----------|--------|
| MED6047 | Gestao e Empreendedorismo | Francisco Junqueira Neto |
| MED6048 | Emergencias Pediatricas/Clinicas/Psiquiatricas | Joanderson Fernandez de Melo |
| MED6049 | Trabalho de Conclusao de Curso II | Jose Luiz de Oliveira Schiavon |
| MED6050 | Medicina Legal | Docente em Contratacao |
| MED6051 | Deontologia e Etica Medica | Antonio Homero Rocha de Toledo |
| MED6052 | Emergencias Cirurgicas e Obstetricas | Benedito Martinho Santana |

---

## App Web (PWA) - v2.0

Aplicacao web progressiva com 4 abas principais:

### Funcionalidades

- **Hoje**: Timeline visual do dia com status ao vivo, countdown para proxima aula
- **Semana**: Horario completo com agrupamento inteligente de aulas consecutivas
- **Materias**: Lista de disciplinas com carga horaria semanal
- **Stats**: Estatisticas - carga por dia e por disciplina com graficos

### Recursos Tecnicos

- PWA instalavel (manifest.json)
- Auto-refresh a cada 60 segundos
- Design dark mode elegante com gradientes
- Responsivo (max 480px mobile-first)
- Status em tempo real (AO VIVO)
- Sem dependencias externas (vanilla JS)

---

## Horario Semanal Resumido

### Segunda-feira (9 aulas)
- 10:20-12:00 | Emergencias Pediatricas (LABA2)
- 13:20-17:00 | Emergencias Cirurgicas (LABA2)
- 17:30-20:20 | Gestao e Empreendedorismo

### Terca-feira (4 aulas)
- 15:20-17:00 | Emergencias Pediatricas (LABA2) - Auditorio 8 Andar
- 19:30-21:10 | Emergencias Cirurgicas - CESP Saber e Saude

### Quarta-feira (3 aulas)
- 14:10-17:00 | Emergencias Pediatricas (PA2) - CESP Saber e Saude

### Quinta-feira (11 aulas)
- 08:20-10:00 | Emergencias Pediatricas - Biblioteca
- 10:20-12:00 | Deontologia e Etica Medica
- 13:20-15:00 | Emergencias Pediatricas - Biblioteca
- 17:30-20:20 | Medicina Legal - 5 Andar TUT 08
- 19:30-21:10 | TCC II - 5 Andar TUT 04

### Sexta-feira (6 aulas)
- 10:20-12:00 | Emergencias Pediatricas - 4 Andar Sala 04
- 13:20-17:00 | Emergencias Cirurgicas (LABA2) - 4 Andar Cons 01

---

## Analise OpenClaw - Integracao Futura

Estudo realizado sobre o OpenClaw (215k stars) para possivel integracao:

### Conceitos Aplicaveis

1. **Gateway Multi-canal**: Receber notificacoes da plataforma via WhatsApp/Telegram
2. **Automacao com Cron**: Verificar avisos novos automaticamente
3. **Skills System**: Criar skill personalizada para consultar horarios
4. **Webhook Integration**: Disparar alertas 15min antes de cada aula
5. **Voice Wake**: Consultar horario por voz no macOS/iOS

### Roadmap

- [ ] Integrar com API do portal Clariens
- [ ] Notificacoes push antes das aulas
- [ ] Sincronizacao automatica de avisos
- [ ] Dashboard com frequencia e notas
- [ ] Bot WhatsApp para consultas rapidas

---

## Stack

- HTML5 / CSS3 / JavaScript (Vanilla)
- GitHub Pages (deploy)
- PWA (Service Worker ready)

## Ultima Atualizacao

Dados atualizados em: Periodo 2026/1 - Inicio 23/02/2026
