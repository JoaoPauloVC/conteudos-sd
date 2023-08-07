## Aula 1 (Introdução aos Sistemas Distribuídos):
        Definição de Sistemas Distribuídos
        Organização, Coerência, Middleware
        Objetivos
            Disponibilização de recursos compartilhados
            Transparência de distribuição
            Abertura
            Escalabilidade
                Tamanho, Geográfica, Administrativa
                Técnicas
                Problemas
        Modelos de sistema
            Síncrono
            Assíncrono
            Parcialmente Síncrono
        Armadilhas

## Aula 2 (Tipos de Sistemas Distribuídos):
        Sistemas para computação distribuída de alto desempenho
            Cluster
            Grade
            Nuvem
        Sistemas de informação distribuídos
            ACID
                Atomicidade
                Consistência
                Isolamento
                Durabilidade
        Sistemas distribuídos para computação pervasiva
            Ubíqua
            Móvel
            Sensores

## Aula 3 (Arquiteturas de Sistemas Distribuídos):
        Estilos arquiteturais
            Arquiteturas em camadas
            Arquiteturas baseadas em objetos
            Arquiteturas baseadas em eventos e dados
            Arquiteturas centradas em recursos
        Arquiteturas de software
            Arquiteturas centralizadas e multicamadas (multidivididas)
            Arquiteturas descentralizadas
            Arquiteturas híbridas
        Arquiteturas versus middleware
        Sistemas distribuídos autogerenciáveis
            Autoconfiguração
            Autogerenciamento
            Autocura
            Auto-otimização
            Auto-*

## Aula 4 (Processos, Threads e Migração):
        Introdução à processos e threads
        Threads em sistemas distribuídos
        Clientes
        Servidores
        Migração de código
            Abordagens para realização de migração de código
            Migração em sistemas heterogêneos

## Aula 5 (Comunicação):
        Fundamentos
            Camadas de baixo nível
            Camada de transporte
            Camada do middleware
            Camada de aplicação
            Tipos de comunicação   
        Comunicação orientada a procedimento (RPC)
            Funcionamento básico de RPCs [Nelson 1984]
            Passagem de parâmetros
            Tipos de comunicação
            Exemplo
        Comunicação orientada a mensagem (MOM)
            Middleware orientado a mensagens (filas)
            Message broker
            Exemplo: Apache Kafka
        Comunicação multicast (FIFO/Causal/Total – Gossip/Flooding)
            FIFO/Causal/Total e sem ordem.
            Gossip/Flooding
        Comunicação orientada a fluxo
            Suporte para mídia contínua
            Fluxo em sistemas distribuídos
            Qualidade de Serviço (QoS)

## Aula 6 (Nomes):
        Definições: nomes, identificadores e endereços
        Resolução de nomes (simples)
            Solução simples (broadcasting / flooding / ponteiros)
            Abordagens baseadas em um local pré-determinado (home-based)
            Tabelas de hash distribuídas (P2P estruturado)
                fingertables
            Serviço hierárquico de nomes
        Resolução de nomes (estruturado)
            DNS
        Resolução de nomes (atributo)

## Aula 7 (Exclusão Mútua e Eleição):
        Exclusão Mútua (acesso exclusivo)
            centralizado
            distribuído
            token
            descentralizado
        Eleição (escolha de um líder)
            Anel
            Bully

## Aula 7.? (Relógios Físicos, Lógicos e Vetoriais):
        Sincronização de relógios
            Relógios físicos
            Relógios lógicos (de Lamport)
                Multicast de Ordem Total
            Relógios vetoriais
                Multicast de Ordem Causal

## Aula 8 (Replicação e Consistência):
        Operações Conflitantes
        Introdução
        Consistência centrada nos dados
            Modelo do sistema
            Linearizable [Herlihy 1991]
            Sequencial [Lamport 1979]
            Causal [Hutto 1990]
            Read your Writes [Terry 1994]
            Eventual [Vogels 2009]
        Protocolos de consistência
            Protocolos primary-based (centrada nos dados: sequencial)
                Remote Write Backup
                Local Write
                Chain Replication
            Protocolos de replicação de escrita (centrada nos dados: sequencial)
                Quorum (leader-less) - Cassandra
        Gerenciamento de réplicas
            replicação de conteúdo e posicionamento
            distribuição de conteúdo

## Aula 9 (Falhas e Consenso):
            Contexto do Consenso
            Revisão e novos Conceitos
                Modelos de Sistemas (Revisão Cap 1)
                    Síncrono
                    Assícrono
                    Particalmente Síncrono
                Modelos Baseado em Falhas
                    Falha do Processo
                        Falha por Parada (Crash-Failure)
                        Omissão (Omission)
                        Recuperação (Recovery)
                        Violação (Eavesdropping)
                        Arbitrária (Byzantine)
                    Falha do Algoritmo
                        Fail-Stop
                        Fail-Noisy
                        Fail-Silent
                        Fail-Safe
                        Fail-Arbitrary
                Safety and Liveness
                IOnterfaces de um Componente
            Consenso
                Especificação
                Consenso no modelo assíncrono
                Consenso no modelo síncrono
                Consenso no modelo parcialmente-síncrono
            * Consenso em Transações Distribuídas
            * Teorema CAP
            * Comportamento Bizantino
            Conclusão