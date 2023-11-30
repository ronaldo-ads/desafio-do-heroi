# desafio-do-heroi. 
# Código em Javascript

//Desafio de Projeto 

// Definindo o nome e a quantidade de experiência (XP) do herói
let nomeDoHeroi = "Herói X"; // Substitua "Herói X" pelo nome do seu herói
let experiencia = 2000; // Substitua o valor 2000 pela quantidade de experiência do seu herói

let nivelDoHeroi;

// Utilizando uma estrutura de decisão para determinar o nível do herói com base na experiência
if (experiencia < 1000) {
  nivelDoHeroi = "Ferro";
} else if (experiencia >= 1001 && experiencia <= 2000) {
  nivelDoHeroi = "Bronze";
} else if (experiencia >= 2001 && experiencia <= 5000) {
  nivelDoHeroi = "Prata";
} else if (experiencia >= 6001 && experiencia <= 7000) {
  nivelDoHeroi = "Ouro";
} else if (experiencia >= 7001 && experiencia <= 8000) {
  nivelDoHeroi = "Platina";
} else if (experiencia >= 8001 && experiencia <= 9000) {
  nivelDoHeroi = "Ascendente";
} else if (experiencia >= 9001 && experiencia <= 10000) {
  nivelDoHeroi = "Imortal";
} else {
  nivelDoHeroi = "Radiante";
}

// Exibindo a mensagem com o nome do herói e seu nível
console.log(`O Herói de nome ${nomeDoHeroi} está no nível de ${nivelDoHeroi}`);.
