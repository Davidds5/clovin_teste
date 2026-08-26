# Olá, eu sou o David Silva 👋

## 💻 Engenheiro de Software Fullstack | Java & Spring Boot | Next.js & TypeScript

Desenvolvedor focado na arquitetura, segurança e deploy de **produtos SaaS escaláveis e em produção**. Combino a solidez e governança do ecossistema Java/Spring Boot no backend com a performance e refinamento visual do Next.js e TypeScript no frontend.

Além de construir produtos comerciais, produzo conteúdo e compartilho rotina de engenharia ao vivo no canal **Clovin DEV**.

---

## 🚀 SaaS & Produtos em Produção

### 🏗️ ObraSync — Gestão Visual de Obras & Portal do Cliente
> **Problema & Solução:** Arquitetos e construtores perdiam horas enviando relatórios e fotos dispersas por WhatsApp. O ObraSync centraliza o diário de obra com linha do tempo fotográfica, cálculo de cronograma físico e portal do cliente em tempo real via Magic Link.

<div align="center">

<img src="https://img.shields.io/badge/Next.js_16-000000?style=for-the-badge&logo=nextdotjs&logoColor=white"/>
<img src="https://img.shields.io/badge/React_19-20232A?style=for-the-badge&logo=react&logoColor=61DAFB"/>
<img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white"/>
<img src="https://img.shields.io/badge/Prisma_ORM-2D3748?style=for-the-badge&logo=prisma&logoColor=white"/>
<img src="https://img.shields.io/badge/PostgreSQL_Neon-316192?style=for-the-badge&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/Cloudinary-3448C5?style=for-the-badge&logo=cloudinary&logoColor=white"/>
<img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white"/>
<img src="https://img.shields.io/badge/Render-46E3B7?style=for-the-badge"/>

</div>

**Destaques de Engenharia & Segurança:**
- **Multi-Tenant Real:** Isolamento estrito de dados automatizado com *Prisma Client Extension* + *AsyncLocalStorage*.
- **Segurança Binária (AppSec):** Validação de *Magic Bytes* no upload (`FF D8 FF`, `89 50 4E 47`, `25 50 44 46`) para prevenir spoofing de MIME types.
- **Governança de Sessão:** Invalidação instantânea de tokens JWT (`tokenVersion`) e painel Super Admin com auditoria de acessos (`AccessLog`) e gestão de trial de 30 dias.
- **Portal do Cliente:** Acesso sem atrito de login via Magic Link (UUID v4) otimizado para celulares.
- 🟢 **Status:** **Em produção com primeiros clientes ativos (trial).**

🌐 [**Acessar Produto no Ar (Live)**](https://obrasync-bf1t.onrender.com) | 🔗 [Repositório GitHub](https://github.com/Davidds5/obrasync)

---

### 💅 BelasUnhas / Manicure API — SaaS de Agendamentos & Gestão de Salões
> **Problema & Solução:** Salões e esmalterias perdem faturamento e geram atritos por gerenciarem horários em cadernos e conversas soltas. A plataforma fornece infraestrutura completa para auto-onboarding, auto-agendamento de clientes e controle financeiro.

<div align="center">

<img src="https://img.shields.io/badge/Java_21-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white"/>
<img src="https://img.shields.io/badge/Spring_Boot_3-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white"/>
<img src="https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white"/>
<img src="https://img.shields.io/badge/JWT-000000?style=for-the-badge"/>
<img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/Flyway-CC0200?style=for-the-badge&logo=flyway&logoColor=white"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/Render-46E3B7?style=for-the-badge"/>

</div>

**Destaques de Engenharia & Segurança:**
- **Arquitetura em Camadas & DTOs:** Estrutura desacoplada utilizando MapStruct, JPA Specifications para filtros dinâmicos e paginação.
- **Segurança & RBAC:** Autenticação stateless com Spring Security e JWT com controle de perfis (`CLIENTE` / `ADMIN`).
- **Práticas de DevOps:** Containerização com Docker **Multi-stage Build**, migrations versionadas com Flyway e deploy automatizado na nuvem (Render).
- **Qualidade & Testes:** Suíte de testes unitários e de integração com JUnit 5 e Mockito.

🌐 [**Documentação Interativa da API (Swagger)**](https://manicure-api-vi63.onrender.com/swagger-ui/index.html) | 🔗 [Repositório GitHub](https://github.com/Davidds5/manicure_api)

---

## 🛠️ Tech Stack & Ferramentas

<div align="center">

### 🚀 Backend & Linguagens
<img src="https://img.shields.io/badge/Java_21-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white"/>
<img src="https://img.shields.io/badge/Spring_Boot_3-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white"/>
<img src="https://img.shields.io/badge/Spring_Data_JPA-59666C?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white"/>
<img src="https://img.shields.io/badge/MapStruct-000000?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white"/>

<br>

### 🎨 Frontend & UI
<img src="https://img.shields.io/badge/Next.js_15%2F16-000000?style=for-the-badge&logo=nextdotjs&logoColor=white"/>
<img src="https://img.shields.io/badge/React_19-20232A?style=for-the-badge&logo=react&logoColor=61DAFB"/>
<img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white"/>
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
<img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white"/>

<br>

### 🏗️ Arquitetura, Segurança & Boas Práticas
<img src="https://img.shields.io/badge/Multi--Tenant_Architecture-4A154B?style=for-the-badge"/>
<img src="https://img.shields.io/badge/REST_API-02569B?style=for-the-badge"/>
<img src="https://img.shields.io/badge/AppSec_Hardening-black?style=for-the-badge"/>
<img src="https://img.shields.io/badge/SOLID-FF6F00?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Clean_Code-000000?style=for-the-badge"/>
<img src="https://img.shields.io/badge/DTO_Pattern-4CAF50?style=for-the-badge"/>

<br>

### 🗄️ Bancos de Dados & ORMs
<img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/Prisma_ORM-2D3748?style=for-the-badge&logo=prisma&logoColor=white"/>
<img src="https://img.shields.io/badge/Hibernate_JPA-59666C?style=for-the-badge&logo=hibernate&logoColor=white"/>
<img src="https://img.shields.io/badge/Flyway-CC0200?style=for-the-badge&logo=flyway&logoColor=white"/>

<br>

### 🧪 Testes & Qualidade
<img src="https://img.shields.io/badge/JUnit_5-25A162?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Mockito-FFCA28?style=for-the-badge"/>
<img src="https://img.shields.io/badge/MockMvc-6DB33F?style=for-the-badge"/>

<br>

### ⚙️ DevOps & Ferramentas
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/Render-46E3B7?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Git-E34F26?style=for-the-badge&logo=git&logoColor=white"/>
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github"/>
<img src="https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apache-maven&logoColor=white"/>
<img src="https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black"/>

</div>

---

## 🎥 Canal & Comunidade (Clovin DEV)

Produzo conteúdo técnico e realizo lives demonstrando desenvolvimento de software na prática, boas práticas de engenharia e disciplina de estudos.

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-David_Silva-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/david-silva-17b2882bb)
[![Portfólio](https://img.shields.io/badge/Portfólio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://davidds5.github.io/portfolio_clovin/)
[![YouTube](https://img.shields.io/badge/YouTube-Clovin_DEV-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/@SEU_CANAL_AQUI)
[![TikTok](https://img.shields.io/badge/TikTok-Clovin_DEV-000000?style=for-the-badge&logo=tiktok&logoColor=white)](https://tiktok.com/@SEU_PERFIL_AQUI)

</div>

---

## 📫 Contato & Oportunidades
Aberto a novas oportunidades profissionais como Desenvolvedor Fullstack / Backend, consultorias e parcerias em projetos SaaS.

- 💼 **LinkedIn:** [linkedin.com/in/david-silva-17b2882bb](https://www.linkedin.com/in/david-silva-17b2882bb)
- 🌐 **Portfólio Web:** [davidds5.github.io/portfolio_clovin](https://davidds5.github.io/portfolio_clovin/)
- 📄 **Currículo Web:** [Acessar Currículo](https://davidds5.github.io/portfolio_clovin/curriculo_david_pt.html)
