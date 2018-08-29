---
title: Use Latex in Jekyll
layout: post
toc: true
categories: latex
---
Two things need to be done.

<!--more-->

1. Import MathJax: make sure use ```https```
    ``` html
    <script type="text/javascript"
        src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML">
    </script>
    ```
2. Put the code in ```{% raw %} {% endraw %}```
    ```
    {% raw %}
        $$put MathJax here$$
    {% endraw %}
    ```
    
## Style Examples

* Inline
    {% raw %}
    $$a^2 + b^2 = c^2$$ --> note that all equations between these tags will not need escaping! 
    {% endraw %}

    ```
    $$a^2 + b^2 = c^2$$ --> note that all equations between these tags will not need escaping!
    ```

* Block
    {% raw %}
    $$a^2 + b^2 = c^2$$
    {% endraw %}

    ```
    $$a^2 + b^2 = c^2$$
    ```

## Syntax Examples

[MathJax quick reference](https://math.meta.stackexchange.com/questions/5020/mathjax-basic-tutorial-and-quick-reference)

### Greek letters
For Greek letters, use ```\alpha, \beta, …, \omega```: {% raw %}$$\alpha, \beta, … \omega$${% endraw %}. For uppercase, use ```\Gamma, \Delta, …, \Omega```: {% raw %}$$\Gamma, \Delta, …, \Omega$${% endraw %}.

### Superscripts and Subscripts

### Groups

### Parentheses 

### Sums and integrals

### Fractions

### Radical signs