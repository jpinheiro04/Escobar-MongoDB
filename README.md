db.veiculos.insertOne(
    [
    { marca: 'Fiat1', modelo: 'Uno', cor: 'Vermelho', ano: 2020 },
    { marca: 'Fiat1', modelo: 'palio', cor: 'Vermelho', ano: 2020 }
    ]
);

db.veiculos.find()

db.alunos.findOne({ nome: "/Joao^/"})
db.alunos.find({ nome: "/Joao^/"})
db.alunos.insert({})
db.alunos.insertOne({})

db.alunos.update({<WHERE>}, {<SET>})
db.alunos.updateOne(
    { marca: 'Fiat' },
    { $set: { modelo: 'punto', cor: "azul" }}
);

use('aluno')

db.posts.insert(  
    {
        "Titulo": "Meu primeiro",
        "resumo": "Aqui foi o dia que cai de bunda",
        "telefone": "(11 999412314213) "/>,   
        "comentario": [
            {
                "comentario": "Nossa que legau",
                "data": "15/02/2024",
                "nome": "Cleiton",
                "reply": [
                    {
                        "comentario": "foi foda",
                        "nome": "joana"
                    },
                ]
            }
        ]
    }
)

db.posts.find()

db.posts.find(
    {
       "Titulo": "Meu primeiro post"
    }
)

/*
F - find
U - update
C - create
K - kill
*/
