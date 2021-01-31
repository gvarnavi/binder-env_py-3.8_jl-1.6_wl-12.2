# Binder Environment (Python, Julia, and Wolfram Language workflow)

This is the git repository for a binder environment with the following kernels:  
- Python 3.8
- Julia 1.6.0-beta1
- WolframLanguage 12.2

The repository uses the [repo2docker Github Action](https://github.com/jupyterhub/repo2docker-action) to automatically build push changes to dockerhub and speed up the launch of binder.  

The notebooks are loaded using [nbgitpuller](https://github.com/jupyterhub/nbgitpuller),
e.g. from the [workflow seminar content repository](https://github.com/gvarnavi/python-julia-wolfram-workflow-nbs) using the binder link: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/gvarnavi/binder-env_py-3.8_jl-1.6_wl-12.2/main?urlpath=git-pull%3Frepo%3Dhttps%253A%252F%252Fgithub.com%252Fgvarnavi%252Fpython-julia-wolfram-workflow-nbs%26urlpath%3Dtree%252Fpython-julia-wolfram-workflow-nbs%252F%26branch%3Dmain)
