# Cônicas

Consiste em um programa criado em linguagem Python no Jupyter Notebook para informar qual é o tipo da cônica da equação digitada.

Inicialmente é importante deixar claro o que é uma seção cônica. \
Ao cortar um cone por um plano, a interseção entre eles será uma curva. Mas o tipo dessa curva dependerá de como estava o plano que cortou o cone.\
Dependendo da inclinação desse plano, a curva encontrada pode ser uma parábola, uma elipse ou uma hipérbole. \
Essa curva terá uma equação. Existe um teorema que permite dizer qual é a categoria da seção cônica(curva) simplesmente fazendo cálculos com os coeficientes da equação.
Esse teorema é implementado por meio de condicionais dentro do código Python.
Além disso, ao final, é plotado o gráfico da curva da equação informada.

Vamos a um exemplo prático.

## Uso do programa para identificar uma elipse

Imagine que queremos saber qual é a cônica da equação $`\frac{x^2}{4} + \frac{y^2}{9} = 1 `$.
Essa equação é de uma elipse que intercepta o eixo x em (2,0) e (-2,0) e intercepta o eixo y em (0,3) e (0,-3). Mas suponha que não saibamos isso.
A equação é então digitada no programa.

![conicainformada](https://github.com/brunopaivabp/Python-Conicas/assets/10210318/631afefa-37b7-4034-b6ec-5a8b04405488)

O programa informada corretamente o tipo da cônica.

![elipse](https://github.com/brunopaivabp/Python-Conicas/assets/10210318/51a1d218-b6c4-4a02-8fda-bcd661634158)

Por fim, o programa plota corretamente o gráfico da elipse.

![elipseplotada](https://github.com/brunopaivabp/Python-Conicas/assets/10210318/206ff6a9-ff90-486c-9762-59ab35410676)

## Uso do programa para identificar uma hipérbole

Imagine que queremos saber qual é a cônica da equação $` x^2 - y^2 = 1 `$.
Essa equação é de uma hipérbole. Mas suponha que não saibamos isso.
A equação é então digitada.
![hiperbole](https://github.com/brunopaivabp/Python-Conicas/assets/10210318/e1c1404d-b11c-4938-ad3f-b84244d4f9f0)

A hipérbole é classificada corretamente.
![classificacaohiperbole](https://github.com/brunopaivabp/Python-Conicas/assets/10210318/ac06fa58-4a41-47bd-9231-b159e68e430a)

O gráfico da hipérbole informada é plotado.
![hiperboleplotada](https://github.com/brunopaivabp/Python-Conicas/assets/10210318/2b38cdad-95cd-4589-8fb1-bb98941116c6)



