<div align="center">
   <h1>
      dop Full Cycle 3.0
   </h1>
  <!-- 
  <h1>
    <img width="490" height="110" alt="dopme io" src="https://github.com/dopme-io/dopmeRepo/blob/main/assests/dopme.png" />
  </h1>
  </br>
  <img width="663" height="69" src="" /> 
   -->
  
  [![.NET](https://github.com/dopme-io/dopmeSite/actions/workflows/dotnet.yml/badge.svg)](https://github.com/dopme-io/dopmeSite/actions/workflows/dotnet.yml)
  [![CI - Build & Test](https://github.com/dopme-io/dopmeSite/actions/workflows/ci.yml/badge.svg)](https://github.com/dopme-io/dopmeSite/actions/workflows/ci.yml)
  [![Dependencies Check & Update](https://github.com/dopme-io/dopmeSite/actions/workflows/dependencies.yml/badge.svg)](https://github.com/dopme-io/dopmeSite/actions/workflows/dependencies.yml)
  [![Deploy to CloudFlare Pages](https://github.com/dopme-io/dopmeSite/actions/workflows/deploy.yml/badge.svg)](https://github.com/dopme-io/dopmeSite/actions/workflows/deploy.yml)
  [![Monitoring & Performance](https://github.com/dopme-io/dopmeSite/actions/workflows/monitoring.yml/badge.svg)](https://github.com/dopme-io/dopmeSite/actions/workflows/monitoring.yml)
  
  ![Status do build](https://img.shields.io/github/actions/workflow/status/dopme-io/REPO/workflow.yml)
  ![Licença](https://img.shields.io/github/license/dopme-io/REPO)
  ![Versão](https://img.shields.io/github/package-json/v/dopme-io/REPO)

   **Repositório base/template** com CI/CD completo para qualquer tecnologia backend e frontend.  
   Inclui workflows de integração contínua, deploy, gerenciamento de dependências e monitoramento prontos para uso.
</div>
</br>

## 📑 Índice

1. [Visão Geral](#visão-geral)
2. [🚀 Roadmap de Estudos](#-roadmap-de-estudos)
3. [📅 Cronograma de Estudos](#-cronograma-de-estudos)
4. [CI/CD e Workflows](#cicd-e-workflows)
5. [Instalação](#instalação)
6. [Como Usar](#como-usar)
7. [Configuração](#configuração)
8. [Contribuições](#contribuições)
9. [Artigos & Conteúdos](#artigos--conteúdos)
10. [Licença](#licença)
11. [Contato](#contato)

## Visão Geral

O **dopBase** é um repositório base/template completo com pipelines de CI/CD prontos para uso, suportando múltiplas tecnologias e frameworks. Este projeto fornece uma base sólida para iniciar qualquer aplicação com as melhores práticas de DevOps.

### 🎯 Como Usar Este Template

Este repositório serve como base para novos projetos. Para usá-lo:

1. **Clone ou use como template**:
   ```bash
   # Opção 1: Clone direto
   git clone https://github.com/daniloopinheiro/dopBase.git meu-novo-projeto
   
   # Opção 2: Use o botão "Use this template" no GitHub
   ```

2. **Adicione seu código**: Os workflows detectam automaticamente a tecnologia e configuram tudo
3. **Configure secrets** (opcional): Para deploy automático
4. **Comece a desenvolver**: Os workflows funcionam imediatamente!

> **Nota**: Arquivos de configuração específicos (como `k6-test.js`, `.pa11yci.json`, `sonar-project.properties`) não estão incluídos. Você pode criá-los conforme necessário para seu projeto específico.

### ✨ Recursos Principais

- 🔄 **CI/CD Automático**: Workflows prontos para build, teste e deploy
- 🌐 **Multi-tecnologia**: Suporta Node.js, Python, .NET, Java, Go e mais
- 🔒 **Segurança**: Scans automáticos de vulnerabilidades
- 📦 **Gerenciamento de Dependências**: Atualização automática e verificação de segurança
- 🤖 **Automação de PRs**: Labeling, validações e estatísticas automáticas
- 📊 **Monitoramento**: Performance, acessibilidade e qualidade de código
- 🚀 **Deploy Automático**: Integração com Vercel, Netlify, Heroku, AWS, Azure e mais

---

## 🚀 Roadmap de Estudos

Este roadmap foi organizado de forma progressiva para garantir um aprendizado estruturado e eficiente. Siga a ordem sugerida para obter o melhor aproveitamento.

### 📍 Comece por Aqui

**Informações importantes para um bom andamento do curso.**

> ⚠️ **Importante**: Leia atentamente esta seção antes de iniciar os estudos. Ela contém informações essenciais sobre a estrutura do curso, metodologia e recursos disponíveis.

---

## 📚 Módulo 1: Fundamentos e Ferramentas Essenciais

### 1.1 Docker
**Status**: ✅ Disponível | 📜 Certificado Disponível

Você vai aprender como criar e administrar ambientes isolados através de containers com o Docker.

**Conceitos abordados:**
- Containers e imagens
- Dockerfile e Docker Compose
- Volumes e networks
- Orquestração básica

---

### 1.2 Padrões e Técnicas Avançadas com Git e Github
**Status**: ✅ Disponível | 📜 Certificado Disponível

Como trabalhar com Gitflow e convenções de commits para padronização e facilitar CodeReviews. O manual para performance em equipe do Git.

**Conceitos abordados:**
- Gitflow workflow
- Convenções de commits semânticos
- Code reviews eficientes
- Branching strategies

---

## 📚 Módulo 2: Fundamentos de Arquitetura de Software

### 2.1 Fundamentos da Arquitetura de Software
**Status**: ✅ Disponível | 📜 Certificado Disponível

Performance, Escalabilidade e Resiliência são fundamentos essenciais para que um software seja construído da forma correta. É necessário entender os conceitos de fundamentos de arquitetura de software para se projetar e construir boas aplicações.

**Conceitos abordados:**
- Performance
- Escalabilidade
- Resiliência
- Princípios de design

---

### 2.2 SOLID Express
**Status**: ✅ Disponível | 📜 Certificado Disponível

Existem cinco princípios de design que todo desenvolvedor precisa seguir para criar bons códigos. O SOLID Express trata de cada um desses princípios e como utilizá-los.

**Conceitos abordados:**
- Single Responsibility Principle (SRP)
- Open/Closed Principle (OCP)
- Liskov Substitution Principle (LSP)
- Interface Segregation Principle (ISP)
- Dependency Inversion Principle (DIP)

---

### 2.3 Comunicação entre Sistemas
**Status**: 🔄 Em Progresso (24% Concluído)

REST, gRPC, GraphQL. Como utilizar protocolos distintos na sua aplicação para que se comuniquem de forma inteligente entre elas e externamente.

**Conceitos abordados:**
- REST API
- gRPC
- GraphQL
- Comparação de protocolos
- Quando usar cada abordagem

---

## 📚 Módulo 3: Domain Driven Design (DDD)

### 3.1 Domain Driven Design
**Status**: ✅ Disponível | 📜 Certificado Disponível

Domain Driven Design (DDD) é um conceito capaz de mudar a forma que você projeta e constrói software.

**Conceitos abordados:**
- Bounded Contexts
- Ubiquitous Language
- Domain Models
- Strategic Design

---

### 3.2 DDD: Modelagem Tática e Patterns
**Status**: 🔄 Em Progresso (2% Concluído)

Como modelar um software utilizando DDD e como aplicar os principais patterns que estão em volta do conceito de modelagem.

**Conceitos abordados:**
- Entities e Value Objects
- Aggregates
- Domain Services
- Repositories
- Domain Events

---

### 3.3 Event Storming na Prática
**Status**: ✅ Disponível | 📜 Certificado Disponível

Envolva toda equipe de negócios e técnica, através de uma maneira colaborativa, prática e hands-on de apresentar todos os eventos do sistema.

**Conceitos abordados:**
- Workshop de Event Storming
- Identificação de eventos
- Mapeamento de domínios
- Colaboração entre equipes

---

## 📚 Módulo 4: Arquiteturas de Aplicação

### 4.1 Arquitetura Hexagonal (Ports and Adapters)
**Status**: ✅ Disponível | 📜 Certificado Disponível

É possível organizar sua aplicação em camadas e responsabilidades. Ports and Adapters permite desacoplar a lógica de negócio das tecnologias.

**Conceitos abordados:**
- Ports (interfaces)
- Adapters (implementações)
- Desacoplamento de tecnologias
- Testabilidade

---

### 4.2 Clean Architecture
**Status**: 🔄 Em Progresso (27% Concluído)

É possível ter reusabilidade de código, coesão, independência de tecnologia e testabilidade. A arquitetura limpa é um padrão criado para isso.

**Conceitos abordados:**
- Camadas da Clean Architecture
- Dependency Rule
- Use Cases
- Frameworks independence
- Testabilidade

---

## 📚 Módulo 5: Arquiteturas de Sistema

### 5.1 Sistemas Monolíticos
**Status**: 🔄 Em Progresso (1% Concluído)

Sistemas monolíticos podem não ser tão ruins, desde que criados de maneira correta, coesa e obedecendo alguns padrões importantes na criação do seu projeto.

**Conceitos abordados:**
- Quando usar monolitos
- Modularização de monolitos
- Padrões de organização
- Vantagens e desvantagens

---

### 5.2 Arquitetura Baseada em Microsserviços
**Status**: 🔄 Em Progresso (23% Concluído)

Os microsserviços permitem que um aplicativo grande seja separado em partes independentes menores, com cada parte tendo sua própria responsabilidade e autonomia de desenvolvimento.

**Conceitos abordados:**
- Princípios de microsserviços
- Decomposição de serviços
- Comunicação entre serviços
- Desafios e soluções

---

### 5.3 EDA - Event Driven Architecture
**Status**: 🔄 Em Progresso (0% Concluído)

Comunicação assíncrona com baixo acoplamento. Uma solução para a comunicação entre microserviços.

**Conceitos abordados:**
- Event-driven patterns
- Event sourcing
- CQRS
- Baixo acoplamento

---

## 📚 Módulo 6: Mensageria e Comunicação Assíncrona

### 6.1 RabbitMQ
**Status**: ✅ Disponível | 📜 Certificado Disponível

RabbitMQ é um dos sistemas de mensageria mais conhecidos, com intuito de facilitar a comunicação assíncrona de dados entre processos.

**Conceitos abordados:**
- Exchanges e Queues
- Routing patterns
- Message durability
- Clustering

---

### 6.2 Apache Kafka
**Status**: 🔄 Em Progresso (0% Concluído)

Veloz, escalável e versátil. Apache Kafka é mais uma ferramenta de mensageria porém com foco em grandes streams de dados e tempo real.

**Conceitos abordados:**
- Topics e Partitions
- Producers e Consumers
- Stream processing
- High throughput

---

## 📚 Módulo 7: Segurança e Autenticação

### 7.1 Autenticação e Keycloak
**Status**: 🔄 Em Progresso (19% Concluído)

Autenticação e autorização se tornam fáceis ao utilizar o Keycloak. Através do SSO, é possível dar acesso a múltiplos serviços sem necessidade de reautenticação.

**Conceitos abordados:**
- OAuth 2.0
- OpenID Connect
- Single Sign-On (SSO)
- Identity and Access Management

---

## 📚 Módulo 8: Projeto Prático - Codeflix

### 8.1 Arquitetura do Projeto Prático - Codeflix
**Status**: ✅ Disponível | 📜 Certificado Disponível

Entenda como irá funcionar toda arquitetura do projeto CodeFlix. O que podemos utilizar, como funciona o diagrama C4 e o que esperamos de resultado.

**Conceitos abordados:**
- Diagrama C4
- Arquitetura do projeto
- Decisões técnicas
- Estrutura de módulos

---

### 8.2 Backend - Admin Catálogo de Vídeo

#### 8.2.1 Codeflix - .NET (Back-end)
**Status**: 🔄 Em Progresso (5% Concluído)

Vamos criar todo backend para a gestão de conteúdos para a CodeFlix, utilizando .NET.

#### 8.2.2 Codeflix - Java (Back-end)
**Status**: 🔄 Em Progresso (1% Concluído)

Vamos criar todo backend para a gestão de conteúdos para a CodeFlix, utilizando Java.

#### 8.2.3 Codeflix - PHP
**Status**: ✅ Disponível

Vamos criar todo backend para a gestão de conteúdos para a CodeFlix, utilizando PHP.

#### 8.2.4 Codeflix - TypeScript (Back-end)
**Status**: ✅ Disponível

Vamos criar todo backend para a gestão de conteúdos para a CodeFlix, utilizando TypeScript.

---

### 8.3 Frontend - Codeflix

#### 8.3.1 Portal do Usuário - React.js (Front-end)
**Status**: 🔄 Em Progresso (0% Concluído)

Vamos criar a interface do usuário para a CodeFlix.

#### 8.3.2 Admin Catálogo de Vídeo - React.js (Front-end)
**Status**: 🔄 Em Progresso (8% Concluído)

Vamos criar o painel administrativo para a gestão de conteúdos para a CodeFlix.

---

### 8.4 Microsserviços - Codeflix

#### 8.4.1 Encoder de Vídeo com Go Lang
**Status**: 🔄 Em Progresso (5% Concluído)

Vamos criar o Encoder de Vídeos em Go Lang, responsável pela segurança e processamento dos vídeos em nossa plataforma.

#### 8.4.2 API do Catálogo com .NET (Back-end)
**Status**: 🔄 Em Progresso (1% Concluído)

Microsserviço: API do Catálogo com .NET (Back-end)

#### 8.4.3 API do Catálogo com Java (Back-end)
**Status**: ✅ Disponível

Microsserviço: API do Catálogo com Java (Back-end)

#### 8.4.4 API do Catálogo com PHP (Back-end)
**Status**: ✅ Disponível

Microsserviço: API do Catálogo com PHP (Back-end)

#### 8.4.5 API do Catálogo com Python (Back-end)
**Status**: ✅ Disponível

Microsserviço: API do Catálogo com Python (Back-end)

#### 8.4.6 API do Catálogo com TypeScript (Back-end)
**Status**: ✅ Disponível

Microsserviço: API do Catálogo com TypeScript (Back-end)

#### 8.4.7 Assinaturas com Python (Back-end)
**Status**: ✅ Disponível

Microsserviço: Assinaturas com Python (Back-end)

---

## 📚 Módulo 9: CI/CD e Integração Contínua

### 9.1 Integração Contínua
**Status**: ✅ Disponível | 📜 Certificado Disponível

Gerir um pipeline de CI, conseguindo automatizar vários processos é muito importante para trabalhar em ambientes críticos e aplicações de grande porte.

**Conceitos abordados:**
- Pipelines de CI
- Automação de testes
- Build automatizado
- Qualidade de código

---

## 📚 Módulo 10: Orquestração e Containers

### 10.1 Kubernetes
**Status**: 🔄 Em Progresso (24% Concluído)

Orquestre seus containers e automatize grande parte de seus processos manuais para implantar, gerir e escalar grandes aplicações em containers.

**Conceitos abordados:**
- Pods, Services, Deployments
- ConfigMaps e Secrets
- Ingress
- Auto-scaling
- Health checks

---

### 10.2 Service Mesh com Istio
**Status**: 🔄 Em Progresso (0% Concluído)

Controle como os microserviços compartilham dados entre si e além disso monitore e proteja seus containers no cluster.

**Conceitos abordados:**
- Service mesh architecture
- Traffic management
- Security policies
- Observability

---

## 📚 Módulo 11: API Gateway

### 11.1 API Gateway
**Status**: 🔄 Em Progresso (4% Concluído)

Um único ponto de entrada, transparência e segurança. Esses são os principais benefícios ao utilizar uma API Gateway em seu projeto.

**Conceitos abordados:**
- Padrão API Gateway
- Routing e load balancing
- Rate limiting
- Autenticação centralizada

---

### 11.2 API Gateway com Kong e Kubernetes
**Status**: 🔄 Em Progresso (29% Concluído)

Como utilizar o Kong e Kubernetes para criar um único ponto de entrada, transparência e segurança em uma camada a mais em seu projeto utilizando API Gateway.

**Conceitos abordados:**
- Kong Gateway
- Plugins do Kong
- Integração com Kubernetes
- Configuração avançada

---

## 📚 Módulo 12: Observabilidade

### 12.1 Observabilidade
**Status**: 🔄 Em Progresso (11% Concluído)

Conceitos e práticas para monitorar e entender o comportamento de sistemas distribuídos.

**Conceitos abordados:**
- Logs, Metrics, Traces
- Distributed tracing
- Monitoring strategies
- Alerting

---

### 12.2 Introdução a OpenTelemetry
**Status**: ✅ Disponível | 📜 Certificado Disponível

Capture, metrifique, monitore os registros e traces de toda a sua aplicação utilizando um padrão.

**Conceitos abordados:**
- OpenTelemetry standard
- Instrumentação
- Exporters
- Integração com ferramentas

---

## 📚 Módulo 13: Infrastructure as Code (IaC)

### 13.1 Terraform
**Status**: 🔄 Em Progresso (19% Concluído)

Trabalhe com IaC e transforme todo seu ambiente cloud em algo descartável. Com o Terraform você será capaz de criar, alterar e criar versões de infraestrutura com segurança e eficiência.

**Conceitos abordados:**
- Infrastructure as Code
- Providers
- State management
- Modules
- Multi-cloud

---

### 13.2 Ansible
**Status**: ✅ Disponível | 📜 Certificado Disponível

Automatize a implantação de seus projetos na nuvem. Provisione, gerencie toda configuração e orquestre intra-serviços utilizando o conceito de código declarativo e agentless.

**Conceitos abordados:**
- Configuration management
- Playbooks
- Roles
- Agentless architecture

---

### 13.3 GitOps
**Status**: ✅ Disponível | 📜 Certificado Disponível

Entenda um modelo unificado de implantação, gestão e monitoramento em projetos em containers.

**Conceitos abordados:**
- GitOps principles
- ArgoCD / Flux
- Declarative deployments
- Version control for infrastructure

---

## 📚 Módulo 14: Deploy em Cloud Providers

### 14.1 Deploy nas Cloud Providers - Codeflix
**Status**: 🔄 Em Progresso (32% Concluído)

Como utilizar os principais Cloud Providers para realizar deploy de suas aplicações.

**Conceitos abordados:**
- AWS, Azure, GCP
- Container services
- Serverless
- Best practices

---

## 🗺️ Fluxo de Aprendizado Recomendado

```
┌─────────────────────────────────────────────────────────────┐
│                    COMECE POR AQUI                          │
│              (Informações Importantes)                      │
└───────────────────────┬─────────────────────────────────────┘
                        │
        ┌───────────────┴───────────────┐
        │                               │
┌───────▼────────┐            ┌────────▼────────┐
│  Módulo 1      │            │  Módulo 2       │
│ Fundamentos    │            │ Arquitetura     │
│ Docker + Git   │            │ de Software     │
└───────┬────────┘            └────────┬────────┘
        │                               │
        └───────────────┬───────────────┘
                        │
        ┌───────────────▼───────────────┐
        │      Módulo 3: DDD            │
        │  (Domain Driven Design)       │
        └───────────────┬───────────────┘
                        │
        ┌───────────────▼───────────────┐
        │   Módulo 4: Arquiteturas      │
        │  Hexagonal + Clean Arch       │
        └───────────────┬───────────────┘
                        │
        ┌───────────────▼───────────────┐
        │   Módulo 5: Arquiteturas      │
        │  Monolito + Microserviços     │
        └───────────────┬───────────────┘
                        │
        ┌───────────────▼───────────────┐
        │   Módulo 6: Mensageria         │
        │  RabbitMQ + Kafka             │
        └───────────────┬───────────────┘
                        │
        ┌───────────────▼───────────────┐
        │   Módulo 7: Segurança         │
        │  Keycloak + Autenticação      │
        └───────────────┬───────────────┘
                        │
        ┌───────────────▼───────────────┐
        │   Módulo 8: Projeto Prático   │
        │      Codeflix                 │
        └───────────────┬───────────────┘
                        │
        ┌───────────────▼───────────────┐
        │   Módulo 9: CI/CD             │
        │  Integração Contínua          │
        └───────────────┬───────────────┘
                        │
        ┌───────────────▼───────────────┐
        │   Módulo 10: Orquestração     │
        │  Kubernetes + Istio           │
        └───────────────┬───────────────┘
                        │
        ┌───────────────▼───────────────┐
        │   Módulo 11: API Gateway      │
        │  Kong + Kubernetes             │
        └───────────────┬───────────────┘
                        │
        ┌───────────────▼───────────────┐
        │   Módulo 12: Observabilidade  │
        │  OpenTelemetry                 │
        └───────────────┬───────────────┘
                        │
        ┌───────────────▼───────────────┐
        │   Módulo 13: IaC               │
        │  Terraform + Ansible + GitOps │
        └───────────────┬───────────────┘
                        │
        ┌───────────────▼───────────────┐
        │   Módulo 14: Cloud Deploy     │
        │  AWS, Azure, GCP               │
        └───────────────────────────────┘
```

---

## 📊 Legenda de Status

| Ícone | Significado |
|-------|-------------|
| ✅ | Conteúdo disponível e completo |
| 🔄 | Em progresso (com percentual de conclusão) |
| 📜 | Certificado disponível ao concluir |
| ⚠️ | Atenção ou pré-requisito |

---

## 📅 Cronograma de Estudos

Para um planejamento detalhado e estruturado dos seus estudos, consulte o **[Cronograma de Estudos](CRONOGRAMA_ESTUDOS.md)**.

O cronograma inclui:

- 📅 **Planejamento semanal** de 60 semanas (cada semana em um arquivo na pasta [`semanas/`](semanas/): `semana-01.md` a `semana-60.md`)
- ⏰ **Estimativas de tempo** por módulo
- ✅ **Checklists** de progresso
- 🎯 **Metas intermediárias** e checkpoints
- 💡 **Dicas de estudo** e boas práticas
- 📈 **Acompanhamento** de progresso

### 🚀 Início Rápido do Cronograma

1. **Escolha sua carga horária**:
   - Intensivo: 4-6h/dia (~4-5 meses)
   - Moderado: 2-3h/dia (~8-10 meses)
   - Leve: 1-2h/dia (~12-15 meses)

2. **Siga o cronograma** semana a semana
3. **Marque as tarefas concluídas** no checklist
4. **Acompanhe seu progresso** regularmente

> 📖 **[Acesse o Cronograma Completo](CRONOGRAMA_ESTUDOS.md)** para começar seus estudos de forma organizada!

---

## CI/CD e Workflows

Este projeto inclui workflows completos de GitHub Actions para automação de todo o ciclo de desenvolvimento.

### 🚀 Workflows Disponíveis

#### 1. **CI - Build & Test** (`ci.yml`)
- ✅ Detecção automática de tecnologias
- 🏗️ Build automático para backend e frontend
- 🧪 Execução de testes
- 📊 Análise de código (Linting)
- 🔒 Scan de segurança com Trivy
- 📈 Análise de qualidade com SonarCloud

#### 2. **CD - Deploy** (`cd.yml`)
- 🚀 Deploy automático para múltiplas plataformas
- 🐳 Build e push de imagens Docker
- 📝 Criação automática de releases
- 🏷️ Geração de changelog

#### 3. **Dependencies Check** (`dependencies.yml`)
- 🔍 Verificação de vulnerabilidades
- 📦 Detecção de pacotes desatualizados
- 🔄 Atualização automática de dependências
- ⚖️ Verificação de licenças

#### 4. **PR Automation** (`pr-automation.yml`)
- 🏷️ Labeling automático
- 📏 Validação de título semântico
- 📊 Estatísticas de mudanças
- 🤖 Auto-merge de PRs do Dependabot

#### 5. **Monitoring** (`monitoring.yml`)
- 🔍 Lighthouse audit
- ⚡ Testes de performance com k6
- 🔒 Verificação de SSL
- 📊 Análise de cobertura de código

#### 6. **Auto Tag & Version** (`auto-tag.yml`) ⭐ NOVO
- 🏷️ Criação automática de tags quando há merge para `main`
- 📊 Versionamento semântico baseado em commits convencionais
- 🔄 Detecta automaticamente o tipo de versão (major, minor, patch)
- 🎯 Integrado com CD para releases automáticas

### 📚 Documentação dos Workflows

- 📖 [Guia Completo](.github/README.md) - Documentação detalhada de todos os workflows
- 🚀 [Quick Start](.github/QUICKSTART.md) - Comece em 5 minutos
- 🏷️ [Auto Versioning](.github/AUTO_VERSIONING.md) - Tags e releases automáticas ⭐ NOVO
- 📦 [Release Guide](.github/RELEASE_GUIDE.md) - Como criar releases
- 📛 [Badges](.github/BADGES.md) - Badges para seu README

### 🔧 Tecnologias Suportadas

| Categoria | Tecnologias |
|-----------|-------------|
| **Frontend** | Node.js, React, Vue, Angular, Svelte, Next.js, Nuxt.js |
| **Backend** | Node.js, Python, .NET, Java, Go |
| **Gerenciadores** | npm, yarn, pnpm, pip, Maven, Gradle, NuGet, Go modules |
| **Containers** | Docker, Docker Compose |
| **Deploy** | Vercel, Netlify, GitHub Pages, Heroku, AWS, Azure |

### ⚡ Início Rápido

1. **Clone o repositório**
2. **Os workflows já estão configurados** em `.github/workflows/`
3. **Faça seu primeiro push**:
   ```bash
   git add .
   git commit -m "feat: initial commit"
   git push origin main
   ```
4. **Veja os workflows em ação** na aba Actions do GitHub

### 🎯 Fluxo Completo de Release Automática

Este repositório possui um fluxo completo de automação:

```
1. Desenvolver → 2. PR → 3. Merge para main → 4. Auto Tag → 5. Auto Release
```

**Exemplo prático:**
```bash
# 1. Criar branch e desenvolver
git checkout -b feature/nova-funcionalidade
git commit -m "feat: adiciona funcionalidade incrível"

# 2. Criar PR e fazer merge para main

# 3. Automação acontece:
#    ✅ Auto Tag detecta "feat:" e cria tag v1.1.0
#    ✅ CD detecta tag e cria release automaticamente
#    ✅ Changelog gerado com base nos commits
```

Para mais detalhes, consulte o [Auto Versioning Guide](.github/AUTO_VERSIONING.md).

---

## Instalação

Forneça instruções claras sobre como instalar o seu software.  
Inclua pré-requisitos, como dependências de software ou bibliotecas necessárias.  

Exemplo:

```bash
$ git clone https://github.com/seu-usuario/nome-do-projeto.git
$ cd nome-do-projeto
```

## Como Usar

Explique como usar o seu software em detalhes.
Forneça exemplos de código, comandos de linha ou capturas de tela para demonstrar o uso típico do software.

Exemplo:

```bash
# Exemplo de execução
dotnet run
```

Isso iniciará o servidor de desenvolvimento.

## Configuração

Se o seu software requer configuração adicional além da instalação padrão, explique aqui como configurá-lo.
Isso pode incluir variáveis de ambiente, arquivos de configuração ou qualquer ajuste necessário para personalizar o comportamento do software.

## Contribuições

Explique se você está aberto para contribuições e como outros desenvolvedores podem ajudar.
Inclua orientações para quem deseja reportar bugs, enviar solicitações de novos recursos ou fazer alterações no código.

## Artigos & Conteúdos

* 💼 [LinkedIn](https://www.linkedin.com/in/daniloopinheiro)
* ✍️ [Medium](https://medium.com/@daniloopinheiro)
* 💻 [Dev.to](https://dev.to/daniloopinheiro)
* 📰 [Substack](https://substack.com/@daniloopinheiro)

## Licença

MIT License © 2025 [LICENSE.md](https://github.com/daniloopinheiro/dopBase/blob/main/LICENSE.md) — por [Danilo O. Pinheiro](https://www.linkedin.com/in/daniloopinheiro/)

## Contato

### 💬 Suporte Técnico
Para questões técnicas, problemas ou sugestões:
- **Issues**: [GitHub Issues](https://github.com/daniloopinheiro/dopNetHL7/issues)
- **Discussions**: [GitHub Discussions](https://github.com/daniloopinheiro/dopNetHL7/discussions)

### 👨‍💻 Autor
**Danilo O. Pinheiro**  
Especialista em .NET, Clean Architecture e Interoperabilidade em Saúde

- **Email Pessoal**: [daniloopro@gmail.com](mailto:daniloopro@gmail.com)
- **Email Empresarial**: [devsfree@devsfree.com.br](mailto:devsfree@devsfree.com.br)
- **Consultoria**: [contato@dopme.io](mailto:contato@dopme.io)
- **LinkedIn**: [Danilo O. Pinheiro](https://www.linkedin.com/in/daniloopinheiro/)

### 🏢 Empresas
- **[DevsFree](https://devsfree.com.br)**: Desenvolvimento de Software
- **[dopme.io](https://dopme.io)**: Consultoria e Soluções Tecnológicas

<div align="center">

**⭐ Se este projeto foi útil, deixe uma estrela no GitHub! ⭐**

<p>
Feito com ❤️ por <strong>Danilo O. Pinheiro</strong><br/>  
<a href="https://devsfree.com.br" target="_blank">DevsFree</a> • <a href="https://dopme.io" target="_blank">dopme.io</a>  
</p>

</div>
