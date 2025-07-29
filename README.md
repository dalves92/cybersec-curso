# 🧪 Laboratório de Segmentação de Rede – Documentação Técnica

Este repositório contém a documentação técnica de um **laboratório de segmentação de rede**, com foco em **análise de exposição, mapeamento de serviços** e **avaliação de riscos** em um ambiente de rede **simulado com múltiplos segmentos**.

---

## 📄 Sobre o Projeto

O laboratório foi desenvolvido para fins acadêmicos e de capacitação técnica, utilizando ferramentas de análise e segurança de rede para avaliar a infraestrutura de um ambiente **Docker simulado** com as seguintes sub-redes:

- `corp_net`
- `infra_net`
- `guest_net`

---

## 📌 Objetivos

- 🔍 Identificar hosts e serviços ativos  
- 🛡️ Mapear vulnerabilidades e riscos operacionais  
- 🧩 Propor recomendações de segurança e plano de ação  
- 📑 Documentar achados técnicos com evidências de varredura  

---

## 🛠️ Ferramentas Utilizadas

- [Nmap](https://nmap.org/)
- [Rustscan](https://rustscan.github.io/)
- [Netdiscover](https://tools.kali.org/information-gathering/netdiscover)
- Ping
- Docker (para simulação de rede)
- Cisco Packet Tracer (para diagrama de rede)
- Word/Excel (documentação técnica e apêndice)

---

## 📊 Conteúdo do Repositório

| Arquivo                                           | Descrição                                                         |
|---------------------------------------------------|-------------------------------------------------------------------|
| `Relatorio_Tecnico_Lab_Segmentacao_Rede.docx`     | Documento técnico com achados, recomendações e plano de ação      |
| `Capa_Relatorio_Tecnico_Segmentacao_Rede.docx`    | Capa personalizada com imagem de cibersegurança                   |
| `Anexo_Evidencias_Siglas_Segmentacao_Rede.xlsx`   | Planilha com evidências, siglas, abreviações e jargões            |
| `diagrama_rede_segmentada.png`                    | Diagrama da arquitetura de rede com segmentação                   |
| `Dockerfile`                                      | Resultado da simulação da rede (ambiente Docker configurado)      |
| `resultados_ping_varredura.txt`                   | Saída da varredura de rede e testes de conectividade com ping     |
---

## ✅ Diagnóstico Realizado

Foram identificados serviços como **FTP, MySQL, LDAP, SMB** e **interfaces web abertas** em múltiplos hosts.  
A análise resultou em um **plano de ação baseado no princípio de Pareto (80/20)**, priorizando medidas de **alto impacto e fácil implementação**.

---

## 🧩 Anexo

O repositório inclui um anexo em formato `.xlsx` com:

- Siglas
- Abreviações
- Termos técnicos
- imagem com evidências

---

## 👤 Autor

**Gonçalo Quissola Mateus Dala**  
Pós-graduando em Segurança da Informação – UNIP