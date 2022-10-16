# Simply Typed Lambda Calculus

## Concepts

A *monoid* is a set M equipped with a binary operation u and special element 1, such that x·y=u(x,y) satisfy

1. association law: (x·y)·z = x·(y·z)
2. left and right unit law: 1·x = x = x·1

A *category* C consists of

1. a collection C0 of objects.
2. a collection C1 of morphisms, or arrows. And morphisms can composite.
3. identiry morphisms 1x

and satisfy

1. src(g·f) = src(f), dst(g·f) = dst(g)
2. src(1x) = x = dst(1x)
3. associative: (x·y)·z = x·(y·z)
4. left and right unit law: 1x·f = f = f·1x

The *product* of of object A and object B can be expressed using diagram

![prod2](https://user-images.githubusercontent.com/49089605/196035001-16ab7bf6-92c9-471a-bb28-b6dc8c61a861.jpeg)
