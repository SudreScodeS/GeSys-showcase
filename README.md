<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:14213D,100:7B2233&height=170&section=header&text=GeSys&fontColor=ffffff&fontSize=42&fontAlignY=38&desc=Agenda%20e%20gest%C3%A3o%20multiempresa%20para%20cl%C3%ADnicas%2C%20sal%C3%B5es%20e%20consultorias&descAlignY=60&descSize=16" width="100%"/>

<img src="https://img.shields.io/badge/c%C3%B3digo-privado%20%C2%B7%20sob%20solicita%C3%A7%C3%A3o-7B2233?style=flat-square&logo=github"/>

</div>

**GeSis Agenda** é um SaaS de **agendamento white-label e multiempresa**: o mesmo sistema vira a agenda de uma clínica, de um salão ou de uma consultoria só por configuração (nome, cores, serviços, textos e regras), sem mudar código. Produto da **SUDRA Technologies**.

<p align="center"><a href="https://gesis.onrender.com"><img src="https://img.shields.io/badge/%F0%9F%9A%80%20Ver%20demo%20ao%20vivo-14213D?style=for-the-badge"/></a></p>

> A demo roda no plano gratuito da Render, então o primeiro acesso pode levar alguns segundos para acordar.


## 🧪 Nichos de demonstração
A mesma base atende três empresas fictícias: uma **clínica**, um **salão de beleza** e uma **consultoria**, cada uma com marca, serviços e equipe próprios.

## ✨ Funcionalidades
| Módulo | O que faz |
|---|---|
| 🗓️ **Agendamento online** | Site público da empresa, escolha de serviço, profissional, dia e horário, com login só na hora de confirmar |
| ⏱️ **Motor de disponibilidade** | Jornada, exceções e bloqueios, intervalo por duração do serviço + folga, sempre no fuso da unidade |
| 👥 **Papéis** | Painéis separados para admin, recepção, profissional e cliente, além do painel de operação da plataforma |
| 🧑‍⚕️ **Profissionais** | Agenda própria, disponibilidade, perfil, clientes e convites para entrar na equipe |
| 💰 **Financeiro** | Extrato, filtros, rankings, exportação em PDF e comissão por profissional |
| 💳 **Pagamentos** | Cliente paga o agendamento via InfinitePay; assinatura dos planos da plataforma via Stripe |
| 🔔 **Avisos** | Notificações Web Push para a equipe e lembretes para o cliente, disparados pelo GitHub Actions |
| 🏢 **Multiempresa** | Planos agenda / booking / full, contratação self-serve, multi-unidade e desfazer exclusões em até 24h |
| 🌎 **Extras** | pt / en / es, painel usável no celular, cookies e LGPD |

## 🧰 Stack
<p align="center"><img src="https://skillicons.dev/icons?i=ts,nextjs,react,tailwind,postgres,githubactions&theme=dark"/></p>
<p align="center"><sub>Next.js 15 · React 19 · TypeScript · Tailwind v4 · PostgreSQL (Neon) · Object Storage S3 · Stripe · InfinitePay · Web Push · PDFKit · date-fns-tz · GitHub Actions · Render</sub></p>

## 👨‍💻 Meu papel
Desenvolvi o sistema: a arquitetura em camadas (domínio puro isolado da infraestrutura), o motor de disponibilidade e o ciclo de vida do agendamento, os painéis de cada papel, o financeiro com comissões, as integrações com InfinitePay, Stripe e Web Push, o multiempresa por configuração e o deploy na Render com banco Neon. O projeto segue spec-driven development, com user stories e decisões registradas em ADRs.

---
📫 **Código disponível sob solicitação:** v.sudresilva@gmail.com · [LinkedIn](https://www.linkedin.com/in/victor-sudre/)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:7B2233,100:14213D&height=90&section=footer" width="100%"/>
