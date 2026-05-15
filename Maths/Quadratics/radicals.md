# Evaluating radicals 
**problem:** $\sqrt{35-10 \sqrt{10}}$
## Basic logic
To simplify such problems remeber the structre of the simplified radical, which is always in the following cases.
**case 1** In $\sqrt{a + b\sqrt{c}}$ if $c$ is prime then, the solution resembles $x + y\sqrt{c}$ 

**case 2** In $\sqrt{a + b\sqrt{c}}$ if $c$ is  NOT prime then, the solution resembles $x\sqrt{u} + y\sqrt{v}$ where $c = uv$ 

## Solving

Since the question is case 2, we need to find x and y such that
$$\sqrt{35-10 \sqrt{10}} = x\sqrt{2} + y\sqrt{5}$$

To solve we square on both sides

$$(\sqrt{35-10 \sqrt{10}})^2 = (x\sqrt{2} + y\sqrt{5})^2$$

$$ 35 -10\sqrt{10} = 2x^2 + 5y^2 + 2xy\sqrt{10}$$

From this we create a system of equations

 1 .$$ 35  = 2x^2 + 5y^2 $$
 2.
$$ -10\sqrt{10} = 2xy\sqrt{10}$$
which simplifies to...
$$ -5 =  xy$$

Here we can use simple guessing or by solving them. For questions like these guessing takes us to the domain of magic and luck, thus we will be solving this.
taking $y = \frac{-5}{x}$ and substituting in the first equation.
$$35 = 2x^2 + 5(\frac{-5}{x})^2$$
$$35x^2 = 2x^4 + 125$$

arranging the equation as a polynomial gives us:

$$2x^4 -35x^2 + 125 = 0$$
using substitution with $x^2 = u$

$$2u^2 -35u + 125 = 0$$
 Now this can be solved as anyother quadratic. It can be factored into
 $$(u-5)(2u-25)$$
so the factors are $x^2=5$ and $x^2 = \frac{25}{2}$. square rooting on both sides gives value for x, $x=\pm\sqrt{5}$ and $x = \pm \frac{5}{\sqrt{2}}$

Here you can take any one of the four answers and use it. Let us take $x = +\sqrt{5}$, as $y = \frac{-5}{x}$.
 $y$ would be $\frac{-5}{\sqrt{5}}$
 $$y= -\sqrt{5}$$ $$x=\sqrt{5}$$

Putting the values in the original equation:
$$(\sqrt{5})\sqrt{2}+(-\sqrt{5})\sqrt{5}$$
$$=\sqrt{10}-5$$

>**But remember:** Radicals should not be negative, Always check if the radical is greater than zero. Take the absolute value of two terms while checking inequality, beacuse $(\sqrt{10})^2<5^2$

$$\sqrt{10}<5$$ 

$$0 <5 -\sqrt{10}$$
So the required answer is 
$$5 -\sqrt{10}$$