# Markdown
Conteudo basico de Markdown

# Titulo
## Subtitulo
### Subtitulo
#### Subtitulo
##### Subtitulo
###### Subtitulo
obeserve que a quantidade de "#" vai de 1-6

Titulo
===
Subtitulo
---
Outra meneira de inserir titulos

## Negrito e Italico

**negrito**

*italico*

Para que haja quebra de linha, de dois espacos, ou um enter.

## inserindo listas ou topicos

- item1
- item2
    - item2.1
    - item2.2
        - item2.2.1
        - item2.2.2

1. item1
2. item2
3. item3

ou

1. item1
1. item2
1. item3

Observe que usando o numero 1 sempre no inicio, fica mais facil de fazer qualquer mudanca futura

## Inserindo codigo

`for(int i = 0; i < 10; i++){
    printf("%d ", i);
}`

```
for(int i = 0; i < 10; i++){
    printf("%d ", i);
}
```

A linguagem pode er informada
```c
for(int i = 0; i < 10; i++){
    printf("%d ", i);
}
```

## Citacao
> Para toda linha, deve ser adicionado um ">", segue o exemplo

>visto que tambem eh possivel selecionar quais linhas entram na citacao

## Links

[Link](https://github.com/felipeasano?tab=repositories)

Ou ainda:

https://github.com/felipeasano?tab=repositories

### Agora usando uma referencia

[link pro meu repositorio]: https://github.com/felipeasano?tab=repositories

[Acesse meu Repositorio][Link pro meu repositorio]

## Inserindo Imagens

![foto](https://t2.tudocdn.net/510706?w=646&h=284)

Observe que o texto "foto" eh de certa forma opcional

### Agora usando uma referencia

[imagem-git]:https://t2.tudocdn.net/510706?w=646&h=284

![][imagem-git]

## Separacao usando linha 

exemplo

---

continuacao

Atencao que, para que a linha apareca deve ser dado uma quebra d linha do conteudo de cima

## Tabelas

Como exemplos, vamos usar uma tabela de produtos

| ID | Nome | Preco |
|-|-|-|
| 1 | Samsung S21 | R$ 2.000 |

A linda de tracos eh necessaria

## Alinhamento de texto

| ID | Nome | Preco |
|-|-:|-|
| 1 | Samsung S21 | R$ 2.000 |
| 2 | iPad | R$ 2.000 |

O alinhamento eh feito usando-se os ":", desta forma, ":" a direira alinha a direita, o mesmo eh feito para a esquerda e usando no dois lado o texto fica centralizado

Negrito e italico tambem podem ser usados e codigo na linha

| ID | Nome | Preco |
|-|-:|-|
| 1 | *Samsung S21* | `R$ 2.000` |
| 2 | **iPad** | R$ 2.000 |


# Para mais informacoes:

[Markdown Cheat Sheet](https://www.markdownguide.org/cheat-sheet/)