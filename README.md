# Sistema de Votação em C

## Descrição
Este programa implementa um sistema de votação simples em C, permitindo que um grupo de eleitores vote em um conjunto de candidatos especificado na linha de comando. O programa conta os votos e exibe o(s) candidato(s) vencedor(es).

## Funcionalidades
- Registrar candidatos a partir dos argumentos da linha de comando.
- Permitir que os eleitores votem digitando o nome do candidato.
- Verificar se um voto é válido.
- Contar os votos de cada candidato.
- Exibir o(s) candidato(s) vencedor(es).

## Estrutura do Código
O programa utiliza:
- Uma estrutura (`struct`) para armazenar os nomes dos candidatos e suas respectivas contagens de votos.
- Um array de candidatos com um limite máximo de 9 candidatos.
- Funções para registrar votos e imprimir o vencedor.

## Como Usar
### Compilar o programa:
```sh
clang -o votacao votacao.c -lcs50
```

### Executar o programa:
```sh
./votacao candidato1 candidato2 candidato3
```
Exemplo:
```sh
./votacao Alice Bob Charlie
```

### Inserir o número de eleitores e votar:
O programa pedirá o número de eleitores e, em seguida, permitirá que cada eleitor insira um nome de candidato.
```sh
NUMERO DE ELEITORES: 3
VOTO: Adila
VOTO: João 
VOTO: Adila
```

### Exibir o vencedor:
O programa imprimirá o(s) vencedor(es) da votação.
```sh
RESULTADO Adila
```

## Requisitos
- Biblioteca CS50 instalada.
- Compilador C (como Clang ou GCC).

## Autor
Este programa foi desenvolvido para fins educacionais como parte de um exercício em C.

## Licença
Este projeto está sob a licença MIT. Sinta-se à vontade para modificá-lo e distribuí-lo.

