---
title: test1
layout: default
parent: Home
---

# Converted from Markdown file
test
## From demo

When $a \ne 0$, there are two solutions to \\(ax^2 + bx + c = 0\\) and they are
$$x = {-b \pm \sqrt{b^2-4ac} \over 2a}.$$


### Line starts from `$$`

```
$$N = \sum_{n=1}^r x_n$$
```

$$N = \sum_{n=1}^r x_n$$

(Converted to `<script type="math/tex">` by Jekyll)

### Line does not start from `$$`

```
test: $$N = \sum_{n=1}^r x_n$$
```

test: $$N = \sum_{n=1}^r x_n$$

(Converted to `<script type="math/tex; mode=display">` by Jekyll)

## Use script type math/tex

<p><script type="math/tex">ax+by+c=0</script></p>
<script type="math/tex; mode=display">\sum_{i=1}^n x_i</script>

## 数式番号
In equation \eqref{eq:sample}, we find the value of an
interesting integral:

\begin{equation}
  \int_0^\infty \frac{x^3}{e^x-1}\,dx = \frac{\pi^4}{15}
  \label{eq:sample}
\end{equation}

## 自作マクロ
$\RR$, 
$\ddx[f]{x}$, 
$\abc$, 
$\bold{math}$, 
$\Cl{R}$,
$\Vt{x}$,
$\int \pi(t) \Id t$,
$\PDF{f(x)}{x}$,
$\ODF{f(x)}{x}$,
$\PDDF{f(x,y)}{x}{y}$

$\phantom{}$$
\newcommand\nr{\notag\\\\}%タグなし改行用
\newcommand\ret{\notag\\\\&\qquad}%数式改行用
\newcommand\I{\mathrm{i}}
\newcommand\D{\mathrm{d}}
\newcommand\E{\mathrm{e}}
\newcommand\hc{\mathrm{h.c.}}
\newcommand\cc{\mathrm{c.c.}}
\newcommand\O[1]{\mathscr{O}\left(#1\right)}
\newcommand\abs[1]{{\left\rvert #1 \right\lvert}}
\newcommand\Res{\mathop{\mathrm{Res}}}
\newcommand\bra[1]{\mathinner{\langle{#1}|}}
\newcommand\ket[1]{\mathinner{|{#1}\rangle}}
\newcommand\braket[1]{\mathinner{\langle{#1}\rangle}}
\newcommand\Bra[1]{\left\langle#1\right|}
\newcommand\Ket[1]{\left|#1\right\rangle}
\newcommand\Braket[1]{\left\langle #1 \right\rangle}
\newcommand\|{\middle|}%\Braket用
\DeclareMathOperator{\Log}{Log}
\DeclareMathOperator{\Arg}{Arg}
\DeclareMathOperator{\sgn}{sgn}
\DeclareMathOperator{\Tr}{Tr}
\newcommand\dashint{\mathchoice
  {\int\kern-10pt-}
  {\int\kern-8.5pt-}
  {\int\kern-6.1pt-}
  {\int\kern-4.58pt-}}
\newcommand\set[1]{\left\\{#1\right\\}}
\newcommand\for[1]{\quad\mathrm{for}\quad #1}
\newcommand\LHS{\mathrm{(LHS)}}
\newcommand\RHS{\mathrm{(RHS)}}
$
$$
\dashint \D x \frac{\E^{\I a x}}{x} = \I \pi \sgn(a) \for{a\in\mathbb{R}},
$$
