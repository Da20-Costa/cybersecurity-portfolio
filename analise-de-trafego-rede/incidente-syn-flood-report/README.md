# 🛡️ Incident Report: TCP SYN Flood Attack

🇺🇸 English

## 🎯 Objective
Analyze a network monitoring alert to identify and mitigate a Denial of Service (DoS) attack. This project involves inspecting TCP traffic logs to understand the 3-way handshake exploitation and implementing firewall rules to restore service.

## 📝 Scenario
An automated alert indicated a web server timeout. Packet analysis revealed a massive volume of TCP SYN requests from an unknown IP, intentionally leaving connections "half-open" to exhaust server resources.

## 🛠️ Skills & Tools
* **Traffic Analysis:** TCP 3-way handshake inspection.
* **Attack Identification:** SYN Flood / Denial of Service (DoS).
* **Mitigation:** IP Blocking and Firewall configuration.

----------------------------------------------------------------------------------------------------------

# 🛡️ Relatório de Incidente: Ataque TCP SYN Flood

🇧🇷 Versão em Português

## 🎯 Objetivo
Analisar um alerta de monitorização para identificar e mitigar um ataque de Negação de Serviço (DoS). Este projeto foca-se na inspeção de logs de tráfego TCP para compreender a exploração do "3-way handshake".

## 📝 Cenário
Um servidor web apresentou timeout devido a um volume anormal de pedidos SYN, mantendo conexões "meio-abertas" para esgotar os recursos da máquina.

## 🛠️ Competências
* **Análise de Tráfego:** Inspeção de fluxo TCP.
* **Identificação de Ataque:** SYN Flood / DoS.
* **Mitigação:** Bloqueio de IP e regras de Firewall.
