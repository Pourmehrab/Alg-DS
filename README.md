# Algorithms and Data Structures
[TOC]

## Usefull Online Courses
- [6.006 Introduction to Algorithms](https://goo.gl/NEvCVt)
- [6.046J / 18.410J Design and Analysis of Algorithms](https://goo.gl/4Hr3bY)
- [6.046J / 18.410J Introduction to Algorithms (SMA 5503)](https://goo.gl/UK2nZo)
- [6.00 Introduction to Computer Science and Programming](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-00-introduction-to-computer-science-and-programming-fall-2008/)
- [COP5536 Advanced Data Structures](https://www.cise.ufl.edu/~sahni/cop5536/)
- [Algorithms: Design and Analysis](https://lagunita.stanford.edu/courses/course-v1:Engineering+Algorithms1+SelfPaced/info)
- [Algorithms: Design and Analysis, Part 2](https://lagunita.stanford.edu/courses/course-v1:Engineering+Algorithms2+SelfPaced/info)

##  Graph Problems
- [Detect Cycle in a Directed Graph (DFS)](https://www.geeksforgeeks.org/detect-cycle-in-a-graph/)
- [Assignment Problem (Hungarian)](https://www.youtube.com/watch?v=rrfFTdO2Z7I)

## Famous Puzzles:
- [N Queen Problem (Recursive and DP)](https://www.geeksforgeeks.org/backtracking-set-3-n-queen-problem/)
- [Tower of Hanoi (Recursive)](https://www.geeksforgeeks.org/c-program-for-tower-of-hanoi/)

## Challenging Math Problems
- [The Putnam Archive](http://kskedlaya.org/putnam-archive/)

## Sharing Jupyter Notebook
- Gist
- [turn repo interactive](https://mybinder.org/)

## conda/python
- `conda search python=3.7`
- [Data Classes in Python 3.7](https://realpython.com/python-data-classes/)
- [Scipy Lecture Notes](http://www.scipy-lectures.org)
- [full stack python](https://www.fullstackpython.com/table-of-contents.html)


## sphinx
- include `sphinx_rtd_theme==0.3.0` in `requirement.txt`
- `pip install easydev `
- http://www.sphinx-doc.org/en/master/usage/restructuredtext/basics.html
- http://build-me-the-docs-please.readthedocs.io/en/latest/Using_Sphinx/OnReStructuredText.html
- `attention, caution, danger, error, hint, important, note, tip, warning`
- http://datadesk.latimes.com/posts/2012/01/sphinx-on-github/
- http://sphinx-bootstrap-theme.readthedocs.io/en/latest/examples.html
- https://daler.github.io/sphinxdoc-test/includeme.html#makefile-changes
- http://www.sphinx-doc.org/en/stable/config.html#confval-extensions
- https://thomas-cokelaer.info/tutorials/sphinx/docstring_python.html
- http://thomas-cokelaer.info/tutorials/sphinx/rest_syntax.html



## requirement.txt
- Do `pip3 install pipreqs` or `conda install pipreqs`
- `requirements.txt` is created using `pipreqs /path/to/project`. Warp the address with "".)

## Microsoft Visual C++ Build Tools
- http://landinghub.visualstudio.com/visual-cpp-build-tools
- Microsoft Visual C++ 2015 Redistributable Package (x64) [here](https://www.microsoft.com/en-US/download/details.aspx?id=53587)

## PyCharm
- Some useful plugins are `Markdown Support`, `CSV Plugin`, `RainGlow`, and `CodeGlance`, `statistics`.

## CPLEX:
- `model.write("model.lp") , model.get_stats() , model.solution.get_linear_slacks() , model.parameters.read.datacheck.set(0,1, or 2) , model.parameters.tune_problem()`
- Refer to ``IBM(R) ILOG CPLEX Python API Reference Manual`` for CPLEX usage using Python
- [solution stats](https://www.ibm.com/support/knowledgecenter/SSSA5P_12.8.0/ilog.odms.cplex.help/refcallablelibrary/macros/Solution_status_codes.html)
- ```f = ./log/cplex_run.log
    model.set_log_stream(f)
    model.set_error_stream(f)
    model.set_warning_stream(f)
    model.set_results_stream(f)```
- [network optimization](https://www.ibm.com/support/knowledgecenter/SSSA5P_12.6.3/ilog.odms.cplex.help/CPLEX/UsrMan/topics/cont_optim/network/09_invoke.html)


## Git:
- [oh shit git](http://ohshitgit.com/)
- To remove a local branch from your machine: `git branch -d {the_local_branch}` (use -D instead to force deleting the branch without checking merged status)
- To remove a remote branch from the server: `git push origin --delete {the_remote_branch}`

## jupyterlab
- R kernel:	`conda install -c r r-irkernel`
- [install packages inside jupyter](http://jakevdp.github.io/blog/2017/12/05/installing-python-packages-from-jupyter/)


## Visualization
- [Fundamentals of Data Visualization](http://serialmentor.com/dataviz/)
- [py graph gallery](https://python-graph-gallery.com/?platform=hootsuite)
- [perfect graph](https://en.wikipedia.org/wiki/Book:Perfect_Graphs)
- matplotlib
    - http://pbpython.com/effective-matplotlib.html
    - https://matplotlib.org/users/mathtext.html
- [tableau interactive resume](https://public.tableau.com/en-us/s/blog/2016/09/how-create-interactive-resume-tableau)
- [TikZ samples](https://github.com/xiaohanyu/awesome-tikz)


## Probability/Stats/ML
- http://nbviewer.jupyter.org/url/norvig.com/ipython/Probability.ipynb
- https://blogs.sas.com/content/subconsciousmusings/2017/04/12/machine-learning-algorithm-use/?utm_source=twitter&utm_medium=cpc&utm_campaign=analytics-global&utm_content=US_tap
- http://www.degeneratestate.org/posts/2018/Mar/24/causal-inference-with-python-part-1-potential-outcomes/
- https://github.com/zonination/perceptions/blob/master/README.md


## Optimization
- http://www.scipy-lectures.org/advanced/mathematical_optimization/

## Parallel
- https://tdhopper.com/blog/parallelizing-a-python-function-for-the-extremely-lazy/
- https://medium.com/@alairock/asyncio-basics-in-python-29bf30cf254f

## Network/graphs
- http://networkx.github.io/
- http://graphclasses.org/
- https://developers.google.com/optimization/cp/cp_solver

## Other
- https://www.dataquest.io/blog/introduction-to-ensembles/
- http://www.norvig.com/
- https://rushter.com/blog/pickle-serialization-internals/
- https://pyformat.info/
- http://matt.might.net/articles/books-papers-materials-for-graduate-students/

## Cool collocations
- <A claim>. To illustrate why this is so, ... .
- For a rigorous proof of Little’s theorem, see Ross (1970). We content ourselves with the following heuristic discussion.
- Before using these important results, we present an intuitive justification of ...
- To verify this claim, note that ...
- The running time of ... is dominated by the time spent in the ...
- In this section, we assume without loss of generality that ...
- Then it sorts the entire deck again on the second-least significant digit and recombines the deck in a like manner.
- ...elicits...
- Figure 9.1 helps us to visualize this bookkeeping.
- Although the mechanics of red-black trees are somewhat intricate, you can glean most of their properties from the chapter without studying the mechanics in detail.

## Career
[google](https://careers.google.com/), [valassis](https://www.valassis.com)
