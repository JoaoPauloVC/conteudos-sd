# Aula 8: Replicação e Consistência

## Introdução

## Operações Conflitantes
    Operações em diferentes partes do sistema podem afetar ou depender umas das outras.

## Modelos de Consistência:
    Linearizável (Herlihy, 1991)
    Sequencial (Lamport, 1979)
    Causal (Hutto, 1990)
    Read Your Writes (Terry, 1994)
    Eventual (Vogels, 2009)
# Protocolos de Consistência
    Protocolos primary-based (centrada nos dados: sequencial), incluindo:
    Remote Write Backup
    Local Write
    Chain Replication
## Protocolos de replicação de escrita (centrada nos dados: sequencial), como:
    Quorum (leader-less) - Cassandra
## Gerenciamento de Réplicas
    Replicação de Conteúdo e Posicionamento
    Distribuição de Conteúdo