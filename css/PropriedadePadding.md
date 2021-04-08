# Propriedade Padding
> Ferramenta fundamental para construção de Layouts agradáveis.

A propriedade padding cria um espaço dentro da própria margem do elemento, dando a impressão de que ele ficou mais "apretado".

<div align="center">
    <img src="../box model.png" alt="Ilustração do Padding" width="500">
    (Ilustração do Padding)
<div>

## Parâmetros
Caso seja passado um único valor, todas as direções ficarão com o mesmo padding:
```css
.box {
  padding: 1.5em;
}
```

Caso sejam passados dois valores, o primeiro será o padding vertical e o segundo será o horizontal:
```css
.box {
  padding: 1.5em 0;
}
```

Caso sejam passados três valores, a sequência de paddings será |topo| |lados| |base|:
```css
.box {
  padding: 20px 1.5em 60px;
}
```

Caso sejam passados quatro valores, a sequência de paddings seguirá o sentido horário |topo| |direita| |base| |esquerda|:
```css
.box {
  padding: 0 1.5em 0 1.5em;
}
```