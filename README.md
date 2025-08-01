# Logística 4.0: Otimização Proativa de Entregas com Inteligência Climática

## Visão Geral do Projeto

Este portfólio demonstra a construção de uma solução de automação ponta a ponta que atua como um "Centro de Inteligência Climática para Logística". O sistema monitora proativamente as condições climáticas, identifica riscos para as rotas de entrega e utiliza Inteligência Artificial Generativa para fornecer alertas contextualizados e sugestões estratégicas para as equipes de logística, visando minimizar atrasos, reduzir custos e aumentar a segurança operacional.

---

### 🎯 O Problema

Empresas de logística e transporte enfrentam perdas financeiras e de reputação significativas devido a eventos climáticos adversos e imprevisíveis. A tomada de decisão reativa resulta em:
- **Atrasos** significativos nas entregas.
- **Aumento de custos** operacionais (combustível, horas extras).
- **Riscos** à segurança dos entregadores e da carga.
- **Insatisfação** e perda de confiança dos clientes.

---

### 💡 A Solução Proposta

Este projeto implementa um fluxo automatizado que:
1.  **Coleta dados** de previsão do tempo em tempo real via API.
2.  **Armazena** um histórico climático em um banco de dados robusto.
3.  **Detecta** automaticamente padrões climáticos que representam ameaças.
4.  **Utiliza um LLM (Gemini)** para analisar o risco e gerar recomendações inteligentes.
5.  **Notifica** as equipes responsáveis com alertas claros e acionáveis.

---

### 🛠️ Tecnologias Utilizadas

| Ferramenta | Função |
|---|---|
| **n8n** | 🧠 Orquestração e automação do workflow |
| **OpenWeatherMap** | 🌦️ Fornecimento de dados climáticos via API |
| **Supabase** | 🗄️ Banco de Dados (PostgreSQL) para armazenamento |
| **Gemini (Google AI)** | 🤖 Geração de insights e recomendações com IA |
| **GitHub** | 📂 Versionamento de código e documentação |

---

*Este repositório contém o schema do banco de dados (`schema.sql`) e a configuração do workflow (`workflow.json`) utilizados no projeto.*