# Módulo 1 - Lição 1.2 - Literais, Tipos de Dados e Variáveis
Na última lição, tivemos um breve primeiro contato com a linguagem _Python_, explorando superficialmente alguns detalhes
sobre ela.

Mas se você saiu da última lição com a sensação de que não aprendeu nada, fique tranquilo:<br>
Você terá _inúmeros aprendizados_ nessa lição.

Prepare-se.<br>
Cabeças podem <s>rolar</s> se confundir ;)

## Literais
Vamos revisitar o programa da última lição rapidamente:

```python
# Arquivo: ola_mundo.py
print("Olá, mundo!")
```

Se você bem se recorda, esse programa apenas imprime (ou _exibe_, de certa forma, para simplificar) o texto `Olá, mundo!` na saída do
console, parecendo, desse modo, pouco útil para nós.

Mas nas entrelinhas desse código tão simples, teremos nosso primeiro aprendizado efetivo:<br>
Compreenderemos o que são os _literais_.

### Literais por toda a parte
Olhe mais atentamente para o código do programa, especificamente, a única linha a ser executada (lembre-se que linhas iniciadas em 
`#` são _comentários_ e são ignoradas pelo interpretador Python):<br>

```python
# Arquivo: ola_mundo.py
print("Olá, mundo!")
```

Mesmo sem ainda termos elucidado algumas questões - tais como _'O que exatamente é `print`?_ - podemos notar que _print_, do inglês
'imprimir' é o que faz a frase ser exibida na tela (mesmo que _como_ ele o faz ainda pareça um mistério).<br>
Mas, se tudo em programação é composto de código, magia negra e termos ininteligíveis, o que é `"Olá, mundo!"`?

Essa pequena frase entre aspas duplas é um **_literal_**.<br>
Em programação, um **_literal_** é qualquer valor 'puro' diretamente escrito no código-fonte.

No nosso simples programa, temos apenas um literal: `"Olá, mundo!"` - um valor diretamente escrito no código-fonte.

### Alterando com literais, literalmente
Sabemos teoricamente o que é um literal, então, que tal abranger mais esse conceito e explorar suas implicações na prática?<br>
Abra o arquivo `ola_mundo.py` que temos usado até aqui e tente substituir o literal `"Olá, mundo!"` por outro literal qualquer.

Sim, exatamente isso que passou pela sua mente: _como assim?_<br>
Acalme-se, jovem.

Apenas delete o literal e coloque outro no lugar.<br>
Uma frase, um número, o que desejar: apenas digite o que quiser, e veja as mudanças provocadas por essa alteração quando executar o
programa.

> [!TIP]
> Caso você não se recorde:<br>
> Para executar um programa através de IDEs populares, basta localizar o botão _Executar_ ou _Run_.<br>
> Para executar um programa através da linha de comando, basta digitar `python3 <nome_do_arquivo>` e apertar _Enter_.

A depender do que você inseriu, o literal terá sido exibido, _impresso_ na tela.<br>
Ou você será agraciado com uma mensagem de erro.

Em caso de erro, apenas deixe-o de lado por enquanto, e mantenha-se atento.

### Um literal no meu console
Vamos supor, por exemplo, que no lugar do nosso literal `"Olá, mundo!"` você tenha inserido o número 5.<br>
Muito provavelmente, o número 5 terá sido exibido em sua tela.

Mas, o que ele é, exatamente?<br>
Você já sabe a resposta: um **_literal_**.

Porém, como você inseriu o número 5?<br>
* `5`
* `"5"` ou `'5'`
* `"\u0035"`

_Não se assuste, apenas ignore a última._

O que acontece é que (_rufem os tambores_) nós
