# Aula 1: Introdução aos Sistemas Distribuídos

## Definição de Sistemas Distribuídos

Um sistema distribuído é um conjunto de computadores interconectados que colaboram entre si para realizar tarefas. Esses sistemas compartilham recursos e informações, permitindo que os usuários acessem serviços de maneira transparente.

## Organização, Coerência, Middleware

**Organização:** Refere-se à estrutura e ao layout dos componentes do sistema distribuído, como como os recursos são alocados e como os processos se comunicam.
    Overlay:
        Estruturado
        Nao Estruturado

**Coerência:** Envolve a garantia de que as informações compartilhadas entre os diversos componentes de um sistema distribuído estejam atualizadas e corretas.

**Middleware:** É uma camada intermediária que fornece serviços de comunicação e coordenação entre os diferentes componentes distribuídos. Isso ajuda a ocultar a complexidade da rede subjacente.

## Objetivos

**Disponibilização de recursos compartilhados:** Permitir que os recursos, como arquivos, impressoras ou bancos de dados, sejam acessados por vários usuários ou aplicativos.

**Transparência de distribuição:** Os usuários e aplicativos não precisam saber onde ou como os recursos estão sendo acessados, tornando a distribuição transparente.

**Abertura:** Possibilidade de adicionar novos recursos e componentes ao sistema sem afetar sua operação.

**Escalabilidade:** Capacidade de aumentar o tamanho do sistema, geograficamente ou administrativamente, para atender às demandas crescentes.

**Técnicas e Problemas de Escalabilidade:** Diversas técnicas podem ser aplicadas para alcançar escalabilidade, mas também podem surgir desafios como consistência e latência.

## Modelos de Sistema

**Síncrono:** Os componentes do sistema têm uma noção compartilhada de tempo, facilitando a coordenação, mas tornando o sistema mais sensível a falhas.

**Assíncrono:** Não há uma noção compartilhada de tempo, o que torna a coordenação mais complexa, mas torna o sistema mais tolerante a falhas.

**Parcialmente Síncrono:** Combina elementos de ambos os modelos anteriores, permitindo coordenação quando necessário e tolerância a falhas quando apropriado.

## Armadilhas
Ao projetar e desenvolver sistemas distribuídos, é importante considerar várias armadilhas, como a complexidade da comunicação, falhas de rede, consistência de dados e segurança.

Esses são os principais pontos abordados na Aula 1 sobre Introdução aos Sistemas Distribuídos. Se você tiver alguma dúvida específica ou quiser explorar mais algum tópico em detalhes, sinta-se à vontade para perguntar!