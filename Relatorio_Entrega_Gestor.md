## RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS
Data: 19 de Agosto de 2025
Nome da Empresa: Abstergo Industries
Responsável: Herivaldo Junior, Analista de Cloud AWS

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Herivaldo Junior. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos, aumentando a eficiência operacional e a escalabilidade dos sistemas que suportam o negócio de revenda e distribuição.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

**Etapa 1**:
•	Nome da ferramenta: AWS Cost Explorer & Budgets
•	Foco da ferramenta: Visibilidade e Controle Financeiro Total.
•	Descrição de caso de uso: Atualmente, a Abstergo Industries não tem uma visão clara e detalhada de para onde está indo cada real gasto na nuvem. O Cost Explorer é um painel intuitivo que permite visualizar e analisar os custos e o uso dos serviços AWS ao longo do tempo, identificando tendências e picos de gastos. Combinado com o AWS Budgets, podemos criar alertas automáticos que disparam um e-mail ou uma notificação para o setor financeiro quando os custos mensais, trimestrais ou mesmo de um serviço específico ultrapassarem um limite pré-definido. Isso elimina surpresas na fatura e permite ações corretivas imediatas.

**Etapa 2**:
•	Nome da ferramenta: Amazon EC2 Auto Scaling e AWS Savings Plans
•	Foco da ferramenta: Otimização de Custos de Computação (Servidores).
•	Descrição de caso de uso: Nossos servidores que hospedam o sistema de pedidos, o portal de revendedores e APIs provavelmente têm picos de uso (ex.: início do mês, campanhas promocionais) e períodos de baixa atividade (ex.: madrugada, finais de semana). Manter servidores fixos e superdimensionados para atender aos picos é caro e ineficiente. O EC2 Auto Scaling automatiza a criação e a terminação de servidores conforme a demanda real, garantindo performance nos picos e pagando apenas pelo necessário nos vales. Além disso, para a base de servidores que precisa ficar sempre ligada, o Savings Plans oferece um desconto significativo (até 72% comparado ao preço sob demanda) em troca de um compromisso de uso por 1 ou 3 anos. É como comprar uma "assinatura" de capacidade, tornando os custos previsíveis e muito mais baixos.

**Etapa 3**:
•	Nome da ferramenta: Amazon S3 Intelligent-Tiering
•	Foco da ferramenta: Otimização de Custos de Armazenamento de Dados.
•	Descrição de caso de uso: A Abstergo Industries armazena grandes volumes de dados, como relatórios financeiros históricos, logs de transações, imagens de produtos e backups de bancos de dados. Muitos desses dados são acessados com frequência apenas nos primeiros 30-90 dias e depois raramente são consultados. Armazenar tudo no mesmo tipo de storage é como pagar o preço de um cofre blindado para guardar um documento de 10 anos atrás que você quase nunca precisa. O S3 Intelligent-Tiering é um tipo de armazenamento inteligente que monitora automaticamente os padrões de acesso aos objetos. Ele move os dados frequentemente acessados para uma camada de custo mais alto e os dados não acessados por longos períodos para uma camada de custo muito mais baixo, tudo de forma automática e sem impacto na disponibilidade. O principal ganho é que pagamos o preço justo pelo nível de acesso de cada dado, sem necessidade de gestão manual complexa.

## Conclusão
A implementação dessas ferramentas na empresa Abstergo Industries tem como esperado uma redução imediata e contínua dos custos operacionais com TI, um aumento drástico na previsibilidade dos gastos (evitando surpresas desagradáveis na fatura) e a otimização automática de recursos, liberando a equipe de TI para focar em projetos estratégicos ao invés de gerenciamento manual de custos e servidores. Recomenda-se fortemente a aprovação da implementação em fases desses serviços, iniciando pelo Cost Explorer para obter visibilidade, seguido pelas ações de otimização. A AWS oferece um conjunto vasto de ferramentas, e esta é a base sólida para uma jornada de crescimento com custos sob controle.

Assinatura do responsável pelo projeto:
Herivaldo Junior
Analista de Cloud AWS

