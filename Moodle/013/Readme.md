# TAD Matriz

![](figura.jpg)

O objetivo desta atividade é implementar um TAD chamado **Matriz** usando obrigatoriamente Programação Orientada a Objetos. O TAD **Matriz** encapsula uma matriz com m linhas e n colunas, sobre a qual podemos fazer as seguintes operações:

- criar matriz com m linhas e n colunas, alocada dinamicamente e com todos os elementos iguais a zero
- liberar(deletar) a matriz que foi alocada dinamicamente
- acessar valor na posição (i,j) da matriz
- atribuir valor ao elemento na posição (i,j) da matriz
- retornar o número de linhas da matriz
- retornar o número de colunas da matriz
- imprimir a matriz
- multiplicar a matriz atual por uma matriz passada por parâmetro e retornar a matriz resultante
- somar a matriz atual com uma matriz passada por parâmetro e retornar a matriz resultante

---
## Observações
***Lembre-se de que nem sempre é possível multiplicar ou somar duas matrizes:**
- Para que a soma dê certo, as duas matrizes precisam ter as mesmas dimensões
- Para que a multiplicação dê certo, o número de colunas da primeira matriz deve ser igual ao número de linhas da segunda. 


## Requisitos

- O código do TAD **Matriz** deve ser dividido em dois arquivos: *Matriz.h* e *Matriz.cpp* como explicado em sala. O código do arquivo *Matriz.h* já foi escrito e pode ser encontrado em anexo logo acima nesta atividade, na pasta **projeto**. Você precisa apenas implementar as funções-membro da classe **Matriz** no arquivo *Matriz.cpp*, que está incompleto.

- Além disso, assim como no exercício do TAD Circle, o código do programa *main.cpp* já está feito. O programa principal lê comandos passados como entrada e manipula uma ou mais matrizes. Os comandos aceitos pelo menu principal estão listados abaixo.

### Comandos do programa principal

| Comando | Significado |
| --- | --- |
| `creatematrix l c ` | Instancia um objeto da Classe Matriz com l linhas e c colunas. Lê os l x c valores e inicializa o objeto matriz |
| `exit` | Sai do programa liberando todos os objetos criados |
| `printmatrix k` | Imprime a (k+1)-ésima matriz criada |
| `nlinhas k` | Imprime o número de linhas da (k+1)-ésima matriz criada |
| `ncolunas k` | Imprime o número de linhas da (k+1)-ésima matriz criada |
| `getvalor i j k` | Imprime o valor contido na posição (i,j) da (k+1)-ésima matriz criada |
| `sum p q` | Soma a (p+1)-ésima matriz com a (q+1)-ésima matriz e imprime a matriz resultante na tela. |
| `multiply p q` | Multiplica a (p+1)-ésima matriz com a (q+1)-ésima matriz e imprime a matriz resultante na tela. |

---
### Exemplo de Entrada

creatematrix 5 5
0 2 0 3 1 9 -8 23 0 1 -33 87 2 6 7 0 1 4 0 9 0 3 0 1 3
nlinhas 0
ncolunas 0
printmatrix 0
exit

### Exemplo de Saída

linhas: 5
colunas: 5
      0      2      0      3      1
      9     -8     23      0      1
    -33     87      2      6      7
      0      1      4      0      9
      0      3      0      1      3
matriz liberada
      
---
## Esqueleto

Acima desta atividade, você encontra uma pasta chamada **projeto** contendo um esqueleto da atividade.  Baixe todo esse projeto no seu computador. Não mexa no arquivo main.cpp pois ele já está pronto para uso. O único arquivo que você deve completar para finalizar esta atividade é o arquivo **Matriz.cpp**.

