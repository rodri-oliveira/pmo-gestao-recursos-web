# Gestão de Projetos e Recursos — Interface PMO

Aplicação web com **Next.js e React** para consultar projetos, acompanhar alocações e visualizar indicadores operacionais de equipes e recursos.

## Problema e solução

Acompanhar a capacidade de equipes e comparar o trabalho planejado com o realizado exige visualizações claras, filtros e uma interface para manutenção dos cadastros. Esta aplicação reúne essas operações em dashboards e telas administrativas.

## Funcionalidades presentes no repositório

- **Visão do gestor:** indicadores de capacidade e alocação.
- **Indicadores de departamento:** dashboards e consultas por agrupamentos.
- **Gerenciamento:** seções, equipes, recursos, projetos e alocações.
- **Relatórios:** horas apontadas e comparação **planejado × realizado**.
- **Administração:** usuários, configurações, logs e integração com sistema externo.
- Fluxo de login e componentes de gerenciamento de sessão.

## Tecnologias

**Next.js 14 · React 18 · Material UI · ECharts · Axios · NextAuth**

As páginas ficam em `app/`, os componentes em `components/` e as chamadas à API em `services/`.

**API associada:** [PMO — Backend](https://github.com/rodri-oliveira/pmo-gestao-recursos-api).

## Execução local

```bash
npm install
npm run dev
```

Em desenvolvimento, o frontend costuma ser servido em `http://localhost:3000`.

**Pré-requisitos para demonstração:** API PMO, base de dados de exemplo e provedor de autenticação configurados. Sem esses componentes, o servidor de desenvolvimento pode iniciar, mas as operações integradas não estarão disponíveis.

## Competências demonstradas

Interfaces administrativas, componentes reutilizáveis, visualização de dados e integração frontend/backend.

**Status:** interface documentada; demonstração integral depende dos serviços de apoio.
