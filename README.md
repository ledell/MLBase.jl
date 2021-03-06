# MLBase.jl

Swiss knife for machine learning. 

[![Build Status](https://travis-ci.org/JuliaStats/MLBase.jl.svg?branch=master)](https://travis-ci.org/JuliaStats/MLBase.jl)
[![MLBase](http://pkg.julialang.org/badges/MLBase_release.svg)](http://pkg.julialang.org/?pkg=MLBase&ver=release)

This package does not implement specific machine learning algorithms. Instead, it provides a collection of useful tools to support machine learning programs, including:

- Data manipulation & preprocessing
- Score-based classification
- Performance evaluation (*e.g.* evaluating ROC)
- Cross validation
- Model tuning (*i.e.* search best settings of parameters)

**Notes:** This package depends on [StatsBase](https://github.com/JuliaStats/StatsBase.jl) and reexports all names therefrom. It also depends on [ArrayViews](https://github.com/lindahua/ArrayViews.jl) and reexports the ``view`` function.

### Resources

- **Documentation:** <http://mlbasejl.readthedocs.org/en/latest/>
- **Release Notes:** <https://github.com/JuliaStats/MLBase.jl/blob/master/NEWS.md>
