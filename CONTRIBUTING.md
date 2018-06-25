# Contributing

NIST produces a lot of software, with open source code available
on [GitHub][_usng]. If you believe one of our repositories is
[*awesome*](AWESOME.md), please nominate it for inclusion in this
[list][_awsm].

## Nominations

To nominate a repository, file an [Issue][_issu] labeled "consider
repository-name" (in lower case) with a link in the comment field.

It would help peer review of the repository if you also paste the
[checklist](AWESOME.md) into the comment field, and check off
whatever applies. Don't worry if several boxes go unchecked:
it gives the developers room to grow!

## Guidelines for Contributors

To add a repository to the curated list, please

* Open [README.md][README.md] and add the link in a single line:
  `* [project-name](url) - A short description ends with a period.`
  Add only one link per Pull Request.
* Create a [Pull Request][_plrq] from your modified [README.md](README.md).
* Paste in and complete the [checklist](AWESOME.md). It should take
  10 minutes or less to complete.
* Don't mention `NIST` in the description as it's implied.
* Check your spelling and grammar. Remove any trailing whitespace.

The original [awesome.re][_awre] has more detailed instructions.

## Continuous Integration

Awesome NIST runs [markdown-link-check][_mdlc] on [Travis CI][_trvs]
once a week, and whenever commits are made to `master`, to make sure
links are not broken. After submitting a pull request, or before reviewing
one, please click on this handy badge to make sure everything is OK:

[![Build Status](https://travis-ci.org/usnistgov/awesome-nist.svg?branch=master)][_awci]

## Guidelines for Reviewers

Each Pull Request must be approved by at least one reviewer before merging.
If the repository is awesome, the review process should be painless. If it
misses the bar, reviewers are asked to provide friendly, clear feedback on
how to improve. If you (as a reviewer) file issues against the nominated
repository, please include links to those issues in your review.

While "awesome" is a subjective evaluation, there is a bar that all repositories
must clear. Please ensure that the prospective repository is fundamentally sound.

### Required Files

Developers signed the [Rules of Behavior][_grob], which requires both
LICENSE.md (or similar) and README.md (or similar).

#### LICENSE.md

LICENSE.md must contain the official [dedication to the public domain][_pub].
If parts of the work are subject to conditions, *e.g.* under [BSD][_bsd], [GPL][_gpl],
or [MIT][_mit] licensing terms, then the secondary license should be included
with a clear description of its scope: what specific subset of the repository
is *not* in the public domain? Why not?

#### README.md

README.md must contain [basic information][_gprg] including the
subject domain and contact information for the repository owner.

### Documentation

The developers' commitment to explaining themselves to the public should
be readily apparent.

#### High-Level Overview

README.md should summarize the context and scope of the software.
What niche or gap in capability does it address? How is it meant
to be used, and by whom?

#### Installation Instructions

Installation of the package and its dependencies should be automated
as much as possible. Best practice provides a `Makefile`, `Gemfile`,
`setup.py`, or similar, with prominent instructions for use. A satisfactory
alternative is to provide a list of dependencies, with suggested means
of installation.

Repositories that list no dependencies should be approached skeptically.

#### Examples and Tutorials

The developers should demonstrate how to use the software after installation,
including some preview of what output or behavior to expect. This is best
done through examples, with clear input and captured output. It is also
acceptable to link or show third-party usage of the software, *e.g.* in
a Jupyter notebook or as a web page hosted elsewhere.

#### Testing and Automation

Developers are strongly encouraged to include badges for continuous integration
services (*e.g.* [Travis-CI][_trvs], [Circle][_crcl], [AppVeyor][_appv]) that
automatically run a comprehensive test suite on each pull request. This
workflow substantially reduces the risk of introducing new bugs.

If automated integration is not available, for example when specialized
hardware is required, a manual test suite is acceptable, provided
clear directions, input files, and documentation of the expected output.

#### Guidance

The developers should provide clear guidelines for contributing code,
reporting bugs, requesting features, and seeking assistance.

#### Functionality

While not required, reviewers are encouraged to download the code and
check its core functionality.

### Acknowledgment

The Reviewer Guidelines borrow heavily from [JOSS][_joss].

## Badges

Any repository included in the list is eligible for an awesome badge like this:

[![Mentioned in Awesome NIST>](https://awesome.re/mentioned-badge.svg)][_awsm]

If you are the party responsible for merging a new repository into the list,
please submit a pull request against that repository's README.md (or similar)
to add the new badge.

<!--References-->
[_appv]: https://www.appveyor.com/
[_awci]: https://travis-ci.org/usnistgov/awesome-nist
[_awre]: https://github.com/sindresorhus/awesome/blob/master/contributing.md
[_awsm]: https://github.com/usnistgov/awesome-nist
[_crcl]: https://circleci.com/
[_copy]: https://www.govinfo.gov/content/pkg/USCODE-2014-title17/pdf/USCODE-2014-title17-chap1-sec105.pdf
[_gprg]: http://odiwiki.nist.gov/ODI/GitHubFAQ#Public_Repository_Guidelines
[_grob]: http://odiwiki.nist.gov/pub/ODI/GitHub/GitHub_ROBv5.pdf
[_issu]: https://github.com/usnistgov/awesome-nist/issues
[_joss]: https://joss.theoj.org/about#reviewer_guidelines
[_mdlc]: https://www.npmjs.com/package/markdown-link-check
[_plrq]: https://github.com/usnistgov/awesome-nist/pulls
[_trvs]: https://travis-ci.org/
[_usng]: https://github.com/usnistgov

<!--Licenses-->
[_bsd]: https://opensource.org/licenses/BSD-3-Clause
[_gpl]: https://opensource.org/licenses/gpl-license
[_mit]: https://opensource.org/licenses/MIT
[_pub]: https://inet.nist.gov/adlp/copyright-fair-use-licensing-statements-srd-data-software#software
