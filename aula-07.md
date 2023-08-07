# Aula 7: Exclusão Mútua e Eleição

## Exclusão Mútua (Acesso Exclusivo)

**Centralizado:** Um único servidor coordena o acesso a um recurso, evitando conflitos.

**Distribuído:** Vários processos cooperam para garantir que apenas um processo acesse um recurso por vez.

**Token:** Processo detentor de um token exclusivo pode acessar um recurso.

## Eleição (Escolha de um Líder)

**Anel:** Os processos formam um anel lógico, onde cada processo decide se tornar líder com base em critérios predefinidos.

**Bully:** Processos com IDs mais altos enviam mensagens para processos com IDs mais baixos, iniciando uma eleição se não recebem resposta.

Esses são os principais tópicos abordados na "Aula 7" sobre Exclusão Mútua e Eleição em Sistemas Distribuídos. Se você tiver alguma pergunta específica ou quiser mais detalhes sobre algum ponto, sinta-se à vontade para perguntar!