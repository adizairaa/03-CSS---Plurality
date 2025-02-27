# 🗳️ Simulador de Eleição

Este programa em C permite a realização de uma eleição simples, onde os eleitores podem votar em candidatos e o vencedor (ou vencedores, em caso de empate) é exibido ao final. 

## 📌 Funcionalidades
- ✅ Registra candidatos automaticamente com base nos argumentos de entrada.  
- ✅ Permite que os eleitores votem digitando o nome do candidato.  
- ✅ Valida os votos para garantir que sejam de candidatos existentes.  
- ✅ Conta os votos e determina o(s) vencedor(es).  

## 📥 Como Compilar e Executar  

1. Compile o código usando o `clang` ou `gcc`:  
   ```sh
   clang -o eleicao eleicao.c -lcs50
   ```  
   ou  
   ```sh
   gcc -o eleicao eleicao.c -lcs50
   ```  
   
2. Execute o programa com pelo menos dois candidatos:  
   ```sh
   ./eleicao Alice Bob Charlie
   ```  
   
3. Insira o número de eleitores e registre os votos digitando os nomes dos candidatos.  

4. O(s) vencedor(es) será(ão) exibido(s) ao final! 🎉  

## 📖 Exemplo de Uso  
```sh
$ ./eleicao Alice Bob  
NUMERO DE ELEITORES: 3  
VOTO: Adila 
VOTO: João  
VOTO: Adila  
RESULTADO Adila 🎉  
```

## ⚠️ Regras e Limitações
- Deve haver pelo menos **dois candidatos**.  
- O número máximo de candidatos permitidos é **9**.  
- Votos inválidos não são contados.  

## 🛠️ Estrutura do Código  
O código se baseia nos seguintes componentes:  

- `vote()`: Verifica se o voto é válido e adiciona à contagem do candidato.  
- `print_winner()`: Determina e exibe o vencedor da eleição.  

## 📜 Licença  
Este projeto é de código aberto e pode ser modificado e distribuído livremente.  

---
## REDME CREADO POR IA
