# AWS Cost Optimization for PharmaHub Distribuidora

## 📋 Descrição do Projeto

Este projeto apresenta uma proposta de otimização de custos em nuvem AWS para a **FarmaHub Distribuidora**, uma empresa fictícia do setor farmacêutico atuando como hub de distribuição para farmácias e revendedores.

O objetivo principal foi identificar e propor a implementação de três serviços AWS fundamentais para reduzir custos operacionais imediatos, aumentar a eficiência e fornecer maior controle e previsibilidade financeira, atendendo a uma solicitação do gestor financeiro.

## 🎯 Objetivos

*   **Redução de Custos:** Identificar oportunidades claras para diminuir a fatura AWS.
*   **Previsibilidade:** Implementar mecanismos de alerta e controle para evitar surpresas na fatura.
*   **Otimização Automatizada:** Utilizar serviços gerenciados pela AWS para reduzir a necessidade de intervenção manual e otimizar recursos automaticamente.
*   **Clareza para o Negócio:** Apresentar as soluções de forma que sejam entendíveis para um público não técnico, como o gestor financeiro.

## ⚙️ Serviços AWS Propostos

A estratégia foi dividida em três etapas focadas em serviços específicos:

| Etapa | Serviço AWS | Foco | Vantagem Principal |
| :--- | :--- | :--- | :--- |
| 1 | **Cost Explorer & Budgets** | Visibilidade e Controle | Dashboard de gastos e alertas personalizados para evitar custos excessivos. |
| 2 | **EC2 Auto Scaling & Savings Plans** | Otimização de Computação | Escalabilidade automática para picos de demanda e discounto por compromisso de uso para cargas de trabalho estáveis. |
| 3 | **S3 Intelligent-Tiering** | Otimização de Armazenamento | Armazenamento de custo otimizado que move dados entre camadas de acesso automaticamente sem overhead manual. |

## 📊 Detalhamento das Etapas

### Etapa 1: Cost Explorer & Budgets
O primeiro passo é ganhar visibilidade. O **AWS Cost Explorer** fornece gráficos e relatórios intuitivos para analisar os padrões de gasto. Combinado com o **AWS Budgets**, é possível criar alertas que notificam a equipe por e-mail ou SMS quando os custos excedem um limite definido, permitindo ação corretiva imediata.

### Etapa 2: EC2 Auto Scaling & Savings Plans
Para os servidores (instâncias EC2), propõe-se uma abordagem dupla:
*   **Auto Scaling:** Automaticamente adiciona ou remove capacidade de computação baseado na demanda real da aplicação, garantindo performance e pagando apenas pelo que se usa.
*   **Savings Plans:** Oferece um discounto significativo (até 72%) em troca de um compromisso de uso de 1 ou 3 anos, ideal para a base de servidores que precisa estar sempre ativa.

### Etapa 3: S3 Intelligent-Tiering
Para otimizar o custo de armazenamento de dados (como logs, backups e documentos), o **S3 Intelligent-Tiering** move automaticamente os objetos para camadas de acesso mais baratas quando não são acessados, sem penalidade de recuperação ou necessidade de gestão manual.