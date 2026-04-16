<p align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=170&color=0:0B1220,50:111827,100:1F2937&text=Cinco%20%7C%20Adilson%20Junior&fontColor=E5E7EB&fontSize=36&fontAlignY=36&desc=Backend%20Engineer%20in%20formation%20%7C%20Systems%20Architecture%20%7C%20Secure%20APIs&descAlignY=58&descSize=14" alt="header" />
</p>

<h3 align="center">Backend Developer em formacao com foco em arquitetura de sistemas, APIs seguras e analise tecnica de requisitos</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Marca-Cinco-111827?style=for-the-badge" alt="Marca" />
  <img src="https://img.shields.io/badge/Foco-Java%20Spring%20Boot%20Node.js-1F2937?style=for-the-badge" alt="Foco" />
  <img src="https://img.shields.io/badge/Objetivo-Backend%20Engineering-0F172A?style=for-the-badge" alt="Objetivo" />
</p>

---

## 1) Header

Construo servicos backend e APIs REST para fluxos de negocio que exigem previsibilidade, seguranca basica e manutencao clara.

Como marca de engenharia, **Cinco** representa estrutura tecnica, decisoes orientadas por requisitos e foco em entrega funcional.

---

## 2) Sobre Mim

Sou **Adilson Junior (Cinco)**, com atuacao em formacao voltada para backend. Meu foco principal e projetar e implementar APIs REST com Java/Spring Boot e Node.js.

O que eu construo:
- APIs para cadastro, autenticacao, consulta e regras de negocio.
- Estruturas de projeto organizadas por camadas.
- Fluxos com validacao de entrada, tratamento de erro e padrao de resposta.

Como eu construo:
- Modelagem de requisitos antes da implementacao.
- Separacao clara entre controller, service e repository.
- Versionamento com Git e documentacao de endpoints.

Que problema eu resolvo:
- Sistemas sem padrao de arquitetura.
- APIs sem consistencia de contratos.
- Regras de negocio dispersas e dificeis de manter.

---

## 3) Stack Tecnica por Camadas

### Backend
<p>
  <img src="https://img.shields.io/badge/Java-111827?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/Spring%20Boot-111827?style=for-the-badge&logo=springboot&logoColor=white" alt="Spring Boot" />
  <img src="https://img.shields.io/badge/Node.js-111827?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js" />
</p>

### Linguagens
<p>
  <img src="https://img.shields.io/badge/JavaScript-111827?style=for-the-badge&logo=javascript&logoColor=white" alt="JavaScript" />
  <img src="https://img.shields.io/badge/Python-111827?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
</p>

### Infra / Ferramentas
<p>
  <img src="https://img.shields.io/badge/Git%20%26%20GitHub-111827?style=for-the-badge&logo=git&logoColor=white" alt="Git e GitHub" />
  <img src="https://img.shields.io/badge/Linux-111827?style=for-the-badge&logo=linux&logoColor=white" alt="Linux" />
  <img src="https://img.shields.io/badge/Postman-111827?style=for-the-badge&logo=postman&logoColor=white" alt="Postman" />
</p>

### Frontend Basico (Secundario)
<p>
  <img src="https://img.shields.io/badge/HTML-111827?style=for-the-badge&logo=html5&logoColor=white" alt="HTML" />
  <img src="https://img.shields.io/badge/CSS-111827?style=for-the-badge&logo=css3&logoColor=white" alt="CSS" />
</p>

---

## 4) Engenharia de Software

- UML aplicada a fluxos reais: casos de uso, classes e sequencia.
- Modelagem de APIs com contratos claros de request/response.
- Arquitetura REST com recursos, verbos HTTP e codigos de status coerentes.
- Boas praticas de backend: principio de responsabilidade unica, separacao por camadas e estrutura modular.
- Versionamento e organizacao de projetos para evolucao incremental.

---

## 5) Mermaid - Fluxo Tecnico de API Segura

```mermaid
flowchart TD
    A[Cliente Web/Mobile] --> B[API Gateway/Controller]
    B --> C{Validacao de Entrada}
    C -- invalida --> D[Retorna 400 com detalhes]
    C -- valida --> E[Autenticacao JWT]
    E -- token invalido --> F[Retorna 401]
    E -- token valido --> G[Autorizacao por Role]
    G -- negado --> H[Retorna 403]
    G -- permitido --> I[Service Layer]
    I --> J[Regras de Negocio]
    J --> K[Repository]
    K --> L[(Banco de Dados)]
    J --> M[Auditoria e Logs]
    M --> N[Monitoramento Basico]
    L --> O[Response Padronizada]
    O --> A
```

---

## 6) Seguranca Aplicada em APIs

- Validacao de entrada para reduzir risco de payload malformado.
- Autenticacao e autorizacao com JWT e controle por permissao.
- Testes de API no Postman cobrindo cenarios positivos e negativos.
- Atencao a vulnerabilidades comuns do OWASP Top 10 (entrada, auth e exposicao indevida).

---

## 7) Roadmap Tecnico

- Construir APIs REST completas com Java/Spring Boot.
- Integrar persistencia com banco relacional e consultas estruturadas.
- Aplicar seguranca basica em endpoints sensiveis.
- Evoluir estrutura de projeto Spring Boot para padrao de producao.
- Usar Python para automacao de tarefas de backend.
- Modelar sistemas reais com UML e fluxos de negocio.

---

## 8) Projetos Tecnicos (Estrutura)

### Projeto A - API de Gestao Operacional
- Arquitetura: camadas (controller/service/repository).
- Problema resolvido: centralizar operacoes e reduzir retrabalho manual.
- Endpoints/fluxo: autenticacao, CRUD de entidades, filtros e paginacao.
- Stack: Java, Spring Boot, SQL, Postman.

### Projeto B - Servico de Autenticacao e Autorizacao
- Arquitetura: API REST com JWT e middleware de permissao.
- Problema resolvido: proteger rotas e controlar acesso por perfil.
- Endpoints/fluxo: login, refresh, validacao de token, permissoes.
- Stack: Node.js, JavaScript, banco de dados, Postman.

### Projeto C - Automacao de Rotinas Backend
- Arquitetura: scripts modulares para tarefas repetitivas.
- Problema resolvido: reduzir tempo operacional em processos tecnicos.
- Endpoints/fluxo: leitura de dados, validacao, geracao de saida.
- Stack: Python, Linux, Git.

---

## 9) GitHub Stats - Technical Dashboard

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=5inco-dev&show_icons=true&theme=tokyonight&hide_border=true" alt="Stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=5inco-dev&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" />
  <img height="165" src="https://github-readme-streak-stats.herokuapp.com/?user=5inco-dev&theme=tokyonight&hide_border=true" alt="Streak" />
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/5inco-dev/5inco-dev/output/github-contribution-grid-snake-dark.svg" alt="Contribution Snake" />
</p>

---

## 10) Mindset de Engenharia

- Sistemas devem ser previsiveis e observaveis.
- Codigo deve ser legivel, testavel e escalavel.
- Seguranca comeca na arquitetura, nao no fim do projeto.
- Software bom resolve problema de negocio com estrutura tecnica.

---

## 11) Contato

<p align="center">
  <a href="https://github.com/5inco-dev" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-111827?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
  <a href="https://www.linkedin.com/in/adilson-junior" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:seu-email@exemplo.com">
    <img src="https://img.shields.io/badge/E--mail-1F2937?style=for-the-badge&logo=gmail&logoColor=white" alt="E-mail" />
  </a>
</p>

---

## 12) Assinatura

**Cinco - construindo sistemas com logica, estrutura e seguranca aplicada.**
