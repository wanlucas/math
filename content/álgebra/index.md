# Álgebra

Uma expressão algébrica é uma combinaçao de números e letras representando números.

## Nomenclaturas

- **Termo** é a parte única de um expressão, 5x é um termo de 5x + 2y
- **Fator** é a parte de um termo, 5x³ é um fator de 5x³y⁴
- Um fator de um termo é **Coeficiente** do restante do termo, no termo 5x³y⁴, 5x³ é coeficiente de y⁴
- **Subtraendo** é a expressão que é removida de outra em uma subtração

## Regras

### Adição

A adição é obtida juntando os termos semelhantes.

        (7x + 3y³ - 4xy) + (3x - 2y³ + 7xy) + (2xy - 5x - 6y³)
        5x + -5y³ + 5xy

### Subtração

A subtração é obtida alterando o sinal de cada termo da expressão que está sendo subtraida e juntando as expressões

        (10x² - 2xy - 3y²) - (2x² - 3xy + 5y²)
        (10x² - 2xy - 3y²) + (-2x² + 3xy - 5y²)
        8x² + xy - 8y²

### Multiplicação

A multiplicação é obtida multiplicando-se os termos nos fatores das expressões

#### Monômio por Monômio

        (-3x²y³z)(2x⁴y)(-4xy⁴z²)
        ((-3)(2)(-4))(x² * x⁴ * x)(y³ * y * y⁴)(z * z²)
        24x⁷y⁸z³

#### Monômio por Polinômio

        (3xy - 4x³ + 2xy²)(5x²y⁴)
        (5x²y⁴)(3xy) + (5x²y⁴)(-4x³) + (5x²y⁴)(2xy²)
        15x³y⁵ - 20x⁵y⁴ + 10x³y⁶

#### Polinômio por Polinômio

        (3 - x)(-3x + 9 + x²)
        (-9x + 27 + 3x²) + (3x² - 9x - x³)
        6x² -18x - x³ + 27
        -x³ + 6x² - 18x - 27

### Divisão

A divisão é obtida usando-se a regra de divisão dos expoentes

#### Monômio por Monômio

        (24x⁴y²z³) / (-3x³y⁴z)
        -8x(1/y²)z²
        -8xz¹ / y²

#### Polinômio por Polinômio

        2x⁴ - 3x³ + x² + x - 2 | x² - 3x + 2
       -2x⁴ + 6x³ - 4²           2x² + 3x + 6
        _____________
        3x³  - 3x² + x
       -3x³  + 9x² - 6x
        _____________
        6x² - 5x - 2
       -6x² + 18x -12
        _____________
        13x - 14

[Exercícios](./examples/1.md)

## Produtos especiais

- Produto entre um monômio e um binômio

        a(c + d) = ac + ad

- Produto entre a soma e a difefença de dois termos

        (a + b)(a - b) = a² - b²

- Quadrado de um binômio
  (a + b)² = a² + 2ab + b²
  (a - b)² = a² - 2ab + b²

- Produto de dois binômios

        (x + a)(x + b) = x² + (a + b)x + ab
        (ax + b)(cx + d) = acx² + (ad + bc)x + bd
        (a + b)(c + d) = ac + ad + bc + bd

- Cubo de um binômio

        (a + b)³ = a³ + 3a²b + 3ab² + b³
        (a - b)³ = a³ - 3a²b + 3ab² - b³

- Quadrado de um trinômio

        (a + b + c)² = a² + b² + c² + 2ab + 2ac + 2bc

- Diferença entre a n-ésima potência

        (a - b)(a⁰ + b⁰) = a¹ - b¹
        (a - b)(a¹ + b¹) = a² - b²
        (a - b)(a² + ab + b²) = a³ - b³
        (a - b)(a³ + a²b + ab² + b³) = a⁴ - b⁴
        (a - b)(a⁴ + a³b + a²b² + ab³ + b⁴) = a⁵ - b⁵
        ...

[Exercícios](./examples/2.md)

## Fatoração

Os fatores de uma expressão consistem em duas ou mais expressões que, quando multiplicadas, resultam na expressão dada.

- Fator monomial comum

        6x²y - 2x³ = 2x²(3y - x)
        2x³y - xy² + 3x²y = xy(2x² - y + 3x)

- Diferença de dois quadrados

        a² - b² = (a + b)(a - b)
        x² - 25 = x² - 5² = (x + 5)(x - 5)
        4x² - 9y² = (2x)² - (3y)² = (2x + 3y)(2x - 3y)

- Trinômios quadrados perfeitos

        a² + 2ab + b² = (a + b)²
        a² - 2ab + b² = (a - b)²
        x² + 6x + 9 = (x + 3)²
        9x² - 12xy + 4y² = (3x - 2y)²

- Soma e diferença de dois cubos

        a³ + b³ = (a + b)(a² - ab + b²)
        a³ - b³ = (a - b)(a² + ab + b²)

        8x³ + 27y³
        (2x)³ + (3y)³
        (2x + 3y)((2x)² + (2x)(3y) + (3y)²)
        (2x + 3y)(4x² + 6xy + 9x²)

        8x³y³ - 1
        (2xy)³ - 1³
        (2xy - 1)((2xy)² + (2xy)(1) + 1²)
        (2xy - 1)(4x²y² + 2xy + 1)

- Agrupamento de termos

  ac + bc + ad + bd = c(a + b) + d(a + b) = (c + d)(a + b)

        2ax - 4bx + ay - 2by
        2x(a - 2b) + y(a - 2b)
        (2x + y)(a - 2b)

- Fatores de a^n +- b^n

        32x⁵ + 1
        (2x)⁵ + 1⁵
        (2x + 1)((2x)⁴ + (2x)³(1) + (2x)²(1²) + (2x)(1³) + 1⁴)
        (2x + 1)(16x⁴ - 8x³ + 4x² - 2x + 1)

        x⁷ - 1
        x⁷ - 1⁷
        (x - 1)(x⁶ + x⁵ + x⁴ + x³ + x² + x + 1)

- outros

        1)
        x² + x(a + b) + ab = (x + a)(x + b)

        x² + 7x + 10
        (x + 2)(x + 5)

        2)
        x² - x(x + b) + ab = (x - a)(x - b)

        x² - 7x + 10
        (x - 2)(x - 5)

        3)
        x² + x(a - b) - ab = (x + a)(x - b)

        x² + 3x - 10
        (x + 5)(x - 2)

        4)
        x² - x(a - b) - ab = (x - a)(x + b)

        x² - x - 12
        (x - 4)(x + 3)

[Exercícios](./examples/3.md)

## Frações

Uma fração algébrica racional pode ser ecrita como o quociente de dois polinômios.

        (3x - 4) / (x² - 6x + 8)

O valor de uma fração permanece inalterado se o numerador e denominador forem multiplicados ou divididos pelo mesmo valor

        (x + 2) / (x - 3) = ((x + 2)(x - 1)) / (x - 3)(x - 1) = (x² + x - 2) / (x² - 4x + 3)

        (x + 2) / (x - 3) = ((x + 2) / (x - 1)) / ((x - 3) / x - 1)) =

Simplificar uma fração é convertê-la numa forma equivalente no qual numerador e denominador não possuam fatores em comum.

        (x² - 4xy + 3y²) / (x² - y²)
        ((x - 3y)(x - y)) / ((x + y)(x - y))
        (x - 3y) / (x + y)


[Exercícios](./examples/4.md)


## Expoentes

Se N é um inteiro positivo, a^n representa o produto de N faturores iguais a a∁

        2^3 = 2 * 2 * 2

Se N é um inteiro negatido, definimos
 
        a^-n = 1 / (a^n) se a ≠ 0

### Regras gerais

        a^3/2 = ²√a³ se a > 0 e n é o divisor é par

        8⁻²/³ = 1 / ³√8² = 1 / ³√64 = 1 / 4

        2³ * 2² = 2³⁺² = 2⁵ = 32

        3¹/³ * 3¹/⁶ = 3¹/³⁺¹/⁶ = 3¹/² = ²√3 = √3

        (3²)³ = 3²*³ = 3⁶

        (2²)⁻³ = 2⁻⁶ = 1 / 2⁶ = 1 / 128
        
        2⁶ / 2⁴ = 2⁶⁻⁴ = 2² 

        3⁻² / 3⁴ = 3⁻²⁻⁴ = 3⁻⁶

        x¹/² / x⁻¹ = x¹/² ⁻ (⁻¹) = x³/²
 
