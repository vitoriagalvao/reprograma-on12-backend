## Algoritmo Salario Funcionario

var
salario,percentual,novosalario:real
inicio
// Seção de Comandos

escreval ("Digite o salario atual: ")
leia (salario)

se (salario == or < 500) então
escreval ("Digite o número: 20 ")
leia (percentual)

novosalario <- salario\*percentual/100

novosalario <- novosalario+salario

escreval ("Salario novo é:", novosalario)

senao
se (salario > 500)então
escreva("Digite o número: 10")

leia (percentual)

novosalario <- salario\*percentual/100

novosalario <- novosalario+salario

escreval ("Salario novo é:", novosalario)

fimalgoritmo
