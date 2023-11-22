# ProjectsInC
Conjunto de algoritmos em linguagem C, de diferentes problemas, reunidos em um repositorio.
//=========================================================================//
//-------------------------Ex1: MAIOR ELEMENTO-----------------------------//
REQUISITOS:
DESCOBRE O MAIOR VALOR LIDO E DIZ SUA POSICAO

//=========================================================================//
//-------------------Ex2: MATRIZ ELEMENTOS MAIOR E MENOR-------------------//
REQUISITOS:
CRIA UMA MATRIZ E O PREENCHE E AO FIM, MOSTRA O MAIOR E MENOR ELEMENTOS, E SUA RESPECTIVA POSIÇÃO

//===========================================================================//
//-------------------Ex3: CONTROLE DE ESTOQUE EM VETORES---------------------//
REQUISITOS:
PREENCHE UM VETOR COM AS VENDAS DE UM DETERMINADO SETOR EM DETERMINADOS DIAS N, E AO FIM, MOSTRA O DIA COM MAIOR VENDA, MENENOR VENDA, VOLUME MEDIO DE VENDA E VALOR TOTAL VENDIDO


//-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=--=-=-=-=-=-=-=-=-=-=-=-ESTRUTURA DE DADOS-=-=-=-=-=-=-=-=-=--=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-//
Ex4: VETORES
REQUISITOS:


EX5: MATRIZES
REQUISITOS:


EX6: MODULARIZAÇÃO
REQUISITOS:



EX7: MATRIZ TRANSPOSTA MODULARIZADA
REQUISITOS:



EX8:MDC RECURSIVO
REQUISITOS:


EX9:SOMA RECURSIVA
REQUISITOS:


EX10: EXPONENCIAÇÃO RECURSIVA
REQUISITOS:


EX11: VETOR DINAMICO
REQUISITOS:


EX12: INVERSAO DINAMICA
REQUISITOS:


EX13: SOMA DINAMICA
REQUISITOS:


EX14: PARES E EIMAPRES
REQUISITOS:


EX15: MATRIZ DINAMICA
REQUISITOS:


EX16: MATRIZ IDENTIDADE
REQUISITOS:


EX17: HISTOGRAMA
REQUISITOS:

//=========================================================================================//
//------------------------------------EX18: STRUCT LIVRO-----------------------------------//
REQUISITOS:  
Defina um ponteiro para uma struct capaz de armazenar dados sobre um livro. O registro contém os seguintes dados: nome, ISBN, preco, avaliacao e editora. Usando este registro faça:
Uma função que aloque o(s) livro(s) e devolva um ponteiro para o bloco de livro(s). Obs: a função deve receber a quantidade de livros a ser alocada.
Uma função que leia do teclado os dados do livro (receba o livro como parâmetro).
Uma função que mostre os dados do livro lido.
Uma função que desaloque os dados do livro lido.
Inicialmente, a primeira leitura deve informar quantos livros serão inseridos. Em seguida, a leitura de cada livro deve seguir a mesma ordem dos campos acima descritos.
Ao final, apresente os dados do livro seguindo o formato exemplificado abaixo:
[Registro 1]
Nome: O Homem que Calculava
ISBN: 8501061964
Preço: R$ 34.90
Avaliação: 4,9
Editora: Record

//==========================================================================================//
//------------------------------------EX19: TAD LIVRO---------------------------------------//
REQUISITOS:
Reescreva o algoritmo construído anteriormente criando um Tipo Abstrato de Dados chamado TADLivro. Obs: criei os arquivos das estruturas para o TAD para que você migre seu código anterior no formado do tipo abstrado.
------------------- Definição anterior -----------------
Defina um ponteiro para uma struct capaz de armazenar dados sobre um livro. O registro contém os seguintes dados: nome, ISBN, preco, avaliacao e editora. Usando este registro faça:
Uma função que aloque o(s) livro(s) e devolva um ponteiro para o bloco de livro(s). Obs: a função deve receber a quantidade de livros a ser alocada.
Uma função que leia do teclado os dados do livro (receba o livro como parâmetro).
Uma função que mostre os dados do livro lido.
Uma função que desaloque os dados do livro lido.
Inicialmente, a primeira leitura deve informar quantos livros serão inseridos. Em seguida, a leitura de cada livro deve seguir a mesma ordem dos campos acima descritos.
Ao final, apresente os dados do livro seguindo o formato exemplificado abaixo:
[Registro 1]
Nome: O Homem que Calculava
ISBN: 8501061964
Preço: R$ 34.90
Avaliação: 4,9
Editora: Record

//===============================================================================================//
//-------------------------------------EX20: TAD CPF---------------------------------------------//
REQUISITOS:
O Cadastro Nacional de Pessoal Física (CPF) é um número que identifica de forma única um brasileiro e lhe assegura direitos enquanto cidadão. Ele é composto por 11 dígitos, sendo que os dois últimos correspondem ao dígito verificador.
Crie um T.A.D chamado CPF contendo uma estrutura capaz de manipular esse tipo abstrato. Nele, insira as seguintes funcionalidades:
Ler um CPF
Exibir o CPF (respeitando a formatação xxx.xxx.xxx-xx)
Validar um CPF (para isso, calcule o dígito verificar do número gerado). Dica como calcular o dígito verificador: https://campuscode.com.br/conteudos/o-calculo-do-digito-verificador-do-cpf-e-do-cnpj
Seu programa deve ler como comandos de entrada e seus respectivos valores (separados por espaços).
Os comandos possíveis são:
-l : o programa irá ler um CPF (apenas números)
-e : exibe o CPF lido usando a formatação para exibição
-v : valida ou invalida o CPF lido

//===================================================================================================//
//-----------------------------------EX21: IMPLEMENTAÇÃO PILHA---------------------------------------//
REQUISITOS:
Implemente um tipo abstrato de dados do tipo “Pilha" chamado TPilha.
Este deve manipular dados do tipo char e oferecer os seguintes serviços:
Exibir todos os elementos que estão na pilha
Esvaziar toda a pilha
Função push
Função pop
Não esqueça que o último elemento que entra na pilha deverá ser o primeiro a sair (LIFO - Last in First out
Entrada e saída de dados:
Seu programa deve ler como comandos de entrada e seus respectivos valores (separados por espaços). Os comandos possíveis são:
-s : exibe a pilha inteira
-c : esvaziar toda a pilha
-i : inserir (empilhar) um novo elemento na fila
-r : remover (desempilhar) um elemento da fila
Obs: após a execução do comando "-s", o programa deve ser encerrado.

//=================================================================================================//
//---------------------------------------EX22: IMPLEMENTAÇÃO FILA----------------------------------//
REQUISITOS:
Implemente um tipo abstrato de dados do tipo “Fila", chamado TFila.
Este deve manipular dados do tipo int e oferecer os seguintes serviços:
Exibir todos os elementos que estão na fila
Esvaziar toda a fila
Função para enfileirar
Função para desenfileirar
Não esqueça que o primeiro elemento que entra na fila deverá ser o primeiro a sair (FIFO - First in First out).
Entrada e Saída de dados:
Seu programa deve ler como comandos de entrada e seus respectivos valores (separados por espaços). Os comandos possíveis são:
-s : exibe a fila inteira
-c : esvaziar toda a fila
-i : inserir (enfileirar) um novo elemento na fila
-r : remover (desenfileirar) um elemento da fila
Obs: após a execução do comando "-s", o programa deve ser encerrado.

//=============================================================================================================//
//-------------------------------------EX23: IMPLEMENTAÇÃO LISTA SIMPLESMENTE ENCADEADA------------------------//
REQUISITOS:
Crie um tipo abstrato de dados para manipulação de uma Lista Simplesmente Encadeada. A Lista deve ser capaz de manipular dados do tipo int.
Atente para os requisitos solicitados e implemente as funcionalidades desejadas.
Seu programa deve ser capaz de ler como comandos de entrada os possíveis valores:
-s : exibe a lista inteira
-c : esvaziar toda a lista
-a < valor > : inserir um novo elemento na lista com o valor especificado (inserção estilo FIFO)
-a < valor > < posicao > : inserir um novo elemento na lista em uma posição especificada pelo parâmetro “posicao"
-r < valor > : remover todas as ocorrências de um elemento especificado da lista
-m : exibe o maior valor da lista
-sl : exibe o último elemento da lista
-sf : exibe o primeiro elemento da lista
-ss : exibe o tamanho da lista
-sg < valor > : exibe a quantidade de elementos da lista são maiores que o valor especificado
O comando -s deve exibir a lista e encerrar o programa.

//===============================================================================================================//
//----------------------------------EX24: IMPLEMENTAÇÃO LISTA SIMPLESMENTE ENCADEADA CIRCULAR--------------------//
REQUISITOS:
Crie um tipo abstrato de dados para manipulação da Lista Simplesmente Encadeada Circular.
Atenção! A lista deve armazenar dados do tipo float.
Atente para os requisitos solicitados e implemente as funcionalidades desejadas.
Seu programa que deve ser capaz de ler como comandos de entrada os possíveis valores:
-s : exibe a lista inteira
-c : esvaziar toda a lista
-a < valor > : inserir um novo elemento na lista com o valor especificado (a inserção segue o padrão FIFO)
-a < valor > < posicao > : inserir um novo elemento na lista em uma posição especificada pelo parâmetro “posicao"
-r < valor > : remover todas as ocorrências de um elemento especificado da lista
-m : exibe o maior valor da lista
-sl : exibe o último elemento da lista
-sf : exibe o primeiro elemento da lista
-ss : exibe o tamanho da lista
-sg < valor > : exibe a quantidade de elementos da lista são maiores que o valor especificado
O comando -s deve exibir a lista e encerrar o programa.

//===================================================================================================================//
//------------------------------------------EX25: IMPLEMENTAÇÃO LISTA DUPLAMENTE ENCADEADA---------------------------//
REQUISITOS:
Crie um tipo abstrato de dados para manipulação de uma Lista Duplamente Encadeada. A Lista deve ser capaz de manipular dados do tipo char.
Atente para os requisitos solicitados e implemente as funcionalidades desejadas.
Seu programa deve ser capaz de ler como comandos de entrada os possíveis valores:
-s : exibe a lista inteira
-c : esvaziar toda a lista
-a < valor > : inserir um novo elemento na lista com o valor especificado (inserção estilo FIFO)
-a < valor > < posicao > : inserir um novo elemento na lista em uma posição especificada pelo parâmetro “posicao"
-r < valor > : remover todas as ocorrências de um elemento especificado da lista
-m : exibe o maior valor da lista
-sl : exibe o último elemento da lista
-sf : exibe o primeiro elemento da lista
-ss : exibe o tamanho da lista
-sg < valor > : exibe a quantidade de elementos da lista são maiores que o valor especificado
O comando -s deve exibir a lista e encerrar o programa.

//========================================================================================================================//
//---------------------------------------EX26: IMPLEMENTAÇÃO LISTRA DUPLAMENTE ENCADEADA CIRCULAR-------------------------//
REQUISITOS:
Crie um tipo abstrato de dados para manipulação da Lista Duplamente Encadeada Circular.
Atenção! A lista deve armazenar dados do tipo int.
Atente para os requisitos solicitados e implemente as funcionalidades desejadas.
Seu programa que deve ser capaz de ler como comandos de entrada os possíveis valores:
-s : exibe a lista inteira
-c : esvaziar toda a lista
-a < valor > : inserir um novo elemento na lista com o valor especificado (a inserção segue o padrão FIFO)
-a < valor > < posicao > : inserir um novo elemento na lista em uma posição especificada pelo parâmetro “posicao"
-r < valor > : remover todas as ocorrências de um elemento especificado da lista
-m : exibe o maior valor da lista
-sl : exibe o último elemento da lista
-sf : exibe o primeiro elemento da lista
-ss : exibe o tamanho da lista
-sg < valor > : exibe a quantidade de elementos da lista são maiores que o valor especificado
O comando -s deve exibir a lista e encerrar o programa.

//=====================================================================================================================//
