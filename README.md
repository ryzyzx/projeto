// Variáveis para armazenar o nome e a quantidade de XP do herói
let nomeHeroi = "HeróiX"; // Substitua pelo nome desejado
let xpHeroi = 7500; // Substitua pela quantidade de XP desejada

// Estrutura de decisão para verificar a categoria
let categoria;

if (xpHeroi < 1000) {
    categoria = "Ferro";
} else if (xpHeroi >= 1001 && xpHeroi <= 2000) {
    categoria = "Bronze";
} else if (xpHeroi >= 2001 && xpHeroi <= 5000) {
    categoria = "Prata";
} else if (xpHeroi >= 5001 && xpHeroi <= 7000) {
    categoria = "Ouro";
} else if (xpHeroi >= 7001 && xpHeroi <= 8000) {
    categoria = "Platina";
} else if (xpHeroi >= 8001 && xpHeroi <= 9000) {
    categoria = "Ascendente";
} else if (xpHeroi >= 9001 && xpHeroi <= 10000) {
    categoria = "Imortal";
} else {
    categoria = "Radiante";
}

// Exibir o resultado
console.log(`O herói ${nomeHeroi} possui ${xpHeroi} XP e pertence à categoria: ${categoria}.`);
