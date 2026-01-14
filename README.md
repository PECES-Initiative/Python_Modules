<!-- Title -->
<h1 align="center">
PECES Python Modules
</h1>

<!-- description -->
<p align="center">
  <strong>Python Teaching modules for teaching programming and earth science concepts. Developed during Programming in Earth Science Classroom Educational Workshop (PECES). </strong>
</p>

<!-- Information badges -->

<p align="center">
  <a href="https://mybinder.org/v2/gh/PECES-Initiative/Python_Modules/HEAD">
    <img alt="Binder tag)" src="http://mybinder.org/badge_logo.svg">
  </a>
</p>


During PECES 2026, we developed a series of Python teaching modules to introduce key programming and data science concepts. This repository is meant to be a growing list of activities that teachers can use and add to. We hope that these modules can be useful in classes and provide inspiratio for further modules. The modules are written as Python notebooks.

A similar set of [R teaching modules are availbile at a sister repository](https://github.com/PECES-Initiative/R_Modules).

# Using the Modules

# Adding New Modules

1. Fork this repository! This will make a copy of this repository in your personal GitHub account. [Here are instructions!](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo)
2. [Clone](https://github.com/git-guides/git-clone) the repository locally on your computer. In the terminal, go to the location you want the repository to be located and type:
```
git clone git@github.com:PECES-Initiative/Python_Modules.git
```

2. Make a branch! Pick a branch name, for example `sea_ice_module`. In the terminal type (but replace with your branch name):
```
git switch -c sea_ice_module
```

3. You can now add in your module (which should be a Python notebook `.ipynb` file) and any other content within your local copy. If you are adding any supplementary material other than a notebook, please make a sub-folder with your module name and add in your content.

4. Git [add](https://github.com/git-guides/git-add), [commit](https://github.com/git-guides/git-commit), and [push](https://github.com/git-guides/git-push) your content. Write your own commit message. Here In the terminal type:
```
git add .
git commit -m "Adding sea ice module - WRITE YOUR OWN DONT COPY THIS"
git push
```

5. Your code is now on your branch on your copy of the GitHub repository! Repeat Step 4 as you keep adding new content or updating your module! See below in the Binder section about how to keep track of what packages you use! 

6. When you module is done, open a Pull Request (PR) so that your module can be added to the main Github organization (since it is just on your fork right now!). [Here is step by step guide of how to open a PR](https://github.blog/developer-skills/github/beginners-guide-to-github-creating-a-pull-request/). Make sure you have completed the PR checklist that shows up once you have made the PR.

7. An administrator will check your module and approve your pull request!

8. You're done! Thank you for contributing! 

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
