# Boletim-VISUALG
Teste de um boletim em algoritmo em linguagem Portunol 
Algoritmo  "Bulleting"
var
nome : caractere
nota1, nota2, nota3 : real
media : real
Aprovados ,  Reprovados : inteiro

 inicio

           Escreval ("Digite o nome do aluno : ")
 Leia (NOME)

     Escreva ("Digite a primeira Nota : ")
     Leia ( nota1)

          Escreva ("Digite a segunda nota ")
          Leia (nota2 )

              Escreva ("Digite a terceira nota ")
              Leia ( nota3)
              Media <-(Nota1+nota2+nota3)/3
        Escreval ("A media do aluno é ", Media )

    Se Media >= 6 então
   Escreval ("Aluno Aprovado")

    Senao Media <= 5
   Escreval ("Aluno Reprovado")

   fimse

           Escreval ("Digite o nome do segundo aluno : ")
 Leia (NOME)

     Escreva ("Digite a primeira Nota : ")
     Leia ( nota1)

          Escreva ("Digite a segunda nota ")
          Leia (nota2 )

              Escreva ("Digite a terceira nota ")
              Leia ( nota3)
              Media <-(Nota1+nota2+nota3)/3
        Escreval ("A media do aluno é ", Media )

    Se Media >= 6 então
   Escreval ("Aluno Aprovado")
      
    Senao Media <= 5
   Escreval ("Aluno Reprovado") 

     fimse
fimalgoritmo
