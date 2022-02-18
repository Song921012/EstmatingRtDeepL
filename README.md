# EstmatingRtDeepL

Codes for the paper " Estimating time-varying reproduction number by deep learning techniques " submitted to JAAC.

## Instructions for running the code

- Step 1: Download Julia and Configuration Julia Environment. 
[Download Julia](https://julialang.org/downloads/)
One can search online for how to configure the julia environment.

- Step 2: Git Clone this repo or download the document.
- Step 3: cd to the repo folder. 
```
using Pkg
Pkg.instantiate(".")
```
Then many packages will be downloaded. My project includes many packages one may not use. You can also set up your personal project environments following the guide:
[Introduction · Pkg.jl](https://pkgdocs.julialang.org/v1/)
`DifferentialEquations.jl`,`DiffEqFlux.jl`, `Plots` ,`DataFrames.jl`, `CSV.jl` and `Flux.jl` are necessary.

- Step 4: Run the codes.

If one are not familiar with Julia, one can see for more details.
Julia Documents: [Julia Documentation · The Julia Language](https://docs.julialang.org/en/v1/)


