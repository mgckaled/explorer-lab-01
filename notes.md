# EXPLORER LAB 01 - Rocketseat Education

## O que é DOM?

- **Doccument Object Model** - Modelagem de documento com objeto JavasScript
- **Representação do HTML em objeto JavaScript** - Atributos (propriedades) e métodos (funcionalidades)
- **Criado pelo navegador (browser)** - É uma interface (API) usada no navegador

---

## Dependências

- Vite
- iMask

---

## Expressões Regulares (JavaScript)

Também conhecida como `Regular Expression` ou `Regex` é uma tecnologia usada para buscar padrões dentro de textos e funciona em diversas linguagens

> Exemplo: Busque por todos os caracteres numéricos dentro de algum texto

### Como pensar?

Existe uma maneira correta de pensar ao utilizar essa tecnologia para a busca de padrões.

- Leitura da esquerda para direita
- Ler um caractere de cada vez, um após o outro
- Conhecer os caracteres reservados da tecnologia

### Criando regex no JavaScript

```js
const re = /foo/

// construtor
const re = new RegExp(/foo/)
```

### Funcões usadas em Strings

Existem diversas maneiras de usar expressões regulares em uma string no JavaScript. Abaixo, vamos verificar 3

```js
// agrupa os padrões em um array
const matches = 'aBC'.match(/[A-Z/g])
//  Output: Array [B, C]

// presquisa se existe ou não o padrão /
const index = 'aBC'.search(/[A-Z/])
// Output: 1

// agrupa os padrões em um array /
const next = 'aBC'.replace(/a/, 'A')
// Output: ABC
```

### CheatSheet

#### **Básico**

- `/expression / flags` - ex: `/[A-Z]+/g`
- `\` usar caracteres especiais - ex: `/ oi\?\*\\/`
- `()` agrupador
- `|` OU lógico
- `Fala Dev` pesquisa exata
- `^Fala` start of the strings
- `Dev$` end of the strings

#### **Conchetes**

- `[xyz]` qualquer um x, y, z
- `[J-Z]` qualquer caracter entre J e Z
- `[^xyz]` nenhum x, y ou z

#### **Classes de caracteres**

- `\w` palavra, `\d` dígito, `\s` espaços em branco(tabs, quebras de linha)
- `\W` NÃO palavra, `\D` NÃO dígito, `\S` NÃO espaços em branco
- `\t` tabs, `\n` quebra de linha
- `.` qualquer caracter (exceto nova linha)
- `marcel|lucas` marcel ou lucas
- `?` zero ou uma ocorrêcia
- `*` zero ou múltiplas ocorrências
- `+` uma ou múltiplas ocorrências
- `{n}` n ocorrências
- `{min, max}` mínima/máxima ocorrêcias

### Testando expressões

- Direto no Editor de Texto (VSCode)
- Online - RegExr: Learn, Build & Test RegEx

### Referências

---
