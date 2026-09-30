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
```

---

## 📊 Dashboard de Monitoramento

O dashboard foi desenvolvido no **Grafana**, utilizando as métricas coletadas pelo **Zabbix Agent 2** e centralizadas no **Zabbix Server**.

Foram implementadas visualizações para:

- Status do servidor;
- Uptime do sistema;
- Utilização de CPU;
- Utilização de memória;
- Espaço utilizado em disco;
- Tráfego de rede (Inbound e Outbound).

### Grafana

<img width="1897" height="913" alt="dashboard-grafana-windows-server" src="https://github.com/user-attachments/assets/8084414d-8a38-4a83-b064-f790875539bd" />


### Zabbix

<img width="1903" height="909" alt="zabbix" src="https://github.com/user-attachments/assets/8e3f2171-3794-4d05-b521-c3d4e7c6e4ef" />

