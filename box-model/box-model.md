# Box Model

- Fundamental para fazer layouts para web
- Maior facilidade para aplicar o CSS

## O que é?

Uma caixa retangular.
Essa caixa possui propriedades de uma caixa (2D).

- Tamanho (largura x altura) width | heigth
- Conteúdo content
- Bordas border
- Preenchimento interno padding
- Espaços fora da caixa margin

* Cada elemento na sua página, será considerado uma caixa.

## box-sizing

Como será calculado o tamanho total da caixa?

- content-box|border-box

```css
div {
  box-sizing: border-box;
}
```

## display: block vs display: inline

- Como as caixas se comportam em relação às outras caixas
- Comportamento externo das caixas

| **block** | **inline** |
|****************\_****************|**************\_\_**************|
| ocupa toda a linha, colocando o | elemento ao lado do outro |
| próximo elemento abaixo desse | |
|****************\_****************|**************\_\_**************|
| width e height são respeitados | width e heigth não funcionam |
|****************\_****************|**************\_\_**************|
| padding, margin, border irão | somente valores horizontais |
| funcionar normalmente. | de margin, padding e border |
|****************\_****************|**************\_\_**************|

exemplos
block: `<p> <div> <section>`, todos os headings `<h1><h2>...`
inline: `<a> <strong> <span> <em>`
