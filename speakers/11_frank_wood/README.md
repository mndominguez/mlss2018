# Probabilistic Programming

## Abstract

How do we engineer machines that reason? This is a question that has long vexed humankind. The answer to this question is fantastically valuable. There exist various hypotheses. One major division of hypothesis space delineates along lines of assertion: that random variables and probabilistic calculation are more-or-less an engineering requirement [Ghahramani, 2015, Tenenbaum et al., 2011] and the opposite [LeCun et al., 2015, Goodfellow et al., 2016]. The field ascribed to the former camp is roughly known as Bayesian or probabilistic machine learning; the latter as deep learning. The first requires inference as a fundamental tool; the latter optimization, usually gradient-based, for classification and regression. Probabilistic programming languages are to the former as automated differentiation tools are to the latter. Probabilistic programming is fundamentally about developing languages that allow the denotation of inference problems and evaluators that “solve” those inference problems. It can be argued that the rapid exploration of the deep learning, big-data/regression approach to artificial intelligence has been triggered largely by the emergence of programming languages tools that automate the tedious and troublesome derivation and calculation of gradients for optimization. Probabilistic programming aims to build and deliver a toolchain that does the same for probabilistic machine learning; supporting supervised, unsupervised, and semi-supervised inference. Without such a toolchain one could argue that the complexity of inference-based approaches to artificial intelligence systems are too high to allow rapid exploration of the kind we have seen recently in deep learning. These lectures introducing probabilistic programming will cover the basics of probabilistic programming from language design to evaluator implementation with the dual aim of explaining existing systems at a deep enough level that students should have no trouble adopting and using any of both the languages and systems that are currently out there and making it possible for the next generation of probabilistic programming language designers and implementers to use this as a foundation upon which to build.

## Links

* [The Anglican Probabilistic Programming System](https://probprog.github.io/anglican/)
* [probprog / ppaml-summer-school-2016   — Bitbucket](https://bitbucket.org/probprog/ppaml-summer-school-2016)
* [PPAML Summer School 2016](http://probmods.github.io/ppaml2016/)
* [GitHub - Tobias-Kohn/PyFOPPL: A FOPPL-Implementation in Python (Lisp-based Probabilistic Programming)](https://github.com/Tobias-Kohn/PyFOPPL)
* [Pyro Programming Language](http://pyro.ai/)
* [Stan Programming Language](http://mc-stan.org/)

## Other resources

* [Peter Norvig's (How to Write a (Lisp) Interpreter (in Python))](http://norvig.com/lispy.html)