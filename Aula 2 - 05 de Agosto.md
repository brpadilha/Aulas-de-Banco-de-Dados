Métodos para projetos de banco de dados:

**Ascendente**("Botton-Up") Engenharia reversa.

**Descendente**("Top-down)

Segue os níveis de abstração "de cima para baixo";

Top down 
_____________________________
Mundo real -> mod. descritivo -> mod. conceiual -> mod. operacional -> modelo interno
_____________________________

O projeto adotado para nossas aulas é descendente (top-Down);

Modelo (conceitual) de entidade e relacionamento:

Introduzir por Pter Chew em 1976.

Entidade: representação abstrata de um "Objeto" do mundo real.



**Representação gráfica**

___
<center>

![Entidade](figuras/Entidade.png "Entidade")
                
</center>

___
Uma entidade tem, normalmente, um conjunto de atributos (características) que devem ser devidamente representados como no exemplo a seguir:

---

<center>

![Banco Alunos](figuras/BancoAlunos.png "Banco Alunos")

<h6>Banco Alunos</h6>

</center>

___
Atributos - como já mencionado, eles representam características e com informações particulares sobre um determinado tipo de ojeto.
Os atributos podem ser classificados quanto ao tipo de informações que receber. Neste aspecto podem representar como:

**Monovariado**: Um único valor para um determinado atributo de um determinado elemento de um grupo de objetos ou entidade.

**Composto**: um conjunto de subatributos com seus respectivos valores para um atributo de um determinado elemento de uma entidade.

**Multivariado**: Múltiplos valores para um determinado atributo de um determinado elemento de uma entidade.

**Determinante**: monovalorado e unívoco, ou seja, valor único para um determinado elemento que permiite indentificá-lo no meio de outros elementos pertencentes à entidade.

