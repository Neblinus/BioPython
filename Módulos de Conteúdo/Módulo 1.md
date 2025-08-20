# Módulo 1 - Definindo Python, Variáveis e Tipos de Dados
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
<br>**Note três coisas:**
* A primeira linha, que começa com #, está com uma cor acinzentada.
  > Isso ocorre porquê, em Python, toda linha começada com # denota um **_comentário_**:<br>
  > Um trecho de texto que o criador daquele código ou seu mantenedor deixa para os próximos usuários do código e para si mesmo para facilitar a copreensão
  > do código ou realizar notas sobre o mesmo. Nesse caso, o comentário indica o nome do arquivo, para ajudar o leitor a se 'localizar'.
* A linha iniciada em # recebe a cor acinzentada para demonstrar seu caráter 'secundário' (_por enquanto_):
  > **Comentários são ignorados** pelo interpretador, ou seja, do início de um comentário (marcado pelo #) até o fim daquela linha, tudo é desconsiderado.<br>
  > Veremos mais sobre comentários, sua importância na documentação de software e as melhores práticas associadas a eles futuramente.
* A palavra `print` e a frase `"Olá, mundo!"` recebem cores diferenciadas:
  > Em editores de código ou IDEs, as palavras contidas no arquivo são colorizadas de acordo com sua classificação na linguagem.<br>
  > `print` é uma palavra reservada da linguagem Python; a essas palavras, chamamos _keywords_.<br>
  > `"Olá, mundo!"` é uma _string_, um tipo de dado na linguagem que denota uma sequência de caracteres.

> [!TIP]
> Não se preocupe com o alto fluxo de informações ou com a incompreensão delas no momento; essa é apenas uma visão geral do que abordaremos.<br>
> Todos esses tópicos serão explorados em maior detalhe a seguir.

