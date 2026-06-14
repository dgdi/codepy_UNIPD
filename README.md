[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dgdi/codepy_UNIPD)

# Python for Data Analysis — Course Material

This repository contains the lecture notes and exercises for the Python programming courses I taught at the **University of Padua**.

- **Laboratory: Coding** — MSc in Accounting, Finance & Business — 21 hours — 2023–2025
- **Coding: Introduction to Python** — MSc in Applied Economics — 21 hours — 2023

I am stepping away from this course to focus on a new research project on extreme weather events and the ability of our society to respond to climate change pressures through climate policy ([clicopre.com](http://www.clicopre.com)), and I hope making this public can be a small contribution to anyone setting out to learn or teach this material.

There is a widespread feeling that learning to code is becoming less useful as AI tools improve. I disagree: if anything, AI is expanding what can be built, which increases demand for people who understand what it actually implements, not just how to prompt it.

That said, the rise of LLMs and the proliferation of programming tools have changed how code is written, and the tools and environment choices in these notebooks are already somewhat dated. These materials are best treated as a foundation, useful for anyone building or redesigning a similar course, rather than a ready-to-use curriculum.

As part of the University of Padua's [Teaching for Learning](https://www.unipd.it/en/t4l-progetto) programme, which supports innovative teaching practices, I put together a micro-lecture on loops, one of the core concepts of the course, and then developed a gamified version of it to make the material more engaging. With LLMs, it is now quite straightforward to set up this kind of material, and I think the approach is promising. I haven't had the chance to extend it further, but I hope it might be useful to anyone thinking along similar lines.


---

## What this course covers

The course is an introduction to Python for data analysis. It starts from first principles: what an algorithm is, what a programming environment is, and how to set one up. It then works through the core ideas of programming: data types, control flow, and iteration. From there it moves to the packages that are standard in Python data analysis: **NumPy** for numerical computation, **Pandas** for data manipulation, and **Matplotlib/Seaborn** for visualization.

The material is organized as Jupyter notebooks combining explanations, worked examples, and exercises. Each notebook builds on the previous one, so working through them in order makes the most sense. Each lecture also comes with slides (handy if you don't have a Python environment set up) and a PDF version for those who prefer to read on paper. 

---

## Recommended reading

The notebooks stand on their own, so you can follow the course without anything else. That said, they were designed with **Python for Data Analysis** by Wes McKinney close at hand, an excellent (and totally free) book:

> [https://wesmckinney.com/book/](https://wesmckinney.com/book/)

For anyone who wants to go deeper or consolidate their understanding, reading both together is well worth it.

---

## Notebooks

### Core lectures

| Notebook | Topic |
|----------|-------------|
| [01](notebooks/lecture01_intro.ipynb) | Introduction |
| [02](notebooks/lecture02_setup.ipynb) | Environment setup |
| [03](notebooks/lecture03_basics.ipynb) | Programming basics |
| [04](notebooks/lecture04_atomicTypes.ipynb) | Atomic types |
| [05](notebooks/lecture05_compoundTypesIter.ipynb) | Compound types and iteration |
| [06](notebooks/lecture06_numpy.ipynb) | NumPy |
| [07](notebooks/lecture07_pandas.ipynb) | Pandas |
| [08](notebooks/lecture08_matplotlibSeaborn.ipynb) | Matplotlib & Seaborn |

### Gamification

| Notebook | Description |
|----------|-------------|
| [Micro-lecture](gamification/T4L_microLecture.ipynb) | Loops: standard micro-lecture |
| [Gamified](gamification/T4L_microLectureGamified.ipynb) | Loops: gamified version |
| [Gamified (solved)](gamification/T4L_microLectureGamified_solved.ipynb) | Loops: gamified version with solutions |


If you do not have a Python environment set up, you can run the notebooks directly in your browser using the Colab badge at the top of this page. It requires a Google account but no installation, and the free tier is more than enough.


---

## A note on my experience teaching it

The 21-hour format turned out to be a bit tight for this material. Around 25 hours would allow a better pace, with more time to work through examples together and less left as independent practice.

Anyone adapting this course under a tight time constraint faces a genuine design tension. Focusing on the fundamentals gives students a solid conceptual base, but leaves them unable to do much with real data until a follow-up course. Prioritizing the packages gets students working with data quickly, but at the cost of a shallower understanding of what the code is actually doing, which matters once they are outside university, where the stack may not rely on Python or these specific libraries. There's no clean answer; it depends on where this course sits in the broader curriculum.

---

## Contact

[Duccio Gamannossi degl'Innocenti](http://www.dgdi.me) — feel free to get in touch at [duccio.gamannossi@unipd.it](mailto:duccio.gamannossi@unipd.it)
