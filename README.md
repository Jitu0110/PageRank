# PageRank Tutorial

A hands-on Jupyter notebook that builds the PageRank algorithm from scratch, with visualizations at every step.

## Contents

0. Beginner's glossary of every term used
1. Random surfer intuition
2. Graph → column-stochastic transition matrix
3. Power iteration and convergence
4. Failure modes: dangling nodes and spider traps
5. Damping factor and the Google matrix
6. Monte Carlo random-surfer simulation vs. the math
7. PageRank as the dominant eigenvector (checked against `networkx.pagerank`)
8. Effect of the damping factor on ranks and convergence speed
9. PageRank on a larger scale-free graph, compared with in-degree
10. Personalized PageRank
11. Interactive β slider (with `ipywidgets`)
12. Summary and exercises

## Run it

```bash
pip install -r requirements.txt
jupyter notebook pagerank_tutorial.ipynb
```
