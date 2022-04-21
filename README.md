**| Exercicio 4 - Euromilhões |**


**Este exercicio serve os seguintes objetivos:**

- Utilização de Vetores,
- Consolidação dos Ciclos e Decisores,
- Utilização de Variáveis,
- Realização de algoritmo,
- Utilização de novas bibliotecas,

**| Descrição do Problema |**

Faça um programa que apresente um menu e fique à espera que o utilizador escolha uma das opções.
Uma vez escolhida uma das opções apresentadas o programa deverá executá-la.
Após o término dessa operação o programa deverá voltar ao menu principal.
Caso o utilizador insira uma opção inválida o programa deverá mostrar a seguinte mensagem : *Opcao Invalida*

**Nota :** O programa deverá estar em loop e deverá sair do mesmo apenas quando o utilizador inserir a opção *<opcMenu> = 3 || <opcMenuFinal> = 2*.

O programa deverá apresentar o seguinte menu:
    <pre>    
    //puts("+-- Euromilhoes ---------------+");
    //puts("|  1  -  Chave Manual          |");
    //puts("|  2  -  Chave Automatica      |");
    //puts("+-- Outros --------------------+"); 
    //puts("|  3  -  Sair do Programa      |");
    //puts("+------------------------------+");
    </pre>
- Opção *1* , o utilizador deverá introduzir os numeros com os valores que acha que são o euromilhões, de seguida após armazenar deverá mostrar uma mensagem ao utilizador 
  para saber que o seu número foi inserido com sucesso. *Numeros:<num[]>\n Estrelas:<est[]>\n Você introduziu a sua chave com sucesso* De seguinda o programa deverá verificar se o jogador ganhou algum prémio:
  Caso o utilizador ganhe deverá mostrar a seguinte mensagem *Acertaste <x> numeros e <x> estrelas*, caso não ganhe nada deverá mostrar a seguinte mensagem: *Tiveste azar! Nao ganhaste nada...*

<pre>
Exemplo
+-- Euromilhoes ---------------+
|  1  -  Chave Manual          |
|  2  -  Chave Automatica      |
+-- Outros --------------------+
|  3  -  Sair do Programa      |
+------------------------------+
1
Digite o 1 ┬║ numero
15
Digite o 2 ┬║ numero
7
Digite o 3 ┬║ numero
45
Digite o 4 ┬║ numero
29
Digite o 5 ┬║ numero
34
Digite a 1 ┬║ estrela
3
Digite a 2 ┬║ estrela
11
Numeros: 7 15 29 34 45
Estrelas: 3 11
Voce introduziu a sua chave com sucesso

Acertaste 1 numeros e 2 estrelas
Parabens, ganhaste 7.44 euros

+-- Deseja apostar novamente? -+
|  1  -  Sim                   |
|  2  -  Nao                   |
+------------------------------+
</pre>


- Opção *2*, o programa deverá gerar uma chave automática para o utilizador e de seguida verificar se o mesmo ganhou algum prémio:
  Caso o utilizador ganhe deverá mostrar a seguinte mensagem *Acertaste <x> numeros e <x> estrelas*, caso não ganhe nada deverá mostrar a seguinte mensagem: *Tiveste azar! Nao ganhaste nada...*

<pre>
Exemplo

+-- Euromilhoes ---------------+
|  1  -  Chave Manual          |
|  2  -  Chave Automatica      |
+-- Outros --------------------+
|  3  -  Sair do Programa      |
+------------------------------+
2
Numeros: 3 23 23 41 48
Estrelas: 1 10

Chave sorteada com sucesso
Acertaste 0 numeros e 0 estrelas
Tiveste azar! Nao ganhaste nada...

+-- Deseja apostar novamente? -+
|  1  -  Sim                   |
|  2  -  Nao                   |
+------------------------------+
</pre>

- Opção *3* deverá sair do loop e terminar o programa.

- No final da opção 1 e 2 o programa deverá apresentar o seguinte menu:
    <pre>
    //puts("+-- Deseja apostar novamente? -+");
    //puts("|  1  -  Sim                   |");
    //puts("|  2  -  Nao                   |");
    //puts("+------------------------------+");
    </pre>
- Opção *1*, deverá voltar para o inicio do programa.

- Opção *2*, deverá sair do loop e terminar o programa.


**Notas adicionais**

- Quando inicia o programa o mesmo deverá de gerar a chave antes de apresentar o menu.
- Deverá recorrer ao uso de novas bibliotecas.

