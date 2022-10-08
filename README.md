# Maia
var palavra;

function reverse(palavra){
    splitPalavra = palavra.split("");
    reversePalavra = splitPalavra.reverse();
    joinPalavra = reversePalavra.join("")
    
    return joinPalavra
}

console.log(reverse(prompt('Digite uma palavra')));
