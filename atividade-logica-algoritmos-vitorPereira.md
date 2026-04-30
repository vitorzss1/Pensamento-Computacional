CENTRO UNIVERSITÁRIO DO DISTRITO FEDERAL
PENSAMENTO COMPUTACIONAL - Profª Kadidja Valeria
Vitor Pereira da Silva MarƟns – RGM 43952810

1. O Desafio: Controle de Acesso

Algoritmo ControleDeAcesso 
// Lista oficial de alunos permitidos 
ListaOficial <- [lista de alunos cadastrados] 
// Lista de alunos na fila de entrada 
FilaAlunos <- [lista de alunos que chegam] 
// Enquanto ainda houver alunos na fila, repetir o processo 
Enquanto FilaAlunos não estiver vazia faça 
// Retira o próximo aluno da fila 
AlunoAtual <- remover primeiro elemento de FilaAlunos 
// Verificação: checar se o aluno está na lista oficial 
Se AlunoAtual estiver em ListaOficial então 
Escrever "Entrada permitida para: " + AlunoAtual 
Senão 
Escrever "ACESSO NEGADO: " + AlunoAtual + " não consta na lista oficial" 
FimSe 
FimEnquanto 
Escrever "Todos os alunos foram verificados." 
FimAlgoritmo
