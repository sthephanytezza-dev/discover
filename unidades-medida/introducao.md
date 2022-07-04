# Valores e unidades de medida

    * cada propriedade possui valores `property: value`
    * estudo constante a fim de entender as propriedades e seus valores

## Prática

    * como conhecer e estudar os valores na documentação?
        * <color> <length>
    * os termos podem variar. `values` ou `data types`

# Tipos numéricos unidades

    * <integer>     Número inteiro como -10 ou 223
    * <number>      Número decimal como -2.4, 64 ou 0.234
    * <dimension>   É um <number> com uma unidade junto: 90deg, 2s, 8px
    * <percentagem> Representa a fração de outro número: 50%

## Unidades comuns

    * <length>      Representa um valor de distância: px, em, vw
    * <angle>       Representa um ângulo: deg, rad, turn
    * <time>        Representa um tempo: s, ms
    * <resolution>  Representa resoluções para dispositivos: dpi

# Distâncias absolutas <length>

São fixas e não alteram seu valor.

Unidade Nome Equivalência
cm Centímetros 1cm = 96px/2.54
in Inches (polegadas) 1in = 2.54cm = 96 px
px Pixels 1px = 1/96th of 1in

- o mais comum e mais utilizado é o **px**
- não recomendado usar cm

# Distâncias relativas

São relativas a algum out valor, pode ser o elemento pai, ou root, ou tamanho da tela.

- Benefício: maior adaptação aos diferentes tipos de tela.

Unidade Relativo a
em Tamanho da font do pai
rem Tamanho da font do elemento raz (root/html)
vw 1% da viewport width
vh 1% da viewport height

# Porcentagens %

- Em muitos casos é tratado da mesma maneira que as distâncias <length>
- Sempre será relativo a algu valor

# Posições

<position>

Representa um conjunto de coordenadas 2D:

- top, right, bottom, left e center

* Usado para alguns tipos de propriedades
* Não confundir com a propriedade `position`

# Funções para

Em programação, funções são reconhecidas por causar um reaproveitamento de código.

- rgb()
- hsl()
- url()
- calc()

# Strings e identificadores

- Strings: texto envolto de aspas
- Identificadores: red, black, gold
