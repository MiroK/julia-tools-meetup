# NOTES FOR TOOLS MEETUP PRESENTATION ON JULIA

1. Julia's REPL `bash> Julia`. Press `?` or ']' for help/Pkg mode once inside REPL
```
bash> julia hello_world.jl SIMULA
```
2. [JUNO](https://junolab.org/) for developing (or VSCode with Julia plugin)
3. JIT-compiler idea (`ffc poisson.ufl`) produces `C++ code` that integrates with DOLFIN
4. For speed comparison with Python see the corresponding ``python_examples.ipynb
5. The main file with Julia things is `julia_examples.ipynb`