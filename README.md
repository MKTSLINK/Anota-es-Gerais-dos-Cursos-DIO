# Anotações-Gerais-dos-Cursos-DIO
Todas as anotações que achei importantes sobre o aprendizado Inicial em TI.

"CÓDIGO DE PROGRAMAÇÃO"

*Algoritmo - sequencia de passos que resolve um problema.

"Link útil 01 - jogo Minecraft"

https://studio.code.org/s/mc/stage/1/puzzle/1

*Pseudocódigos - É uma forma genérica de escrever um algoritmo, utilizando uma linguagem simples (Nativa, ou seja, em português a quem escreve, de forma a ser entendida por qualquer pessoa).

"Link útil 02"

https://www.proprofs.com;games/wolf-sheep-and-cabbage/

-Desafio: Resolver todos os desafios do 1º site em menos de 1 hora.

"Link útil 03"

https://rachacuca.com.br/jogos/pinguins-numa-fria

*Concatenação - É um termo usado em computação para designar a operação de "unir" o conteúdo de duas Strigs.

*Strigs - É uma sequencia de caracteres.

*Fluxograma - é uma ferramenta utilizada para representar graficamente o algoritmo, isto é, a sequencia lógica e coerente do fluxo de dados.

"Link útil 04"

https://www.flowgorithm.org

"INTRODUÇÃO AO PORTUGOL"

*Estrutura de Repetição - Dentro da Lógica de Programação é uma estrutura que permite executar mais de uma vez o mesmo comando ou conjunto de comandos, de acordo com uma condição ou com um contador.

*Exemplo de comando para tabuada do 9*

" 9 * & numero & " = " & 9 * numero

​				      	Principal

​				        		:arrow_down_small:

​        	Declarar (Número / Limite)

​		        				:arrow_down_small:

Atribuir (Variavel =Número :arrow_right: :Expressão = 0

​                                :arrow_down_small:

Atribuir (Variavel =Limite :arrow_right: Expressão =  10

​		                        :arrow_down_small:

Enquanto (Número < = Limite)  	:arrow_forward:			Saida

​	                                                                       	:arrow_down_small:

​														Atribuir (Variavel =Número)

​														    Expressão = Número +1

*Linguagem de Programação - é uma linguagem escrita e formal que especifica um conjunto de instruções e regras usadas para gerar programas (Software).

Um software pode ser desenvolvido para rodar em um computador, dispositivo móvel ou em qualquer equipamento que permita sua execução.

"Existem dois tipos de linguagens de Programação"

-Linguagem de Alto Nível: São aquelas que a sintaxe se aproxima mais da nossa linguagem e se distanciam mais da linguagem de maquina.

-Linguagem de Baixo Nível: É aquela que se aproxima mais da linguagem de Maquina.

Essas são as que você precisa ter um conhecimento direto da arquitetura do computador para fazer alguma coisa.



"Oque é Portugol ?"

É uma pseudolinguagem que permite ao leitor desenvolver algoritmos estruturados em Português de forma simples e intuitiva, independentemente de Linguagem de Programação.

"LAÇOS DE REPETIÇÃO NO PORTUGOL"

Exemplo de laços de Repetição

Programa

{

Função Inicio()            Variavel

{                                          :arrow_down_small:

Inteiro           Contador, limite, Resultado

Contador = 0

Limite = 10

Faca{

Resultado = 9 * contador

Escreva("9 x " + contador + " = " + Resultado + "\n" )

Contador ++

} Enquanto (contador < = Limite)



*Estrutura de Dados - É uma estrutura organizada de dados na memoria de um computador ou qualquer dispositivo de armazenamento, de forma que os dados possam ser utilizados corretamente.

"Principais Estruturas de Dados"

- Vetores e Matrizes
- Registro
- Lista
- Pilha
- Fila
- Árvore 
- Tabela Hash
- Grafos

*Vetores e Matrizes (Arrays)

*Matriz - É uma coleção de variáveis de mesmo tipo, Acessíveis com um único nome e armazenadas contiguamente na memoria (Array Multi - Direcional)

obs: Contiguamente = em sequencia

"A individualização de cada Variável de um Vetor é feita através do uso de Índices"

*Vetores - São Matrizes de uma só Dimensão (Array Uni - Direcional)

obs: O Índice sempre deve começar pelo Zero "0" e sempre entre colchetes - [0].

*Registro - É uma estrutura que fornece um formato especializado para armazenar informações em memoria

- Toda Estrutura de Registro tem um nome (Ex: Livro), e seus campos podem ser acessados por meio do uso do operador Ponto (.). Por Exemplo, para acessar o preço de um livro, poderíamos utilizar a seguinte Operação:

  Livro.Preço

*Listas - Estruturas de dados do tipo Lista, Armazena dados de um determinado tipo em uma ordem Especifica.

A diferença entre Lista e Arrays é que as Listas possuem tamanho Ajustável, enquanto Arrays possuem tamanho FIxo.

"Existem dois tipos de Listas"

-Ligadas

-Duplamente Ligadas

*Pilhas - Estruturas de dados que serve como uma coleção de elementos, e permite o acesso a somente um item de dados armazenado. O acesso aos itens é restrito, somente um item pode ser lido ou removido por vez.

"Existem dois tipos de Pilhas"

-Lifo ou UEPS - Estrutura do tipo Pilha Lifo (Last In First Out) ou UEPS (Ultimo que Entra Primeiro que Sai), apresenta o seguinte critério: O primeiro Elemento a ser retirado é o Ultimo que tiver sido Inserido.

-Fifo ou PEPS - Estrutura do tipo Pilha Fifo (First In Firts Out) ou PEPS (Primeiro que entra Primeiro que Sai), apresenta o seguinte critério: O primeiro Elemento a ser retirado é o primeiro que tiver sido Inserido.

*Filas - A estrutura do tipo Fila admite remoções de elementos e inserção de novos, sujeita à seguinte regra de operação: O elemento removido é o que está na estrutura há mais tempo ou seja, O primeiro Objeto inserido na fila é também o primeiro a ser removido seguindo o conceito FIFO.

*Árvores - é uma estrutura de dados que organiza seus Elementos de forma hierárquica, onde existe um elemento que fica no Topo da árvore, chamado de Raiz e existem os elementos subordinados a ele, que são chamados de Nós ou Folhas.

*Tabela Hash - Uma tabela de dispersão ou espelhamento é uma estrutura de dados especial, que associa chaves de pesquisa a valores.

Uma Tabela Hash é uma generalização da ideia de Array, porém utiliza uma função denominada Hashing para espalhar os elementos, fazendo com que os mesmos fiquem de forma não ordenada dentro do Array que define a tabela.

A Tabela Hash permite a associação de Valores a Chaves.

"Valores é a posição ou índice onde o elemento se encontra."

"Chave é a parte da informação que compõe o elemento a ser manipulado."

Espalhar facilita a busca na estrutura de dados, pois a partir de uma chave podemos acessar de forma rápida uma posição do Array.

*Grafos - São estruturas que permitem programar a relação entre objetos.

Os Objetos são Vértices ou Nós do Grafo.

Os relacionamentos são Arestas.

"INTRODUÇÃO AO GIT / GITHUB"

"Navegação Básica no terminal e Instalação"

---Códigos Básicos---

* Dir - Listar os Diretórios
* CD/ - Navegar dentro do S.O (Sistema Operacional)
* CD.. - Voltar a tela na navegação
* CLEAR - Limpar o terminal (clear screen)
* Tecla TAB - Atalho do teclado, auto-preenchimento
* MKDIR - Criar uma pasta (Make DIrectóry)
* RMDIR - Remover Diretório (Remove Directóry)
* DEL - Remove pastas dentro do diretório
* LS - Listar pastas dentro do diretório
* ECHO - Usado para replicar o comando no terminal
* LS -A - Listar Arquivos Ocultos
* GIT STATUS - Verifica a condição do arquivo 
* GIT ADD - Move os arquivos do diretório de arquivos para a área de Standing
* GIT COMMIT "Mensagem" - Move os Arquivos da Área de Standing para dentro do Repositório



"SHA1 - Conjunto de 40 caracteres criado para identificar um arquivo (Impressão Digital do Arquivo)"

--Editor de Texto - TYPORA --

