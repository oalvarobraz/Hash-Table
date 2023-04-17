# Hash-Table-in-Disk

## Implementação
Esta implementação é baseada em uma tabela hash em disco, onde a tabela é mantida em um arquivo binário no disco e as operações são realizadas lendo e escrevendo nos registros deste arquivo. 

### Encadeamento Exterior
O encadeamento externo é uma técnica de resolução de colisões em uma tabela hash, que consiste em manter uma lista encadeada para cada posição da tabela hash. Quando ocorre uma colisão, ou seja, quando dois ou mais elementos são mapeados para a mesma posição da tabela, esses elementos são inseridos em uma lista encadeada associada a essa posição.

### Função Hash
Nessa implementação foi utilizada o mod em relação ao tamanho da tabela, que inicialmente é escolhido pelo usuário.

```
int hash(int codigo, int tam){
    return codigo % tam;
}
```
### Estrutura dos dados
Para implementar a tabela hash em disco, são usados dois arquivos no disco: um arquivo que armazena os dados dos funcionários, e um arquivo que armazena os índices da tabela hash. 
Cada funcionário e cada compartimento são representados por uma estrutura de dados.

### Menu
O código possui um menu com opções para inserção, busca e remoção de funcionários na tabela hash. Também é possível buscar funcionários aleatoriamente.

## Tecnologias Utilizadas
C

## Autor
Esta implementação da Árvore B em disco foi desenvolvida por oalvarobraz

## Licença
Este projeto está licenciado sob a Licença MIT. Leia o arquivo LICENSE para obter mais informações.
