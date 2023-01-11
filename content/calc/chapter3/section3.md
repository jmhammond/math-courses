---
author: John Hammond
title: Section 3.3
mathjax: true
ShowBreadCrumbs: true
showtoc: true
tocopen: false
---

Section 3.3, The First and Second Derivative Test
<!--more-->

## Increasing / Decreasing Test

- If $f'(x) > 0$ on an interval, then $f$ is increasing on that interval. 
- If $f'(x) < 0$ on an interval, then $f$ is decreasing on that interval.
- If $f'(x) = 0$ on an interval, then $f$ is constant on that interval.

### Example

Find where $f$ is increasing and decreasing.
$$
f(x) = \frac34 x^4 + 2x^3 - 12x^2 + 5
$$

{{< youtube Rrn9QMiE6xU >}}


## The First Derivative Test
Suppose that $c$ is a critical number of a continuous function $f$.
1. If $f'$ changes from positive to negative at $x=c$, then the function $f$ has a local maximum at $x=c$
2. If $f'$ changes from negative to positive at $x=c$, then the function $f$ has a local minimum at $x=c$.
3. If $f'$ doesn't change sign at $x=c$, then $f$ has no local max/min at $x=c$. 

### Example
Find the local maxima and minima of $f(x) = x + 2\sin x$ on the interval $[0, 2\pi]$. 

{{< youtube Jj3qDyMSKx8 >}}

## Concavity

We'll define concavity on an interval in connection to a function's shape related to its tangent lines on that interval. But the basic intuitive idea is that a function is: 

- Concave up if it's shaped up like a cup  ◡
   
   If you poured your favorite beverage into the function, it would hold it. :beer: :grinning_face_with_smiling_eyes: 
- Concave down if it's shaped down like a frown ◠  

   If you poured your favorite beverage into the function, it would spill :droplet: :cry: 

### Concavity and tangent lines

![](/calc/3.3.concavity.png)

We define a function to be **concave up** on an interval if the function is always above its tangent lines on that interval.

We define a function to be **concave down** on an interval if the function is always below its tangent lines on that interval.

### Concavity test

1. If $f''(x) > 0$ for all $x$ in an interval, then $f$ is concave upward on that interval.
2. If $f''(x) < 0$ for all $x$ on an interval, then $f$ is concave down on that interval.

A point is called an **inflection point** if a function is continuous at the point and changes concavity from up to down or down to up at the point. 

### Example

Find the inflection points and determine the concavity of the function
$$
f(x) = x^4 - 2x^2 + 3
$$

{{< youtube J2h_bCkhmwM >}}

## The Second Derivative Test

Suppose that $f''$ is continuous near $x=c$:
1. If $f'(c) = 0$ and $f''(c) > 0$, then $f$ has a local minimum at $x=c$
2. If $f'(c) = 0$ and $f''(c) < 0$, then $f$ has a local maximum at $x=c$.

Note that this uses the second derivative to tell us about extrema. The value $x=c$ is a critical number, but it $f'(c)$ must be defined and 0 at that point. 


### Example
Find local extrema of the function
$$
f(x) = x^4 - 2x^2 + 3
$$

{{< youtube MXB3E9B6zhw >}}

### Example
Using concavity, inflection points, and local extrema, sketch a graph of the function
$$
f(x) = x^4 - 4x^3
$$

{{< youtube sR36oF343VQ >}}

-----

This is section 3.4

## Motivation:

We've already seen $\displaystyle \lim_{x\to \infty} \frac1x = 0$. Also, since those $x$ values are positive, we're approaching 0 from above.

On a similar note, $\displaystyle \lim_{x\to -\infty} \frac1x = 0$ as well. And since those $x$ values are negative, we're approaching 0 from below.  This matches what we know the graph to look like: 

![Screenshot 2021-03-03 9.31.01 AM|605x499, 50%](upload://sYGreLbgaxFVDM0MeetGL6tSKHZ.png)



## Intuitive Definition of the Infinite Limit

Let $f$ be a function defined on some interval $(a, \infty)$. Then 
$$
\lim_{x\to \infty} f(x) = L
$$
means that the values of $f(x)$ can be make arbitrarily close to $L$ by requiring $x$ to be sufficiently large.

Examples of infinite limits where $f(x) \to L$ as $x\to \infty$.

![9781305962125-ch3-0138-t3|690x127](upload://jNFHywJtBQYvYA2yFsrsAMR292X.png) 

Analogously, if the function is defined on $(-\infty, a)$, then we can have $\displaystyle \lim_{x\to -\infty} f(x) =L$ if $f(x)$ gets arbitrarily close to $L$ as $x$ get sufficiently large in the negative direction.

![9781305962125-ch3-0141a-t2|234x308](upload://odlnct2P9xwySGbFKaDylkcs39Y.png) 

## Horizontal Asymptote

We call the line $y=L$ a *horizontal asymptote* of the function if 
$$
\lim_{x\to \infty} f(x) = L
$$
or 
$$
\lim_{x\to -\infty} f(x) = L
$$

### More than one horizontal asymptote?
Yes! We call $y=L$ a horizontal asymptote. It's entirely possible a function has more than one! Here's an example curve with two horizontal asymptotes: 

![9781305962125-ch3-0147-t2|557x177](upload://7sLVEctU9fGvfULEKZH3spgdQR4.png) 

## Computing Limits at Infinity

First, we get a tool we'll use to compute these infinite limits.

### Theorem 

If $r \gt 0$ is a rational number, then
$$
\lim_{x\to \infty} \frac{1}{x^r} = 0
$$
and if $r\gt 0$ is a rational number so that $x^r$ is defined for all $x$[^1], then
$$
\lim_{x\to -\infty} \frac{1}{x^r} = 0
$$
[^1]: No square roots of negative numbers, for example.

### Example

Now let's compute an infinite limit. Evaluate

$$
\lim_{x \to \infty} \frac{2x^2 - 3x - 5}{3x^2 + 4x + 1}
$$

{{< youtube 0Dro6pzAHsI >}}

### Example

Find the horizontal and vertical asymptotes of the graph of the function.

$$
\frac{\sqrt{2x^2 +1}}{3x - 5}
$$

{{< youtube HyUSdX2sFu8 >}}

Here's an image that shows the asymptotes:
![9781305962125-ch3-0169-t2|225x228](upload://jQsGJBWEI57y56YYQAeUOla3wmG.png) 


### Example 

This example is a little different. Is "$\infty - \infty$" equal to 0? Or something else? 

Compute $\displaystyle \lim_{x\to \infty} \sqrt{x^2 + 1} - x$

{{< youtube BiLG4Fl7hF0 >}}

### Example 

Here's a very similar looking example

Compute $\displaystyle \lim_{x\to \infty} \sqrt{x^2 + x} - x$

{{< youtube TT_Zrzog8Zo >}}

... so "$\infty - \infty$" can be 1/2? Yes! In fact it could be any number or even $\infty$.


## Infinite Limits at infinity

When functions continue to grow in the positive (or negative) direction without bound, we write 

$\displaystyle \lim_{x\to \infty} f(x) = \infty$ or $\displaystyle \lim_{x\to \infty} f(x) = -\infty$

But notes that $\infty$ is not a number, so our limit laws do not apply! 

As we saw above, "$\infty - \infty$" could be anything, so we have to be careful such as in the following example:

### Example
Evaluate
$$
\lim_{x \to \infty} 2x^2 - 3x
$$
**Solution**
Don't plug in $\infty$! Otherwise this might happen: 
![IMG_11A11CFAA02A-1|311x500, 50%](upload://cCmtARAm3XFNuedPzqy3ml0uG85.jpeg) 

Instead, factor first!
$$
\begin{align*} \lim_{x \to \infty} 2x^2 - 3x &= \lim_{x\to \infty} x(2x - 3) \end{align*}
$$
but since both $x$ and $2x-3$ grow to $\infty$ as $x$ grows large, we can say 
$$
 \lim_{x \to \infty} 2x^2 - 3x = \infty
$$


### Example

Evaluate 
$$
\lim_{x\to \infty} \dfrac{3x^2 - 4x + 5}{x+5}
$$

{{< youtube YSF3TYj_1nQ >}}