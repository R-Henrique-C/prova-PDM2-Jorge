let chamadaDeAlunos = [ //OBJ de alunos
    {
        nome: "Kayky",
        idade: 16,
        materias: [
            {
                nome: "Tecnologias em Inteligência Artificial",
                presenca: 75,
                nota: 10
            },
            {
                nome: "Programação para Dispositivos Móveis",
                presenca: 90,
                nota: 10
            },
        ],
        numeroChamada: 1221
    },
    {
        nome: "Ana",
        idade: 17,
        materias: [
            {
                nome: "BD1",
                presenca: 100,
                nota: 10
            },
            {
                nome: "Programação para Dispositivos Móveis",
                presenca: 90,
                nota: 7.5
            },
        ],
        numeroChamada: 1222
    },
    {
        nome: "Matheus",
        idade: 20,
        materias: [
            {
                nome: "Tecnologias em Inteligência Artificial",
                presenca: 79,
                nota: 8.5
            },
            {
                nome: "Programação para Dispositivos Móveis",
                presenca: 60,
                nota: 6.5
            },
        ],
        numeroChamada: 1223
    },
    {
        nome: "Jorge",
        idade: 19,
        materias: [
            {
                nome: "Tecnologias em Inteligência Artificial",
                presenca: 100,
                nota: 10
            },
            {
                nome: "Programação para Dispositivos Móveis",
                presenca: 79,
                nota: 10
            },
        ],
        numeroChamada: 1224
    },
    {
        nome: "Richard",
        idade: 18,
        materias: [
            {
                nome: "BD2",
                presenca: 74,
                nota: 10
            },
            {
                nome: "BD1",
                presenca: 90,
                nota: 7
            },
        ],
        numeroChamada: 1225
    },
]

// Mostrar nome e nota dos alunos
function showNomeNota(aluno){
    for(let i = 0; i < aluno.length; i++){ //for que printa todos os nomes
        console.log("Nome: " + aluno[i].nome)

        for(let j = 0; j < aluno[i].materias.length; j++){ //for que printa todas as notas
            console.log("Nota: " + aluno[i].materias[j].nota) 
        }
        console.log("\n--------------------")
    }
}

showNomeNota(chamadaDeAlunos)

// Mostrar os alunos aprovados e reprovados (nota > 6 & presenca > 75%)
function checkAprovados(aluno){
    for(let i = 0; i < aluno.length; i++){
        for(let j = 0; j < aluno[i].materias.length; j++){
            //verifica se o aluno foi aprovado
            if(aluno[i].materias[j].nota >= 6 && aluno[i].materias[j].presenca >= 75){
                //se for aprovado, printar que foi 
                console.log("O ALUNO : " + aluno[i].nome.toUpperCase() + " FOI APROVADO(A)")
            }
        }
    }
    console.log("\n----------------------------")
}

checkAprovados(chamadaDeAlunos)

// Mostrar os alunos reprovados
function checkReprovados(aluno){
    for(let i = 0; i < aluno.length; i++){
        for(let j = 0; j < aluno[i].materias.length; j++){
            //verifica se o aluno foi aprovado
            if(aluno[i].materias[j].nota < 6 && aluno[i].materias[j].presenca < 75){
                //se não for aprovado, printar que não foi
                console.log("O ALUNO : " + aluno[i].nome.toUpperCase() + " FOI REPROVADO(A)")                
            } else{
                console.log("NINGUÉM FOI REPROVADO")
            }
        }
    }
    console.log("\n----------------------------")
}

checkReprovados(chamadaDeAlunos)

// Top 3 alunos com maior nota

// Top 3 alunos com menor nota
