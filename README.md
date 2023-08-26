# TP_1_SINT_SEM
SSL 2023 - Trabajo práctico N° 1

Joaquin Andres Soaje - Legajo: 1632930 Curso K2006

# BNF Arnold
<program> ::= <statement>+

<statement> ::= <assignment> | <output> | <if>

<assignment> ::= "HEY CHRISTMAS TREE" <variable> "YOU SET US UP" <expression>

<output> ::= "TALK TO THE HAND" <expression>

<if> ::= "BECAUSE I'M GOING TO SAY PLEASE" <expression> "HERE IS MY INVITATION" <block>

<expression> ::= <term> | <expression> <operator> <term>

<term> ::= <literal> | <variable>

<literal> ::= <number>

<variable> ::= <identifier>

<operator> ::= "GET UP" | "GET DOWN" | "YOU'RE FIRED" | "HE HAD TO SPLIT"

<block> ::= "I LIED" <statement>+ "YOU HAVE NO RESPECT FOR LOGIC" "BULLSHIT"
