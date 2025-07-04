# Hello

My name is Jonah Pears <a href='https://orcid.org/0000-0003-4492-4072'><img border='0' align='center' alt='orcid id' src='https://orcid.org/assets/vectors/orcid.logo.icon.svg' width='15' height='15'></a> and I am currently a Postdoc researcher at the University of Kent, UK.
I am a member of the [PLAS](https://research.kent.ac.uk/programming-languages-systems/) research group, and am currently working on a project under Dr David Castro-Perez.
During my PhD I was supervised by Dr Laura Bocchi -- [I talk more about my PhD research here](#phd-research).

## Research

### Interests

`TODO`

### Publications

- (*Erlang 2024*) [Erlang on TOAST: Generating Erlang Stubs with Inline TOAST Monitors](https://doi.org/10.1145/3677995.3678192). <br> *Jonah Pears, Laura Bocchi, Raymond Hu*
- (*LMCS, to appear*) [Introducing TOAST: Safe Asynchronous Mixed-Choice For Timed Interactions](https://doi.org/10.48550/arXiv.2401.11197). <br> *Jonah Pears, Laura Bocchi, Maurizio Murgia, Andy King*
- (*COORDINATION 2023*) [Safe Asynchronous Mixed-Choice for Timed Interactions](https://doi.org/10.1007/978-3-031-35361-1_12). <br> *Jonah Pears, Laura Bocchi, Andy King*

> See [my profile on DBLP](https://dblp.org/pid/349/6325.html) for a better overview.

### PhD Research

I started by PhD in September of 2021 and have since passed my viva (January of 2025). During this time I worked on developing the theory of Timeout Asynchronous Session Types (TOAST for short) [[a](https://doi.org/10.1007/978-3-031-35361-1_12), [b](https://doi.org/10.48550/arXiv.2401.11197)], which I then implemented in Erlang as part of a (proof-of-concept) tool-chain [[c](https://doi.org/10.1145/3677995.3678192)] for generating correct-by-construction implementations, which also featured dynamic verification via runtime-monitoring -- I have made a short [blog post](https://jonahpears.github.io/2024/07/09/TOASTER.html) about this.

From a high-level view, the research aims to improve existing models that we can use to reason on the behaviour of, e.g., devices on the web, in order to facilitate them having a broader range of real-world applications.
At a lower-level:
(i) these models capture the behaviour of interactions in asynchronous, concurrent (and possibly distributed) systems,
and (ii) the extensions focused on improving their descriptive capabilities such that they can model the behaviour of [*timeouts*](https://en.wikipedia.org/wiki/Timeout_(computing)) (e.g., a server can receive a response within $n$ time units after which it may do something else).
([My thesis is available here](https://kar.kent.ac.uk/109393/1/136PhDThesis.pdf).)

## This Blog

I ~~plan~~ *would like* to use this blog to host articles that accompany my work (*though*, let us see how this goes).
The writing here will likely be less formal than usual, and will try to assume as little as possible about the reader.
