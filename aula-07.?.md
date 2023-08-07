# Aula 7.? (Relógios Físicos, Lógicos e Vetoriais)

## Sincronização de Relógios

**Relógios Físicos:** Baseados em hardware, mas podem estar sujeitos a variações.

**Relógios Lógicos (de Lamport):** Ordena eventos com base em carimbos lógicos, mas não reflete necessariamente a ordem real dos eventos.

**Relógios Vetoriais:** Utilizam vetores de carimbos para fornecer uma visão mais precisa da ordem dos eventos.

## Multicast de Ordem Total

**Relógios Lógicos (de Lamport):** Utilizados para ordenar as mensagens em relação a outras mensagens.

**Relógios Vetoriais:** Ordenam as mensagens de acordo com o vetor de carimbos de cada processo.

## Multicast de Ordem Causal

**Relógios Vetoriais:** Usados para garantir que os processos recebam as mensagens de forma causal, respeitando a ordem de dependência entre os eventos.