# Capa

**Título do Projeto:** Gestão Financeira Inteligente com Open Finance  
**Nome do Estudante:** Thiago Cirne Arndt  
**Curso:** Engenharia de Software  
**Data de Entrega:** ??? 

---

# Resumo

Este documento apresenta o projeto "Gestão Financeira Inteligente com Open Finance", uma ferramenta de software para auxiliar usuários no controle de suas finanças pessoais. O sistema permite vincular contas bancárias via Open Finance, extrair relatórios de extratos, categorizar despesas manualmente ou com auxílio de IA, gerar gráficos interativos e gerenciar acesso familiar com papéis de administrador e visualizador. O objetivo é oferecer uma solução prática e visual para gestão financeira, promovendo decisões mais informadas e colaborativas em núcleos familiares.

---

# 1. Introdução

## Contexto

- Com o avanço do Open Finance no Brasil, os dados financeiros estão mais acessíveis, mas ainda falta uma ferramenta simples e integrada que ajude as pessoas a organizar suas despesas e entender seus hábitos de consumo.
- Muitos enfrentam dificuldades pra controlar gastos ou compartilhar informações financeiras com a família de forma segura.

## Justificativa

- O projeto é relevante pra Engenharia de Software por explorar integração com APIs modernas (Open Finance), aplicar IA em categorização de dados e implementar controle de acesso.
- Ele atende a uma necessidade real de gestão financeira pessoal e familiar, com potencial de impacto social e econômico.

## Objetivos

- **Principal:** Desenvolver um software que integre contas bancárias via Open Finance, categorize despesas e gere relatórios visuais.
- **Secundários:**
  - Implementar um sistema de controle de acesso baseado em papéis (RBAC).
  - Adicionar suporte a múltiplos usuários (familiares).
  - Integrar IA para sugestão de categorias.

---

# 2. Descrição do Projeto

## Tema do Projeto

- Uma aplicação web para gestão financeira que usa Open Finance pra conectar contas bancárias (ex.: Nubank, Banco Inter), extrai extratos, permite categorizar despesas (mercado, gasolina, restaurante) e gera gráficos interativos.
- Inclui um sistema de papéis (admin e visualizador) pra gerenciar acesso familiar e uma IA pra sugerir categorias automaticamente.

## Problemas a Resolver

- Dificuldade em organizar e visualizar despesas de múltiplas contas bancárias.
- Falta de controle colaborativo em finanças familiares com segurança.
- Categorização manual demorada e propensa a erros.

## Limitações

- Não cobre investimentos ou planejamento financeiro complexo (ex.: aposentadoria).
- Depende de bancos suportados pelo Open Finance ou conectores diretos do Pluggy.
- A IA será limitada a sugestões baseadas em títulos de transações, sem análise profunda de comportamento.

---

# 3. Especificação Técnica

## 3.1. Requisitos de Software

### Lista de Requisitos

**Funcionais (RF):**

- RF01: O sistema deve permitir vincular contas bancárias via Open Finance.
- RF02: O usuário deve categorizar despesas manualmente (ex.: mercado, gasolina).
- RF03: O sistema deve gerar gráficos de despesas por categoria, período ou conta.
- RF04: O administrador deve adicionar/remover usuários (familiares) e definir papéis.
- RF05: A IA deve sugerir categorias com base em títulos de transações.
- RF06: O sistema deve listar extratos detalhados por conta.

**Não-Funcionais (RNF):**

- RNF01: A interface deve carregar gráficos em até 2 segundos com até 1000 transações.
- RNF02: O sistema deve garantir autenticação segura com OAuth 2.0 e criptografia AES-256.
- RNF03: A aplicação deve ser responsiva (desktop e mobile).

### Diagrama de Casos de Uso (UML)

**Atores:** Usuário Administrador, Usuário

**Casos de Uso:**

![image](https://github.com/user-attachments/assets/e6b14f69-6ed2-45fe-8f0b-8c214a2a34b5)


## 3.2 Fluxograma de Atividade
![image](https://github.com/user-attachments/assets/d48a5703-5a15-4801-acde-bbefb0c9aca8)


## 3.3. Considerações de Design

**Escolhas de Design:**

- **Frontend:** NextJS (SSR para SEO e performance).
- **Backend:** Spring Boot (APIs REST robustas).
- **Banco de Dados:** PostgreSQL.
- **Alternativa Descartada:** Flask (menos escalável).

### Visão Inicial da Arquitetura

- **Frontend:** NextJS
- **Backend:** Spring Boot
- **Banco:** PostgreSQL
- **Integração:** Pluggy Connect SDK

## 3.4. Stack Tecnológica

**Linguagens de Programação:** JavaScript/TypeScript e Java

**Frameworks e Bibliotecas:**

- NextJS, Spring Boot, Pluggy SDK, Chart.js, Axios

**Ferramentas:** Jira, GitHub, Confluence, Docker, AWS

**Banco de Dados:** PostgreSQL

## 3.5. Considerações de Segurança

- **Autenticação:** OAuth 2.0 com JWT
- **Criptografia:** AES-256
- **Mitigação:** Proteção contra SQL Injection, XSS/CSRF

---

# 4. Próximos Passos

- **Portfólio I:** Prototipagem da interface e backend básico (Maio-Julho 2025).
- **Portfólio II:** Implementação da IA e deploy na AWS (Julho-Novembro 2025).

**Cronograma:**

- Maio: Requisitos e design.
- Junho: Frontend e backend básico.
- Julho: IA e testes.
- Agosto: Deploy e ajustes finais.

---

# 5. Referências

- [Pluggy API Documentation](https://docs.pluggy.ai/)
- [NextJS Documentation](https://nextjs.org/docs)
- [Spring Boot Documentation](https://spring.io/projects/spring-boot)
- [Chart.js](https://www.chartjs.org/)
- [GitHub Actions Documentation](https://docs.github.com/en/actions)
- [AWS Documentation](https://aws.amazon.com/documentation/)
- [Open Finance Brasil](https://openfinancebrasil.org.br/)

---

# 7. Avaliações de Professores

- **Considerações Professor/a:** ___________________________
- **Considerações Professor/a:** ___________________________
- **Considerações Professor/a:** ___________________________

