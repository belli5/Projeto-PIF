# Projeto-PIF
Projeto da matéria de Programação Imperativa Funcional, do segundo período de Ciência da Computação na Cesar School. 

PASSOS PARA JOGAR O CHICK RUNNING

- CODIGO DE INICIO
  
1. O usuario precisa digitar essa linha de codigo no terminal shell:
   
gcc –o chickrunning main.c keyboard.c screen.c timer.c

2. Logo em seguida digitar essa segunda linha
   
./chickrunning

- INICIANDO O JOGO
  
1. O chick running irá abrir e sera iniciado automaticamente com a cerca indo em direção ao chick.
   
2. E a função do usuario eh desviar desta cerca dando pulos precionando a tecla "ESPAÇO".

3. Enquando o usuario pular a cerca e ela tocar na parede do lado esquerdo do jogo o jogador ganhará um ponto somado no "SCORE".
- A cada vez que a cerca tocar na parede do lado esquerdo a pontuação aumentara 1 ponto no "SCORE" e a cerca retornara para o inicio do do looping.

4. Quando esta cerca esbarrar de alguma maneira com o chick o jogo vai parar imediatamente e vai mostrar na tela um "GAME OUVER".
- Dando a entender que o jogador perdeu.

5. Se o jogador quiser recomeçar e jogar novamente é necessario que ele aperte a tecla "R" e o jogo recomeçará zerando os "SCORES" e salvando este score no HighScore.
- o HighScore salva e mostra as melhores pontuações em sequencia da maior para a menor, para ver elas é necessario digitar a telha "ENTER" ao final da rodada.

6. Para encerrar o chick running é necessario digitar a tecla "ENTER" no "GAME OUVER" e ele ira sair do jogo mostrando o HighScore 
