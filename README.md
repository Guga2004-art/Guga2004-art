//Gustavo_Candido Readme
let linguagensDeProgramacao = ["Python", "JavaScript", "GML"]
let estouDescansando = false
let estouEmUmProjeto = true

if (estouEmUmProjeto) {
console.log("Estou fazendo algo no momento")
} else if (estouDescansando) {
  console.log("Estou descansando.")
} else {
  null
}
function Vida(){
let Estudo = linguagensDeProgramacao
let Faculdade = "Anhanguera"
let curso = "Ads" || "Analise e desenvolvimento de sistemas"
return `Estou na ${Faculdade} cursando ${curso} e ${Estudo}`
}

let eu = {
  nome: "Gustavo Candido Lopes da Silva",
  idade: 20,
  hobbies: ["Programar", "jogar"],
  noTempoLivre: "Dar uma volta e jogar conversa fora",
  faculdade: "Anhanguera",
  curso: "Analise e desenvolvimento de sistemas"
}
console.log(Vida(), eu, "Fim")

