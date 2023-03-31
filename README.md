# AsteroidGravityFields.jl

[![Stable](https://img.shields.io/badge/docs-stable-blue.svg)](https://Astroshaper.github.io/AsteroidGravityFields.jl/stable)
[![Dev](https://img.shields.io/badge/docs-dev-blue.svg)](https://Astroshaper.github.io/AsteroidGravityFields.jl/dev)
[![Build Status](https://github.com/Astroshaper/AsteroidGravityFields.jl/workflows/CI/badge.svg)](https://github.com/Astroshaper/AsteroidGravityFields.jl/actions?query=workflow%3ACI+branch%3Amain)
[![codecov](https://codecov.io/gh/Astroshaper/AsteroidGravityFields.jl/branch/main/graph/badge.svg?token=dJBiR91dCD)](https://codecov.io/gh/Astroshaper/AsteroidGravityFields.jl)
[![Aqua QA](https://raw.githubusercontent.com/JuliaTesting/Aqua.jl/master/badge.svg)](https://github.com/JuliaTesting/Aqua.jl)

Julia-based toolkit for dynamical simulations of planets and small solar system bodies.

## Installation

```julia
using Pkg
Pkg.add(url="https://github.com/Astroshaper/AsteroidGravityFields.jl")
using AsteroidGravityFields
```

You can update the module and run tests as follows.

```julia
Pkg.update("AsteroidGravityFields")
Pkg.test("AsteroidGravityFields")
```

## Gravity calculation for asteroids
You can calculate the precise gravity field of an irregularly shaped body, based on the constant-density polyhedron method (Werner & Scheeres, 1997).

### Example
Distribution of dynamical elevation on asteroid Itokawa. The color map ranges from -25 to 55 m.

![Gravity_Itokawa](https://user-images.githubusercontent.com/21192162/149465150-6cead63e-6027-402f-b866-5111dc5321a7.png)
