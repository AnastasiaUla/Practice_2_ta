# 5. Полученная РГ и эквивалентное ей РВ.

Построена праволинейная регулярная грамматика:

```text
S -> aA | bC | λ
A -> aS | bB
B -> bC | λ
C -> bB
```

Файл JFLAP: [`regular-grammar.jff`](./regular-grammar.jff).

Эквивалентное регулярное выражение:

```math
R'=(aa)^*(\lambda+ab+(b+abb)(bb)^*b)
```
