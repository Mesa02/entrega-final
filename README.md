# Entrega-parcial
 Arquitetura Inicial (com Monitoramento|Observabilidade) + Custos Iniciais (Somente AWS)

       Arquitetura inicial
┌─────────────────────────────────┐ 
│               AWS               │ 
│  us-east-1                      │ 
│                                 │ 
│  EC2 ─── Frontend (HTML/JS/CSS) │ 
│                                 │ 
│  EC2 ─── Prometheus | Grafana   │
│                                 │
│  EC2 Backend (Node.js) ─── ALB  │
│               │                 │
│  VPC: 10.0.0.0/16               │ 
└─────────────────────────────────┘

Bando de Dados:
┌─────────────────────────────────┐ 
│                                 │ 
│     -User: techstock_user       │
│     -Senha: Senai134            │
│                                 │ 
└─────────────────────────────────┘

