# ProjectsInC
## Conjunto de algoritmos em linguagem C, de diferentes problemas, reunidos em um repositorio.



# *//-=-=-=-=-=-=-=-=-= Exemplos Simples-=-=-=-=-=-=-=-=-=--=-=//*

//================================================================================//
### *Ex1: MAIOR ELEMENTO*
### *REQUISITOS:*
- DESCOBRE O MAIOR VALOR LIDO E DIZ SUA POSICAO

//=================================================================================//
### *Ex2: MATRIZ ELEMENTOS MAIOR E MENOR*
### *REQUISITOS:*
- CRIA UMA MATRIZ E O PREENCHE E AO FIM, MOSTRA O MAIOR E MENOR ELEMENTOS, E SUA RESPECTIVA POSIÇÃO

//==============================================================================//
### *Ex3: CONTROLE DE ESTOQUE EM VETORES*
### *REQUISITOS:*
- PREENCHE UM VETOR COM AS VENDAS DE UM DETERMINADO SETOR EM DETERMINADOS DIAS N, E AO FIM, MOSTRA O DIA COM MAIOR VENDA, MENENOR VENDA, VOLUME MEDIO DE VENDA E VALOR TOTAL VENDIDO



# *//-=-=-=-=-=-=-=-=-= ESTRUTURA DE DADOS -=-=-=-=-=-=-=-=-=-//*

//==========================================++++================================//
### Ex4: VETORES
### *REQUISITOS:*
- Você é um desenvolvedor trabalhando em um sistema de controle de estoque para uma loja de eletrônicos. A loja vende produtos como smartphones, laptops e tablets. O gerente sempre está interessado em saber dados sobre o volume das vendas no final do dia. Sua tarefa neste exercício é ler o volume (em reais R$) de N dias de venda para então descobrir (a) o dia que mais vendeu, (b) o dia que menos vendeu, (c) a média de vendas no intervalo de N dias e (d) o valor total das vendas em todo o intervalo.
Obs: seu algoritmo não deve mostrar mensagens de interação com o usuário, pois os testes serão realizados automaticamente por um outro algoritmo de teste. Sendo assim, o usuário do seu algoritmo será um "robô".
Etapas: 1. Leia o número de dias; 2. Para cada dia, leia o volume das vendas; 3. Mostre para o gerente os dados solicitados.

//==================================================================================//
### EX5: MATRIZES
### *REQUISITOS:*
- Você é um desenvolvedor trabalhando em um sistema que gerencia uma agenda de atendimentos para um consultório odontológico. O gerente precisa monitorar os horários vagos da agenda para tentar encaixar pacientes. Ao mesmo tempo, ele precisa saber a distribuição dos atendimentos especialistas em cada dia para melhor organizar o revesamento dos profissionais. Sua missão é escrever um programa capaz de ler uma matriz de tamanho fixo para representar os atendimentos de segunda à sábado. As marcações dos atendimentos consideram que cada atendimento demora 1 hora, limitado a 6 horas por dia. A estrutura deve armazenar qual a especialidade agendada. Os especialistas possíveis são:
1.Clinico geral
   2. Odontopediatra
   3. Ortodontista
   4. Endodontista
   5. Periodontista
   6. stomatologista
   7. Protesista
   8.  Cirugiao bucomaxilofacial
   9. Dentistica Restauradora
O valor zero (0) representa que há um horário vago na agenda.
Obs: seu algoritmo não deve mostrar mensagens de interação com o usuário, pois os testes serão realizados automaticamente por um outro algoritmo de teste. Sendo assim, o usuário do seu algoritmo será um "robô".
Etapas:
Leia a agenda completa
Leia um dia específico da semana
Mostre a quantidade de horários vagos total na agenda
Mostre a quantidade de horários vagos na agenda para o dia lido
Mostre, para cada especialidade, o volume total na agenda
Mostre, para cada especialidade, o volume total para o dia lido
Obs: o algoritmo não precisa validar as quantidades. Os testes foram gerados com agendas ALEATÓRIAS

//===================================================================================//
### EX6: MODULARIZAÇÃO
### *REQUISITOS:*
- Escreva um programa que, por meio de uma função, retorne a soma dos números inteiros que existem entre n1 e n2 (inclusive), ambos informados pelo usuário. A função deve funcionar inclusive se o valor de n2 for menor que n1. Leia n1 e n2 no programa principal e passe-os como parâmetro para a função.

//=================================================================================//
### EX7: MATRIZ TRANSPOSTA MODULARIZADA
### *REQUISITOS:*
- Declare uma matriz 2x3 no bloco principal. Depois escreva funções para:
Ler a matriz 2x3 (a matriz é repassada como parâmetro)
Gerar e devolver sua transposta (matriz 3x2)
Exibir uma matrize recebida como parâmetro
Ao final, chame as funções no bloco principal de modo que o resultado seja como no exemplo demonstrado.

//===============================================================================//
### EX8:MDC RECURSIVO
### *REQUISITOS:*
- [Tremblay-Bunt] Um algoritmo muito conhecido para determinar o maior divisor comum de dois números inteiros é o algoritmo de Euclides. A função maior divisor comum é definida como segue:
MDC(M,N) = MDC(N,M) se N > M
M se N = 0
MDC(N, M mod N) se N > 0
Implemente um algoritmo com uma função recursiva para calcular o MDC dos valores de M e N (lidos pelo teclado).

//=================================================================================//
### EX9:SOMA RECURSIVA
### *REQUISITOS:*
- Escreva uma função recursiva que calcule a soma dos dígitos de um inteiro positivo n.

//=====================================================================================//
### EX10: EXPONENCIAÇÃO RECURSIVA
### *REQUISITOS:*
- Sendo xn = x * x(n-1), faça um algoritmo que utilize uma função recursiva para calcular a potência de um número qualquer (recebido como parâmetro). Receba como parâmetro da função os valores de x e n.

//====================================================================================//
### EX11: VETOR DINAMICO
##### Equipe: Lais, Rosana, Vinicius
### *REQUISITOS:*
- Crie um programa modularizado capaz de alocar dinamicamente um vetor de números reais de tamanho n definidos durante a execução do programa. Nesse vetor, serão armazenados a altura de n pessoas e que deverão ser lidos pelo teclado. Ao final, o programa deve imprimir a maior, a menor e a média das alturas. Obs: precisão de 2 casas decimais.

//==================================================================================//
### EX12: INVERSAO DINAMICA
##### Equipe: Lais, Claudia
### *REQUISITOS:*
- Escreva um programa capaz de alocar dinamicamente valores inteiros positivos. O programa deve ler um número inteiro positivo n e em seguida n números inteiros. Imprima esses n números em ordem invertida. Não esqueça de desalocar a memória usada.

//=======================================================================================//
### EX13: SOMA DINAMICA
##### Equipe: Lais, Claudia
### *REQUISITOS:*
- Crie um programa que aloca dinamicamente um vetor de inteiros de tamanho n (informado pelo usuário). Todos os n números devem ser inseridos pelo usuário, um a um. Ao final, o programa deve calcular e imprimir a soma de todos os valores.

//====================================================================================//
### EX14: PARES E IMPARES
##### Equipe: Lais, Claudia
### *REQUISITOS:*
- Faça um programa que aloque memória para n inteiros inseridos pelo usuário. Em seguida, mostre quantos dos números são pares e quantos são ímpares.

//=============================================================================================//
### EX15: MATRIZ DINAMICA
##### Equipe: Lais, Claudia
### *REQUISITOS:*
- Construa um programa modularizado que:
Aloque dinamicamente uma matriz quadrada de ordem n x n (linha por coluna) (n lido pelo teclado)
Leia os valores para preencher a matriz
Multiplique os valores da diagonal principal.
Mostre o valor da multiplicação
Desaloque a memória alocada para a matriz

//=====================================================================================//
### EX16: MATRIZ IDENTIDADE
##### Equipe: Lais, Claudia
### *REQUISITOS:*
- Crie um programa modularizado para:
Alocar uma matriz de dimensão nxn, em que n é determinado pelo usuário.
Povoar a matriz gerada de modo que ela torne-se uma matriz identidade (matriz quadrada em que os elementos da diagonal principal são iguais a 1 e os demais elementos são iguais a 0)
Mostrar a matriz resultante
Desalocar a memória utilizada

//==========================================================================================//
### EX17: HISTOGRAMA
##### Equipe: Lais, Claudia, Rosana
### *REQUISITOS:*
- Faça um programa modularizado que leia e construa a seguinte tabela de histogramas:
Elemento Valor Histograma A 4 ∗∗∗∗ B 2 ∗∗ C 8 ∗∗∗∗∗∗∗∗ D 12 ∗∗∗∗∗∗∗∗∗∗∗∗ E 1 ∗ Soma 27 ***************************
A quantidade de elementos (n) deve ser lida no programa principal. A quantidade de elementos será o parâmetro para uma alocação dinâmica do histograma. Dica: Use um vetor de ponteiros. Ao final, sua estrutura deve permitir o cálculo da soma dos valores para exibir o histograma da soma (veja a saída esperada no caso de teste). Dica: faça funções para cada "mini problema".
Obs: Todas as impressões devem ser feitas em função(ões) específica(s) para impressão na tela. Jamais dentro da função que constrói ou lê dados. A(s) função(ões) para impressão devem receber a estrutura de dados como parâmetro para então percorrer e imprimir os dados.

//=========================================================================================//
### EX18: STRUCT LIVRO
### *REQUISITOS:*  
- Defina um ponteiro para uma struct capaz de armazenar dados sobre um livro. O registro contém os seguintes dados: nome, ISBN, preco, avaliacao e editora. Usando este registro faça:
Uma função que aloque o(s) livro(s) e devolva um ponteiro para o bloco de livro(s). Obs: a função deve receber a quantidade de livros a ser alocada.
Uma função que leia do teclado os dados do livro (receba o livro como parâmetro).
Uma função que mostre os dados do livro lido.
Uma função que desaloque os dados do livro lido.
Inicialmente, a primeira leitura deve informar quantos livros serão inseridos. Em seguida, a leitura de cada livro deve seguir a mesma ordem dos campos acima descritos.

//===========================================================================================//
### EX19: TAD LIVRO
### *REQUISITOS:*
- Reescreva o algoritmo construído anteriormente criando um Tipo Abstrato de Dados chamado TADLivro. Obs: criei os arquivos das estruturas para o TAD para que você migre seu código anterior no formado do tipo abstrado.

//=====================================================================================//
### EX20: TAD CPF
### *REQUISITOS:*
- O Cadastro Nacional de Pessoal Física (CPF) é um número que identifica de forma única um brasileiro e lhe assegura direitos enquanto cidadão. Ele é composto por 11 dígitos, sendo que os dois últimos correspondem ao dígito verificador.
Crie um T.A.D chamado CPF contendo uma estrutura capaz de manipular esse tipo abstrato. Nele, insira as seguintes funcionalidades:
Ler um CPF
Exibir o CPF (respeitando a formatação xxx.xxx.xxx-xx)
Validar um CPF (para isso, calcule o dígito verificar do número gerado). Dica como calcular o dígito verificador: https://campuscode.com.br/conteudos/o-calculo-do-digito-verificador-do-cpf-e-do-cnpj
Seu programa deve ler como comandos de entrada e seus respectivos valores (separados por espaços).
Os comandos possíveis são:
-l : o programa irá ler um CPF (apenas números)
-e : exibe o CPF lido usando a formatação para exibição
-v : valida ou invalida o CPF lido

//=============================================================================//
### EX21: IMPLEMENTAÇÃO PILHA
### *REQUISITOS:*
- Implemente um tipo abstrato de dados do tipo “Pilha" chamado TPilha.
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

//================================================================================//
### EX22: IMPLEMENTAÇÃO FILA
### *REQUISITOS:*
- Implemente um tipo abstrato de dados do tipo “Fila", chamado TFila.
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

//===============================================================================//
### EX23: IMPLEMENTAÇÃO LISTA SIMPLESMENTE ENCADEADA
### *REQUISITOS:*
- Crie um tipo abstrato de dados para manipulação de uma Lista Simplesmente Encadeada. A Lista deve ser capaz de manipular dados do tipo int.
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

//====================================================================================//
### EX24: IMPLEMENTAÇÃO LISTA SIMPLESMENTE ENCADEADA CIRCULAR
### *REQUISITOS:*
- Crie um tipo abstrato de dados para manipulação da Lista Simplesmente Encadeada Circular.
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

//==========================================================================================//
### EX25: IMPLEMENTAÇÃO LISTA DUPLAMENTE ENCADEADA
### *REQUISITOS:*
- Crie um tipo abstrato de dados para manipulação de uma Lista Duplamente Encadeada. A Lista deve ser capaz de manipular dados do tipo char.
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

//==========================================================================================//
### EX26: IMPLEMENTAÇÃO LISTRA DUPLAMENTE ENCADEADA CIRCULAR
### *REQUISITOS:*
- Crie um tipo abstrato de dados para manipulação da Lista Duplamente Encadeada Circular.
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

//=======================================================================================================//
