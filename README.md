# algortmos_treino_javascript
//1-Concatenação de vetores
let cidadesBrasileiras = ["Rio de Janeiro","São Paulo","Florianopolis"]
let cidadesEstrangeiras = ["Tokyo", "Quito" , "Naguma"]

cidadesBrasileiras.concat([cidadesEstrangeiras])

//2- Removendo e Substituindo Elementos com Splice
let nomesDeAnimais = ["Capivara","Gato","Orca","Leão","Coelho","Corvos"]

nomesDeAnimais.splice(1,2, "Tigre", "Pato")
console.log(nomesDeAnimais)

//3.   Verificando Condição com Estruturas de Controle 
let numeros = [10,20,40,60,70]

const maioresQue50 = numeros.filter(numero => numero >50)
console.log("Existem",maioresQue50.length, "números maiores que 50")

//4. Somando Valores com um Loop for
const numeros = [4,4,12];
let soma = 0;

for(let i = 0; i < numeros.length; i++){
 soma += numeros[i];
}
console.log("O resultado é", soma)

//5. Somando Valores com um Loop  while
const numeros = [4,4,12];
let soma = 0;
let i = 0

while(i < numeros.length){
 soma += numeros[i];
  i++;
}
console.log("O resultado é", soma)

