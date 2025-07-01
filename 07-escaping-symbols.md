# **Escape de Símbolos**
Aprendemos até aqui que podemos formatar textos e muito mais em *Markdown* usando diversos símbolos diferentes, mas e se quisermos mostrar esses símbolos sem que eles tenham efeito? como podemos fazer isso? Tem um jeito e eu vou te mostrar.

## Sintaxe
Para "escaparmos" do efeito que esses caracteres especiais fazem, usamos o `\` antes do caractere para anular seu efeito, veja no exemplo.

### Exemplo:
```
\*Isso não é itálico\*

\# Isso não é um título

\[Google\]\(https://google.com\)
```
### Resultado:
\*Isso não é itálico\*

\# Isso não é um título

\[Google\]\(https://google.com\)

Como você pode ver, conseguimos exibir os símbolos normalmente na mensagem sem que eles alterem ou renderizem a palavra ou frase.

* **_Obs:_**
Não usei muito esse recurso na produção desse arquivo porque preferi usar as **_crases_** para gerar o bloco de código, pois dessa forma o conteúdo fica mais destacado, e o *efeito de anular a renderização* funciona da mesma maneira.