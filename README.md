# Aprendendo-programa-ao
// Este repositório contém as práticas de programação que estou praticando no curso, codigo a baixo na linguagem JavaScript

alert('Boas vindas ao jogo do número secreto');
let numeroSecreto = 5;
console.log(numeroSecreto)
let chute = prompt('Escolha um número entre 1 e 10');

//enquanto o chute nao for igual ao numero secreto.
while (chute != numeroSecreto) {
    chute = prompt(" escolha um numero entre 1 a 10");

// se chute for igual ao número secreto
    if (chute == numeroSecreto) {
        alert(`Isso ai! Você descobriu o número secreto ${numeroSecreto}`);
    } else {
        if (chute > numeroSecreto) {
            alert(`o numero secreto é menor que ${chute}`);
        } else {
            alert(`O numero secreto é maior que ${chute}`);
        }
    }



}
