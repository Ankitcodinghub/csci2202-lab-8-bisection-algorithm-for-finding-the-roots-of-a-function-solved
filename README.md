# csci2202-lab-8-bisection-algorithm-for-finding-the-roots-of-a-function-solved
**TO GET THIS SOLUTION VISIT:** [CSCI2202 Lab 8-Bisection algorithm for finding the roots of a function Solved](https://www.ankitcodinghub.com/product/csci2202/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;116967&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSCI2202 Lab 8-Bisection algorithm for finding the roots of a function Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
• Implement the bisection algorithm for finding the roots (zeros) of a function.

(1) (a) Write and test a Boolean function: hasComplexRoots(a, b, c), that returns True if the quadratic ax2+bx+c = 0 has em complex roots and False otherwise.

Note: The roots of the quadratic above are given by

(b) Using the function hasComplexRoots(a, b, c), to compute the probability P1(n) (the Monte Carlo estimate) that the quadratic has complex roots, assuming that the coefficients are drawn from a uniform random distribution on [0,1], (using random.random()). Run the simulation for n = 1000.

Repeat the experiment to compute P2(n) , where the coefficients are chosen from a normal distribution (random.normalvariate(0, 1)) with mean mu = 0 and std. deviation sigma = 1.

(2) • Implement a function bisection, that can operate on an arbitrary function. Your program should accept: a function (f – to find the roots/zeros of); two endpoints (x0,x1); a tolerance limit () and the max. number of iterations m as input parameters. The function bisection should output the final approximation to the root (zero) and the number of iterations it took to find the root. The program should make sure that the initial interval is acceptable for this method (i.e. (i) it should be greater than the tolerance () and (ii) must contain a zero of f (i.e. f(x0) · f(x1) &lt; 0). Recall that the max. iterations n to achieve an error bound of:

which worked out (see class notes) to be:

Set this value as your max. iterations m .

• The bisection method for finding roots was covered in class. The algorithm is in the notes on-line.

• Note1: Define Python functions for function evaluations in the problems: Note2: You can return two values from a python function using return rootApprox, iterCount as the final line in the function. Make sure to pick up both values in the calling code as: xr, numIter = bisection(a, b, tol, f) for example.

• Use the bisection(f, x0, x1, tol, m) to compute (i) the positive root of f(x) = x2 − x − 1. The positive root of this equation is known to lie in the interval [1,2]. Use a tolerance of f 10−8. (ii) Repeat this exercise for the negative root:. Search in [−1,0]. (The solution to (i) is the Golden Ratio: Φ the limit of

1

2

the ratio of consecutive Fibonacci numbers. The solution to (ii) is known to be −1/Φ).

• Use your program to compute the roots of f1(x) = x3 − 3x − 1 on [0, 1], f2(x) = x3 − 2sin(x) on [0.5, 2], f3 = tan(x) − 2x on [0, 2].

Start by plotting the functions to find a reasonable interval to bracket the root and print x, | f(x) | and the number of iterations required for convergence.
