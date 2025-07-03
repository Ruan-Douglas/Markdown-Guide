# **Tabelas em Markdown**
As tabelas são ótimas ferramentas para representar um conjunto de dados, vamos mostrar agora, como criar tabelas na linguagem *Markdown*

## Sintaxe
Para criar tabelas é bem simples, usamos algo como `Teste | Teste 2 | Teste 3` sendo essa nossa primeira linha e delimitando qual será a coluna com uma barra em pé `|`. Após isso, na próxima linha usamos `--- | --- | ---` para colocarmos uma linha horizontal abaixo da primeira que representa os títulos das colunas, fazendo assim corretamente a separação e os títulos ficarão em negrito.

### Exemplos:
```
Teste | Teste 2 | Teste 3 | Teste 4
--- | --- | --- | ---
Item A | Item B | Item C | Item D
Item E | Item F | Item G | Item H
Item I | Item J | Item K | Item L
```
### Resultado:
Teste | Teste 2 | Teste 3 | Teste 4
--- | --- | --- | ---
Item A | Item B | Item C | Item D
Item E | Item F | Item G | Item H
Item I | Item J | Item K | Item L

> **Dica**: Podemos ainda aplicar alinhamentos personalizados às colunas, utilizando os dois-pontos `:` junto com os traços `---`. Usando `:---:` para um alinhamento central, `---:` para um alinhamento à direita e `:---` para um alinhamento à esquerda, veja abaixo:

### Exemplo:
```
Teste | Teste 2 | Teste 3 | Teste 4
:---: | :--- | ---: | ---:
A | B | C | 4
E | F | G | 6
I | J | K | 10
```
### Resultado:
Teste | Teste 2 | Teste 3 | Teste 4
:---: | :--- | ---: | ---:
A | B | C | 4
E | F | G | 6
I | J | K | 10

Como você pode observar, os textos das colunas foram alinhados conforme definido. Essa técnica é muito útil para deixar suas tabelas mais organizadas e legíveis.