# Replicating Schelling's Dynamic Models of Segregation in Julia

This repository introduces the [Julia programming language](https://julialang.org/) by replicating [Schelling, Thomas C. "Dynamic models of segregation." Journal of mathematical sociology 1.2 (1971): 143-186.](https://scholar.google.com/scholar?cluster=747074237233961749&hl=en&as_sdt=0,5).

## Why Julia?

[From the creator's themselves:](https://julialang.org/blog/2012/02/why-we-created-julia/)

> We are greedy: we want more.
>
> We want a language that's open source, with a liberal license. We want the speed of C with the dynamism of Ruby. We want a language that's homoiconic, with true macros like Lisp, but with obvious, familiar mathematical notation like Matlab. We want something as usable for general programming as Python, as easy for statistics as R, as natural for string processing as Perl, as powerful for linear algebra as Matlab, as good at gluing programs together as the shell. Something that is dirt simple to learn, yet keeps the most serious hackers happy. We want it interactive and we want it compiled.

## Why Schelling's Model?

It's a classical paper in the social science literature with wide influence in urban studies, economics, sociology among other disciplines. The model is brilliantly simple - one could replicate it with a checkers board set, with remarkably profound conclusions.

## Why another tutorial?

There are many other tutorials and introductory material out there that I recommend and have learnt from:

- [The Reference Docs](https://docs.julialang.org/en/v1/)
- [Quantitative Economics with Julia](https://julia.quantecon.org/)
- [From Zero to Julia](https://techytok.com/from-zero-to-julia/)
- [Julia for Data Science](https://ucidatascienceinitiative.github.io/IntroToJulia/)
- [And many others...](https://julialang.org/learning/)

I take a slightly different approach. Rather than going over concepts (Types, Loops, Control Statements etc.), I take a problem-driven approach - given a particular problem, how can we solve it using Julia. This is my favourite way to learn something new, try it on an actual problem and see where we end up. The idea is that this will be an incremental learning repository where we learn something new and apply it to our problem.

## Pre-requisities and Setup

Some prior experience in lanaguages like Python or R and knowledge of git would be useful.

For development, this code is written in Julia v1.4, using both the Jupyter Notebook inteface as well as the vscode plugin for editing .jl files.

Follow the instructions over here to setup [Jupyter for Julia](https://julia.quantecon.org/getting_started_julia/getting_started.html) and [julia-vscode plugin](https://www.julia-vscode.org/docs/stable/setup/).
