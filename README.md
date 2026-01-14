<!-- Title -->
<h1 align="center">
PECES Python Modules
</h1>

<!-- description -->
<p align="center">
  <strong>Python Teaching modules for teaching programming and earth science concepts. Developed during Programming in Earth Science Classroom Educational Workshop (PECES). </strong>
</p>

<!-- Information badges -->

[![Binder](http://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/PECES-Initiative/Python_Modules/HEAD)


During PECES 2026, we developed a series of Python teaching modules to introduce key programming and data science concepts. This repository is meant to be a growing list of activities that teachers can use and add to. We hope that these modules can be useful in classes and provide inspiratio for further modules.

A similar set of [R teaching modules are availbile at a sister repository](https://github.com/PECES-Initiative/R_Modules).

# Using the Modules

# Adding New Modules

# Using Binder


A Binder-compatible repo with an `environment.yml` file.

Access this Binder by clicking the blue badge above or at the following URL:

https://mybinder.org/v2/gh/PECES-Initiative/Python_Modules/HEAD

## Notes
The `environment.yml` file should list all Python libraries on which your notebooks
depend, specified as though they were created using the following `conda` commands:

```
conda activate example-environment
conda env export --from-history -f environment.yml
```

Note that the only libraries available to you will be the ones specified in
the `environment.yml`, so be sure to include everything that you need! 

Also note that if you skip the `--from-history`, conda may include OS-specific
packages in `environment.yml`, which you would have to manually prune from
`environment.yml`.  For example, confirmed macOS-specific packages that should
be removed are:

* libcxxabi=4.0.1
* appnope=0.1.0
* libgfortran=3.0.1
* libcxx=4.0.1
