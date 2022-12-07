Protection Profile for Session Border Controlers
===============
![Master Badges](https://img.shields.io/badge/Build-master-black.svg)
![Build](https://github.com/commoncriteria/sbc/workflows/Build/badge.svg)
![Validate](https://github.com/commoncriteria/sbc/workflows/Validate/badge.svg)

![Last QuickBuilt Branch](https://raw.githubusercontent.com/commoncriteria/sbc/gh-pages/build-branch-badge.svg)
[![Validation](https://raw.githubusercontent.com/commoncriteria/sbc/gh-pages/validation.svg)](https://github.com/commoncriteria/sbc/blob/gh-pages/ValidationReport.txt)
[![SanityChecks](https://raw.githubusercontent.com/commoncriteria/sbc/gh-pages/warnings.svg)](https://github.com/commoncriteria/sbc/blob/gh-pages/SanityChecksOutput.md)
[![SpellCheck](https://raw.githubusercontent.com/commoncriteria/sbc/gh-pages/spell-badge.svg)](https://github.com/commoncriteria/sbc/blob/gh-pages/SpellCheckReport.txt)
[![QuickBuild](https://github.com/commoncriteria/sbc/actions/workflows/quick_build.yml/badge.svg)](https://commoncriteria.github.io/sbc)


[![GitHub issues Open](https://img.shields.io/github/issues/commoncriteria/sbc.svg?maxAge=2592000)](https://github.com/commoncriteria/sbc/issues) 
![license](https://img.shields.io/badge/license-Unlicensed-blue.svg)

This repository hosts the draft version of the Protection Profile for SBC based on the 
This repository is used to facilitate collaboration and development on the draft document. 
See the [release](#Release-Version) section if you are looking for the officially released version for evaluations. 
A list of products that have passed evaluation against this Protection Profile can be found [here](QQQQ).

## Draft Version

* [PP-Module for SBC](https://commoncriteria.github.io/pp/sbc/sbc-release.html) (html)
* [PP-Module for SBC](https://commoncriteria.github.io/pp/sbc/sbc-release.pdf) (pdf)
* [Quick Build Directory](https://commoncriteria.github.io/sbc)

## Release Version
* [PP-Module for SBC](https://www.niap-ccevs.org/Profile/Info.cfm?PPID=478&id=478)

## Contributing

If you are interested in contributing directly to future versions the this Protection Profile, please consider joining the NIAP technical community.
* [How to join the NIAP Technical Community (Mailing list and updates)](https://www.niap-ccevs.org/NIAP_Evolution/tech_communities.cfm)

## Feedback

Questions, comments, and fixes can be submitted to the [repository issue tracker](https://github.com/commoncriteria/sbc/issues)

## Quickstart
To clone this project along with its _transforms_ submodule run:

````
  git clone --recursive git@github.com:commoncriteria/qqqq.git
````
To pull updates from the upstream _transforms_ submodule and commit them run:
````
 git submodule update --remote transforms
 git add transforms
 git commit
````

### Development Info
[Help working with Transforms Submodule](https://github.com/commoncriteria/transforms/wiki/Working-with-Transforms-as-a-Submodule)

## Repository Content
* input - Contains the 'meat' of the project. It's the input content (in XML form) that gets transformed to readable html.
* output - The output directory where the html is placed after transformation.
* output/images - The directory where images are stored
* transforms - Points to the transform subproject which is really a repository for resources shared amongst many Common Criteria projects. You shouldn't need to modify it.

## Links 
* [National Information Assurance Partnership (NIAP)](https://www.niap-ccevs.org/)
* [Common Criteria Portal](https://www.commoncriteriaportal.org/)

## License
See [License](./LICENSE)
