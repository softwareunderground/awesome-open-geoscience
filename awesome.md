# Our Definition of Awesome

If you want a project to be included in this `awesome` list, please check our definition of awesome. After all, it's a curation, not a collection. We base it loosely on the [manifesto of the Journal of Open Source Software (JOSS)](https://joss.readthedocs.io/en/latest/review_criteria.html). We say loosely, because their standards are higher. Our definition of awesome is more like guidelines to aim for and less like a strict set of rules. If you're new to coding and aren't sure if something qualifies, submit a pull request following the [contribution guidelines](contributing.md) and maintainers will help you out!

For now, we choose English as a common language for the list and as acceptable contributions to the list.

But **what is awesome?**

# Contents

- [Open Licensing](#choose-an-appropriate-license)
    - [Software](#software)
    - [Non - Software](#non-software)
    - [Unacceptable](#unacceptable-licenses)
- [Project Community Guidelines](#project-community-guidelines)
- [Publications and Cheat Sheets](#publicationsand-cheat-sheets)
- [Datasets](#datasets)
    - [Dataset Documentation](#dataset-documentation)
    - [Download Instructions](#download-instructions)
- [Software](#software)
    - [Software Documentation](#software-documentation)
        - [Readme](#readme)
        - [Installation Instructions](#installation-instructions)
        - [Examples and Tutorials](#examples-and-tutorials)
        - [API Documentation](#api-documentation)
    - [Software Tests](#software-tests)



# Choose an appropriate license

Need help?

**http://choosealicense.com/**

There should be an [Open Software Initiative](https://opensource.org/licenses/) or [Free Software Foundation](https://www.fsf.org/licensing/licenses/) approved license file for software included in the repository. Keep in mind that if you [haven't selected a license](http://choosealicense.com/no-license/), it very likely means the people are *not* allowed to reproduce, distribute or create derivative works.

## Software
Common licenses for software are [found here](http://choosealicense.com/):
* [Apache License 2.0](https://opensource.org/licenses/Apache-2.0)
* [BSD 3-Clause "New" or "Revised" license](https://opensource.org/licenses/BSD-3-Clause)
* [BSD 2-Clause "Simplified" or "FreeBSD" license](https://opensource.org/licenses/BSD-2-Clause)
* [GNU General Public License (GPL)](https://opensource.org/licenses/gpl-license)
* [GNU Lesser General Public License version 3](https://opensource.org/license/lgpl-3-0)
* [MIT license](https://opensource.org/licenses/MIT)

## Non-Software
Non-software typically use Creative Commons:
* [CC0](https://creativecommons.org/publicdomain/zero/1.0/)
* [CC-BY](https://creativecommons.org/licenses/by/4.0/).
* [CC-BY-SA](https://creativecommons.org/licenses/by-sa/4.0/).
* Code licenses like MIT, BSD, GPL, and so forth are **not** recommended for this type.

## Unacceptable Licenses
Some licenses that are ***not*** open and **cannot be included**:
* [No license](http://choosealicense.com/no-license/)
* [CC-BY-NC](https://creativecommons.org/licenses/by-nc/4.0/)
* [CC-BY-ND](https://creativecommons.org/licenses/by-nd/4.0/)
* [NASA Open Source Agreement](http://directory.fsf.org/wiki/License:NASA-OSA_v1.3)
* [Microsoft's Shared Source CLI, C#, and Jscript License](http://directory.fsf.org/wiki/License:Ms-SS)
* [Oculus Rift SDK License](http://directory.fsf.org/wiki/License:Oculus_VR_Rift_SDK_License)
* More exhaustive lists: [Software](http://www.gnu.org/licenses/license-list.html#NonFreeSoftwareLicenses) and [Others](http://www.gnu.org/licenses/license-list.html#NonFreeDocumentationLicenses)

| ▲ [Top](#our-definition-of-awesome) |
| --- |

# Project Community Guidelines

Awesome projects make it easy to get involved with. Tell the community, how you would like your issues and pull requests and how you credit them when they contribute to the software, report issues or problems with the software or simply seek support.


| ▲ [Top](#our-definition-of-awesome) |
| --- |

# Datasets

Awesome datasets need an open license and should be accessible. Ideally, they should be obtainable online, without sign-up. We appreciate that sometimes data portals with sign-ups are necessary. The sign-up for these portals *must be* automatic, meaning no long wait for response, and *cannot* limit usage of the data, meaning license restrictions that would make it non-open.

    Awesome: Open downloadable data like an S3 bucket, API, kaggle dataset, or data.world dataset.
    Awesome-ish (we get it, sometimes it's necessary): Data Portal with sign-up
    Bad (not acceptable): Contact the authors / maintainers and ask for the thing in the back of the cabinet.
    
## Dataset Documentation

Awesome datasets contain a full description of the data included and information about acquisition, processing and ideally reference implementations of loading and visualization of the adata.
    
## Download Instructions

Awesome datasets make it easy to obtain the data. Tell the community, how they can best obtain the data in the most stable way.


| ▲ [Top](#our-definition-of-awesome) |
| --- |

# Publications and Cheat Sheets

Awesome publications make it easy for the reader to navigate and obtain the information they need. These publications condense information in a unique way or offer a complete, exhaustive and comprehensive overview of a topic.


| ▲ [Top](#our-definition-of-awesome) |
| --- |

# Software

Awesome software is easy to install, beautifully documented with great examples and fully tested to ensure functionality. We go into more detail in the following sections.

## Software Documentation

For a project to be awesome, documentation should be awesome. Look at our awesome list, we're trying to make this look good and people appreciate it. All of this was achieved with good formatting via [Markdown](https://en.wikipedia.org/wiki/Markdown) in the Readme. If you really enjoy a project, but find the documentation is weak, that might be a great way to contribute to that project!

### Readme
The readme of the repository should be well formatted and contain the gist of the project, and links all the following points, that ideally should be part of the larger documentation.

### Installation Instructions

Awesome software makes it easy to use and include in your programming environment. In Python, Pypi and Conda make package management extremely powerful, ideally the software should be included in at least one of these. Gemfiles for Ruby, or NPM for nodejs are equally great for serving the software.

    Awesome: A package management file such as a Gemfile or requirements.txt or equivalent
    Awesome-ish (it's missing some of the magic): A list of dependencies to install
    Bad (not acceptable): Reliance on other software not listed by the authors

### Examples and Tutorials

Sometimes it can be a little non-obvious how to get the software started. An awesome project includes tutorials and examples how to use the software. This is another easy way to contribute to a project. If you think it is awesome, you've likely already made something that can be used as an example. 

### API Documentation

The API, or the collection of functionality should be described in the documentation. Making people guess if it's `xy.from_csv`, `xy.read_csv`, or `xy.load_csv` is less than Awesome. Better let them know and choose good defaults that can be changed regardless for all the edge cases that appear along the way.

    Uber-Awesome: All functions methods have tutorials and examples.
    Awesome: All functions/methods are documented including example inputs and outputs
    Awesome-ish (it could be so much more awesome though): Core API functionality is documented
    Bad (not acceptable): API is completely undocumented

## Software Tests

> Untested code is broken code.

Awesome projects make sure their code is working, ideally by automatic tests with full coverage of their software package. Remember many automatic Continuous Integration (CI) tools, offer discounts or free functionality to open source projects.

Tests can also be non-applicable for certain projects and are sometimes really hard to implement, if you're not sure whether the tests are acceptable, just let us know in the pull request and the maintainers will figure it out with you.

    Uber-Awesome: Full coverage of all tests, automatically executed and instructions to test by hand
    Awesome: An automated test suite hooked up to an external service such as Travis-CI or similar
    Awesome-ish (If we're in a really good mood): Documented manual steps that can be followed to objectively check the expected functionality of the software


| ▲ [Top](#our-definition-of-awesome) |
| --- |
