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
