# Aula 5: Comunicação

## Fundamentos

**Camadas de Baixo Nível:** Lidam com a transferência bruta de bits pela rede.

**Camada de Transporte:** Responsável por estabelecer conexões confiáveis e gerenciar fluxo de dados.

**Camada do Middleware:** Fornece abstrações para comunicação entre componentes distribuídos.

**Camada de Aplicação:** Lida com a lógica específica do aplicativo.

## Tipos de Comunicação

**Comunicação Orientada a Procedimento (RPC):** Permite que um programa chame uma função ou procedimento em um processo remoto como se fosse local.

**Comunicação Orientada a Mensagem (MOM):** Baseada em trocas de mensagens assíncronas entre processos.

**Comunicação Multicast (FIFO/Causal/Total – Gossip/Flooding):** Envia uma mensagem para um grupo de processos.
Comunicação Orientada a Procedimento (RPC)

**Funcionamento Básico de RPCs:** Cliente invoca uma função remota, que é executada em um servidor remoto, e o resultado é retornado ao cliente.

**Passagem de Parâmetros:** Os parâmetros da função são empacotados e transmitidos entre os processos.

**Exemplo:** Chamada de função remota para somar dois números.

## Comunicação Orientada a Mensagem (MOM)

**Middleware Orientado a Mensagens (Filas):** As mensagens são armazenadas em filas intermediárias, permitindo que os processos se comuniquem de forma assíncrona.

**Message Broker:** Componente intermediário que gerencia o roteamento e entrega de mensagens.

**Exemplo: Apache Kafka:** Plataforma de streaming de dados para processamento em tempo real.
Comunicação Multicast (FIFO/Causal/Total – Gossip/Flooding)

**FIFO/Causal/Total e Sem Ordem:** Tipos de garantia de entrega de mensagens em comunicação multicast.

**Gossip/Flooding:** Método de disseminação de informações em uma rede, onde cada nó repassa informações para outros nós.
Comunicação Orientada a Fluxo

**Suporte para Mídia Contínua:** Comunicação que lida com fluxos contínuos de dados, como streaming de áudio ou vídeo.

**Fluxo em Sistemas Distribuídos:** Transmissão contínua de dados entre processos em uma rede.

**Qualidade de Serviço (QoS):** Garantia de níveis de desempenho e prioridades na comunicação de fluxos.

Esses são os principais pontos abordados na Aula 5 sobre Comunicação em Sistemas Distribuídos. Se tiver alguma dúvida ou quiser aprofundar algum conceito específico, estou à disposição para ajudar!