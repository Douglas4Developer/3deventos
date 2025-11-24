# 3DEventos – Projeto Aplicado (Arquitetura de Software)

Este repositório reúne os artefatos produzidos no Projeto Aplicado de Arquitetura de Software, tendo como caso a plataforma **3DEventos**, uma solução SaaS para gestão de eventos (espaços, convidados, fornecedores, orçamento, tarefas e convites).

O foco deste trabalho é a **arquitetura da solução**, contemplando visão de negócio, requisitos, modelagem (C4, ER) e especificação de endpoints REST.

---

## 1. Visão Geral da Solução

A 3DEventos é uma plataforma web que busca:

- Centralizar o cadastro de eventos, convidados e fornecedores;
- Padronizar orçamentos e checklists de tarefas;
- Apoiar a comunicação com clientes e convidados;
- Ser oferecida como **SaaS multi-tenant**, permitindo que diferentes espaços de eventos utilizem a mesma plataforma com isolamento lógico de dados.

A arquitetura proposta utiliza:

- **Backend:** Java + Quarkus
- **Frontend:** Angular
- **Banco de Dados:** PostgreSQL
- **Autenticação:** JWT
- **Multi-tenant:** isolamento lógico por `tenant_id` (espaço/cliente)

---
##  . Próximos Passos Técnicos

A partir desta base arquitetural, os próximos passos previstos são:

1. Implementação do **MVP** com Quarkus + Angular + PostgreSQL;
2. Validação com usuários reais (donos de espaços de eventos, cerimonialistas);
3. Evolução de segurança, observabilidade e operação (logs, métricas, monitoramento);
4. Integrações externas (meios de pagamento, canais de comunicação);
5. Refinamento contínuo da arquitetura e do DAS conforme a evolução do produto.

---

## 6. Autor

- **Douglas Soares de Souza Ferreira**  
  Especialização em Arquitetura de Software e Inteligência Artificial – XP Educação.