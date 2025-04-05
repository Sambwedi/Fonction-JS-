# Fonction-JS-
Index.js
function sommeOuTriple(a, b) {
    let somme = a + b;
    return (a === b) ? somme * 3 : somme;
}
alert(sommeOuTriple(4, 4)); 
alert(sommeOuTriple(4, 5)); 




function differenceAvec51(n) {
    let difference = Math.abs(n - 51);
    return (n > 51) ? difference * 2 : difference;
}
alert(differenceAvec51(30)); 
alert(differenceAvec51(60)); 



function verifierNombre(n) {
    return n > 10 || (n >= 200 && n <= 400);
}
alert(verifierNombre(8)); 
alert(verifierNombre(250)); 
alert(verifierNombre(15));


function divisiblePar3Ou7(n) {
    return n % 3 === 0 || n % 7 === 0;
}
alert(divisiblePar3Ou7(9)); 
alert(divisiblePar3Ou7(14)); 
alert(divisiblePar3Ou7(10));






function maximumDeTrois(a, b, c) {
    return Math.max(a, b, c);
}
console.log(maximumDeTrois(10, 20, 30)); 
console.log(maximumDeTrois(5, 8, 2)); 
