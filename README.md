# Sistema de Aluguel de Jogos de Tabuleiro
Este README.md detalha um projeto de simulação de um sistema de aluguel de jogos de tabuleiro, com foco na implementação da lógica de programação e algoritmos.

1. **Introdução**
Este projeto simula um sistema de aluguel de jogos de tabuleiro, onde o principal objetivo é implementar a funcionalidade de alugar e devolver jogos. A interface básica apresenta uma lista de jogos, cada um com um botão que permite "Alugar" ou "Devolver", dependendo do seu status. Além disso, a capa do jogo é visualmente alterada para indicar seu estado (disponível ou alugado).

2. **Estrutura do Projeto**
A estrutura do projeto assemelha-se a um sistema de loja de aluguel, onde o usuário interage diretamente com a lista de jogos para gerenciar seus empréstimos.

3. **Funcionalidades Implementadas**
As principais funcionalidades desenvolvidas neste projeto incluem:

*Aluguel de Jogos*: Ao clicar no botão "Alugar" de um jogo disponível, o status do jogo é alterado para "alugado". O texto do botão muda para "Devolver", e a capa do jogo é visualmente escurecida para indicar sua indisponibilidade.

*Devolução de Jogos*: Se um jogo estiver alugado, o botão exibirá "Devolver". Ao clicar neste botão, o jogo retorna ao status de "disponível", o texto do botão muda para "Alugar", e a capa do jogo retorna à sua aparência original.

*Visualização de Status*: Os usuários podem facilmente identificar quais jogos estão disponíveis para aluguel e quais estão atualmente alugados através da alteração visual das capas e do texto dos botões.

4. **Foco e Objetivos de Aprendizagem**
O foco principal deste projeto é a aplicação prática de conceitos fundamentais de lógica de programação e algoritmos. Durante o desenvolvimento, foram explorados e testados os seguintes conceitos:

#### Variáveis: Utilização de variáveis para armazenar o estado dos jogos (alugado/disponível).

#### Controle de Condicionais: Implementação de estruturas condicionais (ex: if/else) para determinar o comportamento dos botões e a alteração visual com base no status do jogo.

#### Loops (Laços de Repetição): Embora o escopo inicial possa não demandar laços complexos para esta simulação, a base foi estabelecida para futuras expansões que envolvam a iteração sobre listas de jogos.

#### Arrays (Vetores): Utilização de arrays para armazenar e gerenciar a lista de jogos e seus respectivos estados.

Este projeto serve como uma excelente oportunidade para consolidar os conhecimentos adquiridos na formação de iniciação em programação, construindo uma funcionalidade simples, mas completa.
