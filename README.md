# RPGDETEXTO_PDS2
Repositório do trabalho da disciplina PDS2, que consiste em um RPG de texto em c++.
Os requisitos são: - Possuir classes com diferentes armas e atributos, utilizando polimorfismo.
- Efetuar batalhas com inimigos dentro do jogo.
- Escolher itens dentro de seu inventário.
- Interface de opções via terminal.
- 2 armas diferentes para cada personagem.

Objetivo da modularização:
- Criar uma classe mãe chamada personagem, e 6 classes filhas: guerreiro, mago, arqueiro, vilao 1, vilao 2 e o boss.
- As classes filhas terão habilidades de ataque e defesa, e possuiram uma vida determinada previamente com base na classe.
- O dano, defesa e ataque são definidos com base na rolagem de dados, prevista na classe DADO.
