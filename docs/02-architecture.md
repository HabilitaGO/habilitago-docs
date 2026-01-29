# Arquitetura (PT-BR)

Visão geral dos componentes:

- **Web**: landing/portal público
- **Admin**: painel administrativo
- **API (Backend)**: autenticação, agendamento, pagamentos, notificações, regras de negócio
- **Mobile (Expo)**: app do aluno/instrutor
- **DB**: Postgres (dados de usuários, aulas, pagamentos, avaliações, etc.)

## Fluxo (alto nível)
Mobile/Web/Admin → API → DB  
API → Serviços externos (pagamentos, e-mail, notificações)

---

# Architecture (EN-US)

High-level components:

- **Web**: public landing/portal
- **Admin**: admin dashboard
- **API (Backend)**: auth, scheduling, payments, notifications, business rules
- **Mobile (Expo)**: student/instructor app
- **DB**: Postgres (users, lessons, payments, reviews, etc.)

## Flow (high level)
Mobile/Web/Admin → API → DB  
API → External services (payments, email, notifications)
