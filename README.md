# Publicação da iniciação cientifica: PROJETO E ANÁLISE SINTÁTICA DE LINGUAGEM DE PROGRAMAÇÃO EDUCACIONAL

O objetivo principal desta pesquisa foi estabelecer uma linguagem de programação que seja próxima de uma alta abstração, mas que não seja as linguagens tradicionais para ensinar lógica de programação. Em muitos casos, o aluno ainda não teve contato com a programação, e é importante aprender a lógica. É necessário que o resultado do execicio lógico seja expressado em um código, e muitas vezes a linguagem escolhida, é a linguagem C por exemplo, o que é ótimo, porém em muitos casos foi constatado que o aluno encontra grande dificuldade, pois primeiro é necessário entender a linguagem para depois exercitar a lógica. Foi pensando em treinar diretamente a lógica em primeiro plano que surgiu então o objetivo desta iniciação.

Arquivo do projeto de iniciação cientifica publicada no X Conict em Sorocaba em 2019. **Link da publicação:** http://ocs.ifsp.edu.br/index.php/conict/xconict/paper/view/5788

**RESUMO:** Este projeto tem como propósito projetar e implementar o analisador sintático de uma
linguagem de programação educacional aplicando os conceitos de gramáticas regulares,
livres-de-contexto, análise léxica e sintática. Tem-se como propósito fundamentar o desenvolvimento
de uma linguagem de fácil compreensão lógica, com o intuito de auxiliar no ensino da lógica de
programação para indivíduos que ainda não possuem contato com seus conceitos básicos.

**PALAVRAS-CHAVE:** linguagem de programação; lógica de programação; compiladores; análise
sintática;

O projeto atual pode ser complementado utilizando esse resultado para implementar o analisador sintático para compeender a linguagem, já que ela esta estrutura e com sua base sintática definida.

**Alguns Exemplos de código utilizando esta anotação sintática**

**_Exemplo 1 — Olá mundo!_**

    Arquivo “ola_mundo.hln”
    escreva "Olá mundo!"
    
    
**_Exemplo 2 — Olá (des)conhecido!_**

    texto nome
    leia nome

    se nome != ''
      escreva "Olá {:nome}!"
    senão
      escreva "Olá (des)conhecido."
      siga
      
      
      
**_Exemplo 5 — Ímpares_**

    rotina escreva_ímpares(natural [] números)
        para i = números
            se i % 2 == 1 então escreva extenso(i); ' '
            volte
        retorne

    natural [] exemplo = [0; 1; 2; 3; 4; 5; 6; 7; 8; 9]
    escreva_ímpares(exemplo)



