Descrição - Atividade 1:
Crie uma aplicação capaz de identificar a faixa etária com base na idade informada pelo
usuário. Considere os seguintes critérios:
Se a idade informada for maior ou igual a 0 e menor que 15, exibir a mensagem “Criança”.
Se a idade informada for maior ou igual a 15 e menor que 30, exibir a mensagem “Jovem”.
Se a idade informada for maior ou igual a 30 e menor que 60, exibir a mensagem “Adulto”.
Se a idade informada for maior ou igual a 60, exibir a mensagem “Idoso”.
Fique à vontade para utilizar qualquer uma das funções aprendidas para exibição de dados
para o usuário. 

Descrição - Atividade 2:
Crie uma aplicação para efetuar o cálculo do índice de massa corporal.
Considere os seguintes critérios:
1) Ao executar o script a aplicação deve solicitar a entrada do nome da pessoa.
2) Na sequência a aplicação deve solicitar que seja informada a altura da pessoa em
centímetros.
3) Na sequência a aplicação deve solicitar que seja informado o peso da pessoa.
4) Após as estradas de dados, atente-se a conversão das informações para dados do tipo
float.
5) Converta a altura recebida em centímetros para metros. (basta dividir a altura por
100).
6) Internamente a aplicação deve executar o cálculo do índice de massa corporal através
da expressão: M = peso (quilos) ÷ altura²
7) Após identificar o índice de massa corporal o sistema deverá classificar em faixas
descritivas utilizando os critérios abaixo:
a) Se M estiver abaixo de 16 : Baixo peso muito grave
b) Se M estiver entre 16 e 16,99: Baixo peso grave
c) Se M estiver entre 17 e 18,49: Baixo peso
d) Se M estiver entre 18,50 e 24,99: Peso normal
e) Se M estiver entre 25 e 29,99: Sobrepeso
f) Se M estiver entre 30 e 34,99: Obesidade grau I
g) Se M estiver entre 35 e 39,99: Obesidade grau II
h) Se M for maior que 40: Obesidade grau III
8) Ao término o sistema deve fornecer a seguinte saída para o usuário:
“<Nome> possui índice de massa corporal igual a <m>, sendo classificado como:
<classificacao>.”
*As informações em vermelho são variáveis e devem ser substituídas pelos seus respectivos
valores calculadas dentro da aplicação. 

Descrição - Atividade 3:
Crie uma aplicação para efetuar cálculo aritméticos de soma e subtração.
Considere os seguintes critérios:
1) Ao executar o script a aplicação deve solicitar a entrada de um número, seguido de
uma operação de soma ou subtração e posteriormente seguido de um segundo
número.
2) A operação deve ser inserida pelo usuário de forma textual, ou seja, quando o sistema
solicita a operação o usuário deve informar o texto ‘soma’ ou ‘subtração’ (sem as
aspas).
3) Na sequência o sistema deve enviar os parâmetros para uma função efetuar o devido
cálculo. Exemplo: calculo(num1, num2, operacao).
4) A função deve executar o cálculo com base na operação informada pelo usuário e na
sequência deve retornar o valor encontrado.
5) Ao término o sistema deve fornecer a seguinte saída para o usuário:
“O resultado é: <resultado>.”
*A informação em vermelho é uma variável e deve ser substituída pelo seu respectivo valor
calculada dentro da aplicação.

Descrição - Atividade 4:
Crie uma aplicação para efetuar cálculo aritméticos de soma e subtração.
Considere os seguintes critérios:
1) Ao executar o script a aplicação deve solicitar a entrada de um número, seguido de
uma operação de soma ou subtração e posteriormente seguido de um segundo
número.
2) A operação deve ser inserida pelo usuário de forma textual, ou seja, quando o sistema
solicita a operação o usuário deve informar o texto ‘soma’ ou ‘subtração’ (sem as
aspas).
3) Na sequência o sistema deve enviar os parâmetros para uma função efetuar o devido
cálculo. Exemplo: calculo(num1, num2, operacao).
4) A função deve executar o cálculo com base na operação informada pelo usuário e na
sequência deve retornar o valor encontrado.
5) Ao término o sistema deve fornecer a seguinte saída para o usuário:
“O resultado é: <resultado>.”
*A informação em vermelho é uma variável e deve ser substituída pelo seu respectivo valor
calculada dentro da aplicação.

Descrição - Atividade 5:
Crie uma aplicação web contendo um campo para entrada de texto (input text) e dois
botões (buttons), sendo um botão com a descrição "Adicionar" e outro com a descrição
"Ordenar".
Após criar os elementos de interação com o usuário acima, crie um Array de nome objetos contendo
os seguintes valores:
var objetos = Array('Cadeira', 'Impressora', 'Garfo')
Os próximos passos são:
A) Ao clicar no botão "Adicionar" disparar função que irá:
• Recuperar o valor contido no campo de texto.
• Verificar se o valor está vazio ou preenchido.
o Se vazio, exibir alert com a mensagem "Informe um valor válido".
o Se preenchido:
▪ Verificar se o valor informado já existe dentro do Array objetos.
▪ Se existir, exibir alert com a mensagem "Objeto já foi adicionado".
▪ Se não existir:
• Incluir o valor preenchido no campo dentro do Array.
• Efetuar um console.log do Array para debug (checar se está
funcionado).
• Limpar o valor contido no campo de entrada de texto.
B) Ao clicar no botão "Ordenar" disparar função que irá:
• Ordenar de forma alfabética os valores do Array de objetos.
• Efetuar um console.log do Array para debug (checar se está funcionado).

Descrição - Atividade 6:
1) Baseado no exemplo da aula "Praticando um pouco - Percorrendo e listando itens de
Arrays", implemente a mesma solução, porém utilizando o comando for.
2) Baseado no exemplo da aula "Praticando um pouco - Criando uma tabuada de 1 a 10
(laços encadeados)", implemente a mesma solução, porém utilizando o comando while.
