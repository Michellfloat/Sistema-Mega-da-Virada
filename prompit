function gerarNumeros(qJogos, qNumeros){//função para gerar números usando 2 variáveis
    const meuJogo = []//array para armazenar o jogo completo//
    while (meuJogo.length < qJogos) {//enquanto o que tiver no array for menor que qJogos o repetidor 'while' continuará a ser executado
       const numeros = new Set()//números irá receber um novo set de valores(quase como um armazenador)//
       let num
        while(numeros.size<qNumeros) {
            numeros.add(Math.floor(Math.random() * 60 + 1))
            num = Array.from(numeros)

        }
        num.sort((a,b) => a- b)//ordenado em ordem crescente!!!
        meuJogo.push(num)
        
    }
    console.log(meuJogo)
}

gerarNumeros(6,5)

/* 
    1. Reorganizar em ordem crescente
    2. Remover duplicatas
    3. Adicionar a possibilidade de escolher a quantidade de números
    4. Usar a função while
*/

/*Código para uso geral 👍*/
