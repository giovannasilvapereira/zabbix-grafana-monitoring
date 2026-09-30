# 📊 Monitoramento de Windows Server com Zabbix + Grafana

Projeto prático de monitoramento de infraestrutura desenvolvido em laboratório, utilizando **Zabbix Server, Zabbix Agent 2 e Grafana**.

O objetivo foi implementar uma solução capaz de coletar métricas de um **Windows Server**, centralizá-las no Zabbix e transformá-las em um dashboard visual no Grafana.

> **Status:** Projeto concluído e funcional.

---

## 🎯 Objetivo

Construir um ambiente de monitoramento para praticar:

- Instalação e configuração do Zabbix Server;
- Monitoramento de Windows Server com Zabbix Agent 2;
- Coleta de métricas de infraestrutura;
- Integração entre Zabbix e Grafana;
- Construção de dashboards;
- Troubleshooting de comunicação e autenticação;
- Monitoramento de disponibilidade e desempenho.

---

## 🏗️ Arquitetura

O fluxo de monitoramento implementado foi:

```text
Windows Server
     │
     │ Zabbix Agent 2
     ▼
Zabbix Server
     │
     │ Zabbix API
     ▼
   Grafana
     │
     ▼
Dashboard de Monitoramento
