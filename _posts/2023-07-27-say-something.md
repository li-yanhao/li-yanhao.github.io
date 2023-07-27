---
title: Hello World
date: 2023-07-27 01:58:00 +0200
categories: [Fruit, Apple]
tags: [misc]     # TAG names should always be lowercase
math: true
---

Say something pls ...

It's late. I should sleep Zzzzzz~


# Heading 1

## Heading 2

## Paragraph

Quisque egestas convallis ipsum, ut sollicitudin risus tincidunt a. Maecenas interdum malesuada egestas. Duis consectetur porta risus, sit amet vulputate urna facilisis ac. Phasellus semper dui non purus ultrices sodales. Aliquam ante lorem, ornare a feugiat ac, finibus nec mauris. Vivamus ut tristique nisi. Sed vel leo vulputate, efficitur risus non, posuere mi. Nullam tincidunt bibendum rutrum. Proin commodo ornare sapien. Vivamus interdum diam sed sapien blandit, sit amet aliquam risus mattis. Nullam arcu turpis, mollis quis laoreet at, placerat id nibh. Suspendisse venenatis eros eros.

## List

1. First

2. Second

3. Third

### Unordered list

- Chapter
    - Section
        - Paragraph


### Todo list

- [ ] Close your laptop
- [x] Brush your teeth
- [ ] Turn off all the lights
- [ ] Go to bed

- [ ] Job
  + [x] Step 1
  + [x] Step 2
  + [ ] Step 3


### Description list

Sun
: the star around which the earth orbits

Moon
: the natural satellite of the earth, visible by reflected light from the sun


## Prompts

> An example showing the `tip` type prompt.
{: .prompt-tip }

> An example showing the `info` type prompt.
{: .prompt-info }

> An example showing the `warning` type prompt.
{: .prompt-warning }

> An example showing the `danger` type prompt.
{: .prompt-danger }  

> WARNING: Sleep now!
{: .prompt-warning }

## Tables

| Company                      | Contact          | Country |
|:-----------------------------|:-----------------|--------:|
| Alfreds Futterkiste          | Maria Anders     | Germany |
| Island Trading               | Helen Bennett    | UK      |
| Magazzini Alimentari Riuniti | Giovanni Rovelli | Italy   |

## Links

<http://127.0.0.1:4000>


## Footnote

Click the hook will locate the footnote[^footnote], and here is another footnote[^fn-nth-2].


## Inline code

This is an example of `Inline Code`.

## Filepath

Here is the `/path/to/the/file.extend`{: .filepath}.

## Code blocks

### Common

```
This is a common code snippet, without syntax highlight and line number.
```

### Specific Language

```python
print(f"Hello World")
```

### Specific filename

```cpp
#include <iostream>
int main() {
    std::cout << "Hello World" << std::endl;
    return 0;
}
```
{: file='hello.cpp'}


## Mathematics

The mathematics powered by [**MathJax**](https://www.mathjax.org/):

$$ \sum_{n=1}^\infty 1/n^2 = \frac{\pi^2}{6} $$

When $a \ne 0$, there are two solutions to $ax^2 + bx + c = 0$ and they are

$$ x = {-b \pm \sqrt{b^2-4ac} \over 2a} $$

Number of False Alarm (NFA):





$$
\begin{align}
I & = \int \rho R^{2} dV & + P \\
Y & = 1 & + x
\end{align}
$$

$$ \text{NFA}(p, b, X ) = N(p,b) \cdot \mathbb{P} \left( k(p, b, \pmb r) \geq K \right) 
= \left(\left\lfloor \frac {n-1} {2} \right\rfloor - 2d\right) \cdot p \cdot \mathbf{B}\left(K,\,\, \# S(p, b, \pmb r),\,\, \frac{1}{2d+1} \right) $$

$$ \begin{align}
    \text{NFA}(p, b, X ) &= N(p,b) \cdot \mathbb{P} \left( k(p, b, \pmb r) \geq K \right)  \notag \\
    &= \left(\left\lfloor \frac {n-1} {2} \right\rfloor - 2d\right) \cdot p \cdot \mathbf{B}\left(K,\,\, \# S(p, b, \pmb r),\,\, \frac{1}{2d+1} \right)
\end{align} $$

## Video

{% include embed/youtube.html id='yMNlifMSRO0' %}

## Reverse Footnote

[^footnote]: The footnote source
[^fn-nth-2]: The 2nd footnote source