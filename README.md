Otávio Lana





  Cloud Solutions Architect · AWS · Azure · DevSecOps







  
  
  




---

## Sobre

Estudante de Segurança da Informação com foco em **arquitetura de soluções cloud**.
Projeto e implemento infraestruturas escaláveis, seguras e de alta disponibilidade
na AWS, com visão prática de multi-cloud (AWS + Azure).

Meu objetivo é atuar como **Arquiteto de Soluções** — conectando requisitos de
negócio a decisões técnicas de infraestrutura, segurança e custo.

---

## Certificações

| Certificação | Status | Validade |
|---|---|---|
| AWS Certified Cloud Practitioner | ✅ Obtida | — |
| Microsoft AZ-900 | 🔄 Em andamento | — |
| AWS Solutions Architect – Associate | 📌 Próxima meta | — |

---

## Arquitetura em destaque

### WordPress em Alta Disponibilidade (AWS)
> Infraestrutura multi-AZ com failover automático, escalabilidade horizontal e custo otimizado.

```
Internet → Route 53 → ALB (Multi-AZ)
                         ├── EC2 Auto Scaling Group
                         │       └── EFS (storage compartilhado)
                         └── RDS MySQL (Multi-AZ, standby automático)
                                   └── CloudWatch Alarms + SNS
```

**Decisões de arquitetura:**
- ALB para distribuição de carga e health checks automáticos
- EFS para garantir consistência de arquivos entre instâncias
- RDS Multi-AZ para RTO/RPO baixos
- Auto Scaling baseado em métricas de CPU e requisições

---

### Pipeline CI/CD com DevSecOps
> Automação de build, análise de segurança e deploy com shift-left security.

```
Push → GitHub Actions
          ├── Build & Test
          ├── SAST (análise estática)
          ├── Scan de imagem Docker
          └── Deploy containerizado
```

**Controles de segurança implementados:** análise estática no pipeline,
scan de vulnerabilidades em imagem antes do deploy, secrets via variáveis
de ambiente criptografadas.

---

### Servidor Linux com Observabilidade
> Monitoramento proativo com alertas em tempo real via webhook.

**Stack:** Linux · Nginx · Bash · Cron · Discord Webhook

Coleta de métricas (CPU, memória, disco), log centralizado e alertas
automáticos — sem dependência de ferramentas pagas.

---

## Tecnologias

**Cloud & Infra**
`AWS` `Azure (AZ-900)` `Docker` `Kubernetes` `Terraform`

**Segurança**
`IAM` `Security Groups` `DevSecOps` `SAST` `Hardening Linux`

**Observabilidade**
`CloudWatch` `Nginx` `Bash` `Cron` `Webhooks`

**Linguagens**
`Python` `Bash` `YAML`

---

## GitHub




![GitHub Stats](https://github-readme-stats.vercel.app/api?username=OtavioLxna&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true)




---

## Contato

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Otávio%20Lana-0077B5?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/otaviolana)
[![Email](https://img.shields.io/badge/Email-otaviolxna14%40gmail.com-D14836?style=flat-square&logo=gmail)](mailto:otaviolxna14@gmail.com)

---




  Construindo soluções que escalam · AWS · Azure · Open Source
