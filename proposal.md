# Community Software Analysis Proposal
Please edit this file and push to your repository.

## Software: MFEM 

MFEM is a finite element toolbox that provides the building blocks for developing finite element algorithms in a manner similar to that of MATLAB for linear algebra methods. It's primary audiance is anyone who is looking for a high-performance and scalable tool to enable finite element discretization and applicaton development. It is aimed to be run on a wide variety of machines, from laptops to supercomputers. MFEM is parallel and GPU ready, enables the use of various discretization methods, mesh types, and higher-order finite element spaces. MFEM also makes use of GLVis to visualize the meshes and finite element functions (Solutions) produced by MFEM.  

@article{Anderson_MFEM_A_Modular_2021,
author = {Anderson, Robert and Andrej, Julian and Barker, Andrew and Bramwell, Jamie and Camier, Jean-Sylvain and Cerveny, Jakub and Dobrev, Veselin and Dudouit, Yohann and Fisher, Aaron and Kolev, Tzanio and Pazner, Will and Stowell, Mark and Tomov, Vladimir and Akkerman, Ido and Dahm, Johann and Medina, David and Zampini, Stefano},
doi = {10.1016/j.camwa.2020.06.009},
journal = {Computers \& Mathematics with Applications},
month = {1},
pages = {42--74},
title = {{MFEM: A Modular Finite Element Methods Library}},
volume = {81},
year = {2021}
}

### Stats

| Description | Your answer |
|---------|-----------|
| Repository URL |  https://github.com/mfem/mfem/  |
| Main/documentation website |  https://mfem.org/  |
| Year project was started | First released July 2010  |
| Number of contributors in the past year | `git shortlog -se --since=2021-10-01` does not work for this repo |
| Number of contributors in the lifetime of the project | 100 |
| Number of distinct affiliations | >10 |
| Where do development discussions take place? | GitHub issues, pull-requests |
| Typical number of emails/comments per week? | ~40 is my guess from looking at all Issues, Discussions, Pull Requests, etc. |
| Typical number of commits per week? | ~15 |
| Typical commit size | `git log --shortstat` does not work for this repo |
| How does the project accept contributions? | "The MFEM team welcomes contributions at all levels: bugfixes; code improvements; simplifications; new mesh, discretization or solver capabilities; improved documentation; new examples and miniapps; HPC performance improvements; etc.
MFEM is distributed under the terms of the BSD-3 license. All new contributions must be made under this license.
Note also that MFEM has a Code of Conduct. By participating in the MFEM community, you agree to abide by its rules.
If you plan on contributing to MFEM, consider reviewing the issue tracker first to check if a thread already exists for your desired feature or the bug you ran into. Use a pull request (PR) toward the mfem:master branch to propose your contribution. If you are planning significant code changes or have questions, you may want to open an issue before issuing a PR. In addition to technical contributions, we are also interested in your results and simulation images, which you can share via a pull request in the mfem/web repo." |
| Does the project have an automated test suite? | yes |
| Does the project use continuous integration? | yes |
| Are any legal/licensing steps required to contribute? | All new contributions must be made under BSD-3 license. |

### Install and run

Check the following boxes when complete or add a note below if you
encountered a problem.

- [x] I have installed the software
- [x] I have run at least one example
- [x] I have run the test suite
- [x] The test suite passes

### Notes/concerns/risks

None at this time.

#### Note on copyright
Students retain copyright on any work done in completion of a CU
course, so you are authorized to sign a [contributor license
agreement (CLA)](https://en.wikipedia.org/wiki/Contributor_License_Agreement),
affirm a [developer's certificate of
origin (DCO)](https://en.wikipedia.org/wiki/Developer_Certificate_of_Origin),
etc.  If you have concerns about this, please note them and/or reach
out to Jed directly.
