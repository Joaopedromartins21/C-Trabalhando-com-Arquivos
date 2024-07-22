Projeto Desenvolvido na Plataforma Alura

Começamos criando um file stream por meio do Open e conseguimos ler nosso arquivo, criando o buffer e o passando ao método Read. Inclusive, tivemos toda a preocupação com os intervalos que esse método pode usar para gravar os dados do buffer.

De início, visualizamos apenas os bytes, o que não era muito útil para nós.
Então, partimos para a decodificação desses dados para exibir um texto.
Para realizar essa conversão, trabalhamos com a classe Encoding.
Conhecemos o Unicode, o conceito de code point e nos aprofundamos nos formatos de transformação, como UTF-8 e UTF-32. Com o método GetString, conseguimos converter a cadeia de bytes para string.

Mais adiante, aprendemos sobre o StreamReader, para que não tenhamos que nos preocupar sempre com o buffer, seus intervalos e o Encoding.
Exploramos como ler linhas e mostrar mensagens no console referentes ao conteúdo do arquivo, desenvolvendo um código para converter strings em ContaCorrente.
Nesse processo, utilizamos o Parse para transformar strings em números inteiros e double, e também usamos o método Replace.
Assim, conseguimos trazer o conteúdo do arquivo para dentro do nosso código e mostrá-lo no console.

Depois, exploramos como criar arquivos e inserir informações neles, utilizando o FileMode.Create. Desenvolvemos o método CriarArquivo empregando o GetBytes, semelhante ao GetString. Também aprendemos sobre o funcionamento de arquivos binários e como eles podem nos ajudar a otimizar o uso de memória do computador. Descobrimos como fazer tanto a escrita quanto a leitura de arquivos binários, com BinaryWriter e BinaryReader. Desse modo, pudemos mostrar as informações do arquivo binário no nosso console de forma legível para nós.

Por fim, exploramos o stream do console. Armazenamos os dados inseridos pelo usuário em arquivos, usando o OpenStandardInput. Ademais, também aprendemos sobre o método Flush, responsável por despejar diretamente no stream.
