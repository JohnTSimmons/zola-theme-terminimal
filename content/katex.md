+++
title = "Katex Tests"

date = 2018-09-06

[taxonomies]
tags = ["javascript"]
+++
Block of Katex Tests:

{{ katex(body="\KaTeX") }}

{% katex(block=true) %}\KaTeX{% end %}

\\( \KaTeX\\)

{% katex(block=true) %}

x = \begin{cases}
   a &\text{if } b \\
   c &\text{if } d
\end{cases}

{% end %}
