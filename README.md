<p align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=170&color=0:0B1220,50:111827,100:1F2937&text=Cinco%20%7C%20Adilson%20Junior&fontColor=E5E7EB&fontSize=36&fontAlignY=36&desc=Backend%20Engineer%20in%20formation%20%7C%20Systems%20Architecture%20%7C%20Secure%20APIs&descAlignY=58&descSize=14" alt="header" />
</p>

<h3 align="center">Backend Developer em formacao com foco em APIs, arquitetura de sistemas, modelagem e seguranca aplicada</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Marca-Cinco-111827?style=for-the-badge" alt="Marca" />
  <img src="https://img.shields.io/badge/Foco-Java%20Spring%20Boot%20Node.js-1F2937?style=for-the-badge" alt="Foco" />
  <img src="https://img.shields.io/badge/Objetivo-Backend%20Engineering-0F172A?style=for-the-badge" alt="Objetivo" />
</p>

---

## 1) Header

Construo APIs REST e servicos backend com foco em estrutura, consistencia e seguranca aplicada.

Como marca tecnica, **Cinco** representa backend, sistemas bem modelados e engenharia aplicada a problemas reais.

---

## 2) Sobre Mim

Sou **Adilson Junior (Cinco)**, em formacao voltada para backend. Meu foco principal e projetar e implementar APIs REST com Java/Spring Boot e Node.js.

O que eu construo:
- APIs para cadastro, autenticacao, consulta e regras de negocio.
- Estruturas de projeto organizadas por camadas.
- Fluxos com validacao de entrada, tratamento de erro e padrao de resposta.

Como eu construo:
- Modelagem de requisitos antes da implementacao.
- Separacao clara entre controller, service e repository.
- Versionamento com Git e documentacao de endpoints.

Que problemas eu resolvo:
- Sistemas sem padrao de arquitetura.
- APIs sem consistencia de contratos.
- Regras de negocio dispersas, com alto custo de manutencao.

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

### Infra e Ferramentas
<p>
  <img src="https://img.shields.io/badge/Git%20%26%20GitHub-111827?style=for-the-badge&logo=git&logoColor=white" alt="Git e GitHub" />
  <img src="https://img.shields.io/badge/Linux-111827?style=for-the-badge&logo=linux&logoColor=white" alt="Linux" />
  <img src="https://img.shields.io/badge/Postman-111827?style=for-the-badge&logo=postman&logoColor=white" alt="Postman" />
</p>

### Frontend Basico
<p>
  <img src="https://img.shields.io/badge/HTML-111827?style=for-the-badge&logo=html5&logoColor=white" alt="HTML" />
  <img src="https://img.shields.io/badge/CSS-111827?style=for-the-badge&logo=css3&logoColor=white" alt="CSS" />
</p>

---

## 4) Engenharia de Software

- UML aplicada a sistemas reais: casos de uso, classes e sequencia.
- Modelagem de APIs REST com contratos claros de request/response.
- Arquitetura em camadas: Controller, Service e Repository.
- Boas praticas de codigo limpo: SOLID basico, separacao de responsabilidades e estrutura modular.
- Versionamento e organizacao de projetos para evolucao incremental.

---

## 5) Modelagem e Visualizacao com Mermaid

```mermaid
flowchart TD
    A[Cliente Web/Mobile] --> B[Controller]
    B --> C{Validacao de Entrada}
    C -- invalida --> D[Retorna 400]
    C -- valida --> E[Autenticacao JWT]
    E -- token invalido --> F[Retorna 401]
    E -- token valido --> G[Autorizacao Basica]
    G -- negado --> H[Retorna 403]
    G -- permitido --> I[Service]
    I --> J[Regras de Negocio]
    J --> K[Repository]
    K --> L[(Banco de Dados)]
    J --> M[Logs e Auditoria]
    L --> N[Resposta Padronizada]
    N --> A
```

---

## 6) Seguranca Aplicada

- Validacao de entrada para reduzir risco de payload malformado.
- Autenticacao e autorizacao basica com JWT ou mecanismo equivalente.
- Testes de API com Postman cobrindo cenarios positivos e negativos.
- Consciencia das vulnerabilidades comuns do OWASP Top 10.

---

## 7) Roadmap Tecnico

- Construir APIs REST completas com Java/Spring Boot.
- Integrar bancos de dados relacionais e consultas estruturadas.
- Evoluir Spring Boot com DTOs, exceptions e organizacao de camadas.
- Aplicar Python em automacao e apoio a backend.
- Modelar sistemas reais com UML antes da implementacao.
- Aplicar seguranca basica em APIs desde a concepcao.

---

## 8) 🧪 Engineering Lab

### Backend APIs (Java / Spring Boot)
- Foco: construcao de APIs REST com camadas bem definidas.
- Evolucao: CRUD, validacao, tratamento de erro e estrutura de projeto.
- Estudo: controller, service, repository, DTOs e excecoes.

### Node.js APIs
- Foco: rotas REST e manipulacao de dados em backend simples.
- Evolucao: estrutura de endpoints, middlewares e organizacao de fluxo.
- Estudo: autenticacao basica, respostas padronizadas e integracao com dados.

### Python (Automacao e Estudos Aplicados)
- Foco: scripts para automacao e apoio a backend.
- Evolucao: processamento de dados, leitura de arquivos e tarefas repetitivas.
- Estudo: logica aplicada e produtividade tecnica.

### Modelagem de Sistemas (UML & Mermaid)
- Foco: diagramacao antes do codigo.
- Evolucao: fluxos, APIs, autenticacao e arquitetura backend.
- Estudo: estrutura de sistemas reais e representacao visual de requisitos.

### API Testing (Postman)
- Foco: teste de endpoints REST e validacao de respostas.
- Evolucao: cenarios positivos, negativos e de seguranca basica.
- Estudo: contratos de API, status code e consistencia de retorno.

### Status
- Todos os itens representam pratica ativa de engenharia de software em evolucao continua.

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

- Software deve ser tratado como sistema estruturado.
- Seguranca deve fazer parte da arquitetura.
- Codigo limpo deve ser padrao, nao excecao.
- Sistemas devem ser previsiveis, escalaveis e mantiveis.
- O objetivo e resolver problemas reais com engenharia.

---

## 11) Contato

<p align="center">
  <a href="https://github.com/5inco-dev" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-111827?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
  <a href="https://www.linkedin.com/in/adilson-junior" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:dev.adilsonj@gmail.com">
    <img src="https://img.shields.io/badge/E--mail-1F2937?style=for-the-badge&logo=gmail&logoColor=white" alt="E-mail" />
  </a>
</p>

---

## 12) Assinatura

**Cinco - construindo sistemas com logica, estrutura e seguranca aplicada.**
