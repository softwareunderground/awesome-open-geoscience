# Our Definition of Awesome

If you want your project to be included in this `awesome` list, please check our definition of awesome. After all, it's a curation, not a collection. We base it loosely on the [manifesto of the Journal of Open Source Software (JOSS)](https://joss.readthedocs.io/en/latest/review_criteria.html). Additionally, for now, we choose English as a common language for the list and as acceptable contributions to the list.

But **what is awesome?**

## Contents

- [Open Licensing](#choose-an-appropriate-license)
    - [Software](#software)
    - [Non - Software](#non-software)
    - [Unacceptable](#unacceptable-licenses)
 - [Software Documentation](#software-documentation)
    - [Readme](#readme)
    - [Installation Instructions](#installation-instructions)
    - [Examples and Tutorials](#examples-and-tutorials)
    - [API Documentation](#api-documentation)
- [Software Tests](#software-tests)
- [Datasets](#datasets)
    - [Dataset Documentation](#dataset-documentation)
    - [Download Instructions](#download-instructions)
- [Publications and Cheat Sheets](#publicationsand-cheat-sheets)
- [Project Community Guidelines](#project-community-guidelines)


## Choose an appropriate license

Need help?

**http://choosealicense.com/**

There should be an [Open Software Initiative](https://opensource.org/licenses/) or [Free Software Foundation](https://www.fsf.org/licensing/licenses/) approved license file for software included in the repository. Keep in mind that if you [haven't selected a license](http://choosealicense.com/no-license/), it basically means the people are *not* allowed to reproduce, distribute or create derivative works.

### Software
Common licenses for software are [found here](http://choosealicense.com/):
* [Apache License 2.0](https://opensource.org/licenses/Apache-2.0)
* [BSD 3-Clause "New" or "Revised" license](https://opensource.org/licenses/BSD-3-Clause)
* [BSD 2-Clause "Simplified" or "FreeBSD" license](https://opensource.org/licenses/BSD-2-Clause)
* [GNU General Public License (GPL)](https://opensource.org/licenses/gpl-license)
* [GNU Library or "Lesser" General Public License (LGPL)](https://opensource.org/licenses/lgpl-license)
* [MIT license](https://opensource.org/licenses/MIT)

### Non-Software
Non-software typically use Creative Commons:
* [CC0](https://creativecommons.org/publicdomain/zero/1.0/)
* [CC-BY](https://creativecommons.org/licenses/by/4.0/).
* [CC-BY-SA](https://creativecommons.org/licenses/by-sa/4.0/).
* Code licenses like MIT, BSD, GPL, and so forth are **not** recommended for this type.

### Unacceptable Licenses
Some licenses that are ***not*** open and **cannot be included**:
* [No license](http://choosealicense.com/no-license/)
* [CC-BY-NC](https://creativecommons.org/licenses/by-nc/4.0/)
* [CC-BY-ND](https://creativecommons.org/licenses/by-nd/4.0/)
* [NASA Open Source Agreement](http://directory.fsf.org/wiki/License:NASA-OSA_v1.3)
* [Microsoft's Shared Source CLI, C#, and Jscript License](http://directory.fsf.org/wiki/License:Ms-SS)
* [Oculus Rift SDK License](http://directory.fsf.org/wiki/License:Oculus_VR_Rift_SDK_License)
* More exhaustive lists: [Software](http://www.gnu.org/licenses/license-list.html#NonFreeSoftwareLicenses) and [Others](http://www.gnu.org/licenses/license-list.html#NonFreeDocumentationLicenses)

## Software Documentation

Make your documentation awesome. Look at our awesome list, we're trying to make this look good and people appreciate it. Make your documentation look good as well. All of this was achieved with good formatting via [Markdown](https://en.wikipedia.org/wiki/Markdown) in the Readme.

### Readme
The readme of the repository should be well formatted and contain the gist of the project, and links all the following points, that ideally should be part of the larger documentation.

### Installation Instructions

Awesome software makes it easy to use and include in your programming environment. In Python, Pypi and Conda make package management extremely powerful, ideally the software should be included in at least one of these. Gemfiles for Ruby, or NPM for nodejs are equally great for serving the software.

    Good: A package management file such as a Gemfile or requirements.txt or equivalent
    OK-ish: A list of dependencies to install
    Bad (not acceptable): Reliance on other software not listed by the authors

### Examples and Tutorials

An awesome project includes tutorials and examples how to use the software. Sometimes it can be a little non-obvious how to get the software started. Help the community see, how awesome your software is.

### API Documentation

The API, or the collection of functionality should be described thoroughly in your documentation. Don't make people guess if it's `xy.from_csv`, `xy.read_csv`, or `xy.load_csv`. Better let them know and choose good defaults that can be changed regardless for all the edge cases that appear along the way.

    Uber-Awesome: All functions methods have tutorials and examples.
    Good: All functions/methods are documented including example inputs and outputs
    OK: Core API functionality is documented
    Bad (not acceptable): API is undocumented

## Software Tests

> Untested code is broken code.

Awesome projects make sure their code is working, ideally by automatic tests with full coverage of their software package. Remember many automatic Continuous Integration (CI) tools, offer discounts or free functionality to open source projects.

    Uber-Awesome: Full coverage of all tests, automatically executed and instructions to test by hand
    Good: An automated test suite hooked up to an external service such as Travis-CI or similar
    OK: Documented manual steps that can be followed to objectively check the expected functionality of the software
    Bad (not acceptable): No way for you to objectively assess whether the software works as intended
    
## Datasets

Awesome datasets need an open license and should be accessible. Ideally, they should be obtainable online, without sign-up. We appreciate that sometimes data portals with sign-ups are necessary. The sign-up for these portals *must be* automatic and *cannot* limit usage of the data.

    Good: Open downloadable data like an S3 bucket
    OK: Data Portal with sign-up
    Bad (not acceptable): Contact the authors / maintainers
    
### Dataset Documentation

Awesome datasets contain a full description of the data included and information about acquisition, processing and ideally reference implementations of loading and visualization of the adata.
    
### Download Instructions

Awesome datasets make it easy to obtain the data. Tell the community, how they can best obtain the data in the most stable way.

## Publications and Cheat Sheets

Awesome publications make it easy for the reader to navigate and obtain the information they need. These publications condense information in a unique way or offer a complete, exhaustive and comprehensive overview of a topic.

## Project Community Guidelines

Awesome projects make it easy to get involved with. Tell the community, how you would like your issues and pull requests and how you credit them when they contribute to the software, report issues or problems with the software or simply seek support.
