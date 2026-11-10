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

**Limitações:** dashboards, login e relatórios dependem de uma API, dados e autenticação configurados. O funcionamento completo fora da implantação original **não foi testado** nesta revisão. Não utilize configurações ou credenciais de serviços de terceiros.

## Competências demonstradas

Interfaces administrativas, componentes reutilizáveis, visualização de dados e integração frontend/backend.

**Status:** aplicação histórica de portfólio; dependências externas a substituir para demonstração independente.
