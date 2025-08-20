# Módulo 1 - Lição 1.1 - Introduzindo Python
Ao iniciar os estudos em Pyhton e em programação, especialmente quando temos pouca familiariedade com computadores e sistemas de tecnologia atuais,
algumas dúvidas podem surgir.<br><br>
_O que é Python?_<br>
_O que é uma variável?_<br>
_O que são tipos de dados?_<br>
<br> Para responder a essas e outras perguntas, continue sua leitura abaixo.

## Python, linguagens de programação e computadores
Diferentemente de nós, computadores não conseguem compreender instruções complexas - precisam, porém, de instruções claras, precisas, comunicadas em 
ordem pré-definida de modo a serem transmitidas sem ambiguidade: as linguagens de programação.<br>

<br>No caso da linguagem _Python_ - a qual, assim como qualquer língua humana, possui regras de sintaxe bem definidas - interagimos com o computador,
nos casos mais comuns e mais simples, da seguinte forma:<br>

1. Criamos um _arquivo de código Python_, com operações adequadas à sintaxe da linguagem.
2. Passamos o arquivo de código que criamos para o _intepretador Python_.
3. O interpretador percorre o arquivo de código de cima para baixo, da esquerda para a direita.
4. Ele 'traduz' sob demanda o código no arquivo para uma 'linguagem-pai', ou código binário (a depender do interpretador).
5. O código é executado, e ao chegar ao fim, o programa é encerrado, e os recursos utilizados por ele são disponibilizados novamente para o sistema
   operacional.<br>

<br>Vamos percorrer esses passos com código escrito em Python.

## Dados em constante movimento
> [!IMPORTANT]
> Para acompanhar e por em prática os conceitos aqui apresentados, é recomendável que você tenha o interpretador Python e uma IDE (ou editor de texto
> e/ou código de sua preferência) instalados no seu dispositivo.<br>
> Para informações sobre como obter esses componentes, acesse o guia de configuração do ambiente de desenvolvimento.

Para começar nosso aprendizado, vamos criar um arquivo de código Python, acessando a opção 'Arquivo' (_File_) -> 'Novo' (_New_) na sua IDE/editor de
código, ou através do gerenciador de arquivos do seu sistema operacional.<br>
Crie um novo arquivo (com qualquer nome que desejar) cuja extensão (final do arquivo) seja _.py_.
> [!TIP]
> Assim como arquivos de texto do Word terminam em _.docx_ e arquivos do PowerPoint como _.pptx_, arquivos de código Python terminam em _.py_, o que
> indica para o sistema operacional e para o editor de código/IDE que aquele é um arquivo de código Python.

Aqui, usarei um arquivo nomeado como _ola_mundo.py_.<br>
Em nosso arquivo, atualmente desprovido de conteúdo, digitaremos o seguinte:<br>
```python
# Arquivo: ola_mundo.py
print("Olá, mundo!")
```
<br>**Note duas coisas:**
* A linha iniciada em # recebe a cor acinzentada para demonstrar que não faz parte do código:
  > Qualquer linha iniciada em `#` (ou qualquer texto após `#`), em Python, define um _**comentário**_.<br>
  > **Comentários são ignorados** pelo interpretador, ou seja, do início de um comentário (marcado pelo `#`) até o fim daquela linha, tudo é desconsiderado.<br>
  > Veremos mais sobre comentários, sua importância na documentação de software e as melhores práticas associadas a eles futuramente.
* A palavra `print` e a frase `"Olá, mundo!"` recebem cores diferenciadas:
  > Em editores de código ou IDEs, as palavras contidas no arquivo são colorizadas de acordo com sua classificação na linguagem.<br>
  > `print` é uma palavra reservada da linguagem Python; a essas palavras, chamamos _keywords_.<br>
  > `"Olá, mundo!"` é uma _string_, um tipo de dado na linguagem que denota uma sequência de caracteres.

> [!TIP]
> Não se preocupe com o alto fluxo de informações ou com a incompreensão delas no momento; essa é apenas uma visão geral do que abordaremos.<br>
> Todos esses tópicos serão explorados em maior detalhe a seguir.

Agora que a _semente do desespero_ quer começar a brotar, vamos expandir as definições dessas duas linhas de código inocentes.

## Olá desespero, adeus mundo
Cumprimos o primeiro passo da nossa (pequena e simplificada) lista de passos para a interação de um código em Python com o computador:
- [x] Criamos um _arquivo de código Python_, com operações adequadas à sintaxe da linguagem.

_Mas_...ainda não aprendemos nada substancial.<br>
Vamos dissecar a estrutura desse pequeno programa.<br>
Aqui está ele novamente:
```python
# Arquivo: ola_mundo.py
print("Olá, mundo!")
```
### Comentários
Na primeira linha, `# Arquivo: ola_mundo.py`, temos um _comentário_.<br><br>
Como dito antes, um comentário se estende desde o `#` até o fim da linha; eles são completamente ignorados pelo interpretador, e por isso, é seguro escrever
em linguagem humana neles (ou chorar em forma de versos, quem sabe.)<br>
Nesse caso, o comentário foi feito apenas para ajudar o leitor a 'se situar', informando o arquivo ao qual esse código pertence. Porém, no desenvolvimento de
software do 'mundo real', comentários são essenciais para manter o software mais legível, auto-documentável e escalável.<br><br>
Por isso, teremos uma lição dedicada apenas a eles.<br>
Por enquanto, saiba que são ferramentas importantes no mundo da programação, que se estendem do `#` ao fim
da linha e são ignorados pelo interpretador.

### _Keywords_: palavras reservadas
Python tem uma sintaxe definida, contando com palavras especiais que denotam algum tipo de significado específico para o interpretador da linguagem.<br>
Para garantir que nenhum programador use essas palavras como identificadores de algo (veremos mais à frente sobre), essas palavras são _reservadas_
pelo interpretador: se alguém tentar usá-las como identificadores, o interpretador gera um erro e o programa não é executado.<br><br>
`print`, na segunda e última linha, é uma _keyword_, uma palavra reservada em Python, que nesse caso denota uma _função_ da linguagem, tópico também
abordado futuramente.<br>
O fato de `print` ser uma keyword nos leva à última adição de informação dessa lição: introduzir as _variáveis_ e os _literais_.

### Variáveis
Apesar de abordar mais clara e amplamente cada um dos tópicos abordados aqui em lições futuras, vale a pena olhar brevemente para as variáveis.<br>
E _não_, ao leitor curioso: não há nenhuma variável nesse arquivo.<br><br>
Variáveis são, primariamente, modos de _identificar_ um 'instrumento' que armazena dados ou é uma referência a determinados dados.<br>
Nesse arquivo, apesar de não haver variáveis, temos um _literal_: `"Olá, mundo!"`, um valor não associado a variáveis ou constantes, como um 'valor
avulso', solto. Se uma variável identifica um instrumento que pode armazenar dados, o literal é constituído apenas pelos dados.

## A peça que faltava
Após ser bombardeado com informações, você pode estar se perguntando:
> 'Não vamos fazer nada com o código?'

O fato é que nosso pequeno arquivo de código Python não serve apenas como nosso objeto de estudo: ele é um programa completo.<br><br>
Assim sendo, vamos executá-lo.<br>
Se você estiver usando a IDE VSCode ou qualquer editor de código com suporte à linguagem Python, é provável que haja um botão 'Executar' (_Run_),
que quando clicado, com o arquivo aberto, irá executar seu código.
> [!NOTE]
> Se você não estiver conseguindo executar o programa, acesse o guia de configuração do ambiente de desenvolvimento e certifique-se de que seguiu
> todas as instruções de modo correto.<br>
> Se ainda assim tiver problemas, verifique a [seção de dúvidas](https://github.com/Neblinus/BioPython/discussions/categories/q-a-perguntas-e-respostas)
> da comunidade por questões pertinentes ao seu problema: é provável que alguém já tenha enfrentado esse problema e sido ajudado por um membro do repositório.
> <br>Se não houver nenhum tópico semelhante, crie uma questão.

Se tudo der certo, você deve ver a frase `Olá, mundo!` exibida na sua tela.<br>

### Mas e a lista de passos?
Até a execução do nosso programa, só havíamos completado o primeiro passo da lista.<br>
Agora, ela está assim:
- [x] Criamos um _arquivo de código Python_, com operações adequadas à sintaxe da linguagem.
- [x] Passamos o arquivo de código que criamos para o _intepretador Python_.
- [x] O interpretador percorre o arquivo de código de cima para baixo, da esquerda para a direita.
- [x] Ele 'traduz' sob demanda o código no arquivo para uma 'linguagem-pai', ou código binário (a depender do interpretador).
- [x] O código é executado, e ao chegar ao fim, o programa é encerrado, e os recursos utilizados por ele são disponibilizados novamente para o sistema
   operacional.

Como isso ocorreu e as minúcias dessas etapas são dúvidas a serem sanadas no decorrer das aulas desse repositório.<br><br>
Por agora, dê-se por satisfeito:<br>
Você acaba de executar seu primeiro programa em Python.
