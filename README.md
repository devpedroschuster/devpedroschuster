### Olá! 👋 Eu sou Pedro Schuster

> Desenvolvedor Full-Stack Júnior 🚀
> Construindo aplicações SaaS multi-tenant com foco em arquitetura segura e escalável.

Atualmente sou o desenvolvedor responsável pelo **Nexofy**, uma plataforma SaaS multi-tenant de gestão para estúdios fitness e dança, construída do zero — do banco de dados à interface. No dia a dia, trabalho tanto na definição da arquitetura (modelagem, RLS, RPCs) quanto na experiência do usuário final (React, componentização, performance).

---

### 🛠️ Stack principal

**Front-end**

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

**Back-end & Dados**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![TanStack Query](https://img.shields.io/badge/TanStack_Query-FF4154?style=for-the-badge&logo=reactquery&logoColor=white)

**Ferramentas**

![Git](https://img.shields.io/badge/Git-E44C30?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![VSCode](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

---

### 🚀 Destaque: Nexofy

Plataforma SaaS multi-tenant para gestão de estúdios (alunos, professores, agenda, comissões e financeiro), com:

- **Isolamento de dados multi-tenant** via `estudio_id` + Row Level Security no Supabase
- **RPCs transacionais em PostgreSQL** (ex: agendamento com `pg_advisory_xact_lock` para evitar concorrência em vagas limitadas)
- **Sistema de impersonation** para suporte administrativo, com contexto próprio e fallback seguro de tenant ativo
- **Edge Functions** para geração de repasses financeiros e controle de acesso de professores
- Front-end em React + TanStack Query + Vite, com design system próprio (tema "Midnight Indigo")

🔗 [Nexofy](https://www.nexofy.com.br/super) · [Repositório](https://github.com/devpedroschuster/nexofy)

---

### 🌱 Aprofundando

Meu foco atual é elevar o nível de engenharia do que já construí: auditorias sistemáticas de segurança e qualidade de código, testes automatizados e boas práticas de Git Flow para trabalhar melhor em equipe.

---

### 📫 Como me encontrar

- **LinkedIn:** [in/pedro-regus-schuster-382b04104](https://www.linkedin.com/in/pedro-regus-schuster-382b04104/)
- **E-mail:** devpedroschuster@gmail.com
