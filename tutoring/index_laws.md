---
layout: notepage
---

# Index Laws

## Products

Expressions like ${}x^{3}{}$ mean: take 3 lots of ${}x{}$, and multiply them all together.

$$
\begin{align}
x^{3}&=x\cdot x\cdot x \\
x^{2}&=x\cdot x \\
\end{align}
$$

So if we multiply both of these:

$$
\begin{align}
x^{3}\cdot x^{2}&=(x\cdot x\cdot x)\cdot(x\cdot x) \\
&=x\cdot x\cdot x\cdot x\cdot x \\
&=x^{5}
\end{align}
$$

This means that we have our first rule:

$$
\begin{align}
\text{Rule 1:}&&\boxed{x^{a}\cdot x^{b}=x^{a+b}}
\end{align}
$$

## Powers of terms with powers

Have a look at the boxed equation above. What happens when ${}a=b{}$?

$$
x^{a}\cdot x^{a}=x^{a+a}=x^{2a}
$$

Notice that when something is multiplied by itself, that is what we call squaring:

$$
x^{a}\cdot x^{a}=(x^{a})^{2}
$$

So, combining these two equations, we have ${}(x^{a})^{2}=x^{2a}{}$. This strongly suggests that ${}(x^{a})^{b}{=x^{a\cdot b}}$. How could we prove this? 

The expression ${}{}(x^{a})^{b}{}$ says is: take ${}b{}$ lots of ${}x^{a}{}$, and multiply them together. It's the same as how ${}y^{3}{}$ means take 3 lots of ${}y{}$ and multiply them together, ${}y^{3}=y\cdot y\cdot y{}$. But here we have:

$$
\begin{align}
(x^{a})^{b} =\underbrace{ x^{a}\cdot x^{a}\cdot(\dots)\cdot x^{a} }_{ \text{\(b\) lots of \(x^{a}\)} }=x^{\overbrace{ a+a+(\dots)+a }^{ \text{\(b\) lots of these too} }}=x^{ba}
\end{align}
$$

Here, we made use of Rule 1, which let us combine the powers into a sum. We've provedq the statement that

$$
\begin{align}
\text{Rule 2:}&&\boxed{(x^{a})^{b}=x^{ab}}
\end{align}
$$

## Fractional powers

So, what does $x^{1/2}$ mean? It isn't immediately clear. Let's try looking at *two* lots of it, and see if that helps. We will use the above Rules, too.

$$
\begin{align}
x^{1/2}\cdot x^{1/2}&=x^{1/2+1/2}=x^{1}=x
\end{align}
$$

Something times itself is that thing squared, e.g. ${}a\cdot a=a^{2}{}$. So, the above equation also says:

$$
\begin{align}
(x^{1/2})^{2}=x
\end{align}
$$

You could have worked this out using Rule 2 as well. Rearranging to make ${}x^{1/2}{}$ the subject:

$$
x^{1/2}=\sqrt{ x }
$$

In fact, you can play the same game with ${}x^{1/n}{}$, where ${}n{}$ is a whole number. We just multiply ${}n{}$ lots of ${}x^{1/n}{}$, where before we multiplied 2 lots of ${}x^{1/2}{}$.

$$
\begin{align}
\underbrace{ x^{1/n}\cdot x^{1/n}\cdot(\dots)\cdot x^{1/n} }_{ \text{\(n\) lots of \(x^{1/n}\)} }&=x \\
(x^{1/n})^{n}&=x &\text{now, take the \(n\)th root of both sides:}\\
\implies x^{1/n}=\sqrt[n]{ x }
\end{align}
$$

In summary: we have shown that

$$
\begin{align}
\text{Rule 3: } &&\boxed{x^{1/n}=\sqrt[n]{ x }}
\end{align}
$$

###  Improper fractions

The next logical question is how to deal with powers that are improper fractions, like ${}x^{5/3}{}$. It is not so easy to apply the logic above (although it is possible - see if you can reason your way through!).

One way of looking at it is using Rule 2. In the same way we can 'join together' ${}(x^{a})^{b}{}$ into ${}x^{ab}{}$, we can do it in reverse and split up ${}x^{ab}{}$ into ${}(x^{a})^{b}{}$. For example, we could write

$$
\begin{align}
x^{5/3}&=(x^{5})^{1/3}=(x^{1/3})^{5}
\end{align}
$$

This works because multiplication doesn't care about the order of terms: ${}a\cdot b=b\cdot a{}$. Using Rule 3, we can rewrite the middle and RHS of the above as:

$$
x^{5/3}=\sqrt[3]{ x^{5} }=(\sqrt[3]{ x })^{5}
$$

So, in general:

$$
\begin{align}
\text{Rule 4: } &&\boxed{x^{a/b}=\sqrt[b]{ x^{a} }=(\sqrt[b]{ x })^{a}}
\end{align}
$$

I try to imagine the maths moving on the page when I do algebra, and I see this as the ${}a{}$ staying in place, and the ${}b{}$ moving around the ${}x{}$ until it is in position, then a square root sign appearing. Remembering how the letters move around has always seemed easier than remembering the formula itself for me.

## Zero as a power

It turns out that ${}x^{0}=1{}$, no matter what ${}x{}$ is. We can work this out by observing that ${}(x^{0})^{n}=x^{0\cdot n}=x^{0}{}$. Both 1 and 0 have the property that if you raise them to a power, they are unchanged. What sets them apart? If you multiply a number by zero, that number gets turned into zero. However, if you multiply a number by 1, that number doesn't change. So, let's look at ${}x^{0}\cdot x^{n}{}$, for any number ${}n{}$:

$$
\begin{align}
x^{0}\cdot x^{n}=x^{0+n}=x^{n}
\end{align}
$$

We've multiplied a number ${}x^{n}{}$ by ${}x^{0}{}$. Did it become zero? No! It stayed as ${}x^{n}{}$. Hence, ${}x^{0}\neq 0{}$. In fact:

$$
\begin{align}
\text{Rule 5:}&&\boxed{x^{0}=1} 
\end{align}
$$

## Negative powers

When we looked at ${}x^{1/2}{}$ above, we tried seeing what happened if we multiplied two lots of it together. This turned out to be helpful. We can do a similar trick with ${}x^{-n}{}$. What happens if we multiply it by ${}x^{n}{}$?

$$
x^{-n}\cdot x^{n}=x^{n-n}=x^{0}=1
$$

Now let's rearrange to make ${}x^{-n}{}$ the subject (after all, that's what we're interested in)

$$
x^{-n}=\frac{1}{x^{n}}
$$

And therefore we have another Rule:

$$
\begin{align}
\text{Rule 6:}&&\boxed{x^{-n}=\frac{1}{x^{n}}} 
\end{align}
$$

## Divisions

Let's look at ${}x^{a}\div x^{b}{}$. Recall that you can write a division as a multiplication if you flip the thing on the right:

$$
\begin{align}
x^{a}\div x^{b}&=x^{a}\cdot \frac{1}{x^{b}} \\
&=x^{a}\cdot x^{-b} \\
&=x^{a-b}
\end{align}
$$

Hence:

$$
\begin{align}
\text{Rule 7:}&&\boxed{x^{a}\div x^{b}=x^{a-b}} 
\end{align}
$$