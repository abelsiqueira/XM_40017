```@meta
CurrentModule = XM_40017
```
# Programming Large-Scale Parallel Systems (XM_40017)

Welcome to the interactive lecture notes of the [Programming Large-Scale Parallel Systems course](https://studiegids.vu.nl/EN/courses/2023-2024/XM_40017#/) at [VU Amsterdam](https://vu.nl)!

## What

This page contains part of the course material of the Programming Large-Scale Parallel Systems course at VU Amsterdam.
We provide several lecture notes in jupyter notebook format, which will help you to learn how to design, analyze, and program parallel algorithms on multi-node computing systems.
Further information about the course is found in the study guide
([click here](https://studiegids.vu.nl/EN/courses/2023-2024/XM_40017#/)) and our Canvas page (for registered students). 

!!! note
    This page contains only part of the course material. The rest is available on Canvas. In particular, **the lecture notes in this public webpage do not fully cover all topics in the final exam**.

## How to use this page

You have two main ways of running the notebooks:

- Download the notebooks and run them locally on your computer (recommended)
- Run the notebooks on the cloud via [mybinder.org](https://mybinder.org) (high startup time).

You also have the static version of the notebooks displayed in this webpage for quick reference. At each notebook page you will find a green box with links to download the notebook or to open in on mybinder.

## How to run the notebooks locally

To run a notebook locally follow these steps:

- Install Julia (if not done already). More information in [Getting started](@ref).
- Download the notebook.
- Launch Julia. More information in [Getting started](@ref).
- Execute these commands in the Julia command line:

```
julia> using Pkg
julia> Pkg.add("IJulia")
julia> using IJulia
julia> notebook()
```
- These commands will open a jupyter in your web browser. Navigate in jupyter to the notebook file you have downloaded and open it.

## Authors

This material is created by [Francesc Verdugo](https://github.com/fverdugo/) with the help of Gelieza Kötterheinrich. Part of the notebooks are based on the course slides by [Henri Bal](https://www.vuhpdc.net/henri-bal/).


## License

All material in this page that is original to this course may be used under a [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.


## Acknowledgment

This page was created with the support of the Faculty of Science of [Vrije Universiteit Amsterdam](https://vu.nl) in the framework of the project "Interactive lecture notes and exercises for the Programming Large-Scale Parallel Systems course" funded by the "Innovation budget BETA 2023 Studievoorschotmiddelen (SVM) towards Activated Blended Learning".