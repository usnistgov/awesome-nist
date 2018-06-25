# Awesome NIST Guide to Awesomeness

## Baseline Checklist *(prerequisite)*

The repository complies with our [Terms of Use][_ntos].

- [ ] README.md or README.rst clearly describes, in layman's terms:
  - [ ] goals of the repository and project
  - [ ] whether the code is usable (pre-release, production-ready, or in-between?)
  - [ ] how to get in touch with the development team
  - [ ] acknowledges collaborators and reused code, if applicable
- [ ] Documentation exists, in README.md or separately, and explains
  - [ ] dependencies, if any
  - [ ] installation process
  - [ ] basic usage
- [ ] LICENSE.md or LICENSE.txt dedicates the software to the public domain using
      [approved language][_dirl], preferably a duplicate of [LICENSE.md][_stdl]

## Maturity Checklist *(bonus)*

The repository demonstrates mature development practices, including
integration with services that improve maintainability and an overall
commitment to helping newcomers quickly achieve proficiency.

- [ ] Developers leverage GitHub as a communication tool
  - [ ] Description, Website, and Topics fields are meaningfully populated
  - [ ] Closed pull requests indicate a [branching][_brwf] or otherwise
        consistent workflow
  - [ ] Merged pull requests underwent formal [code review][_ghrv]
  - [ ] Badges in README.md display positive status messages
  - [ ] CONTRIBUTING.md provides clear guidance on
    - [ ] where the stable code resides, if not on `master`
    - [ ] expected workflow and release process (rolling, [semver][_smvr], or other)
- [ ] Self-documenting code with link to online docs
  - [ ] using [Doxygen][_doxy], [Docstrings][_docs], or similar
  - [ ] hosted by [NIST][_nstp], [readthedocs][_rtfd], or similar
  - [ ] provides worked examples and tutorials
- [ ] Tests automatically run on a continuous integration service,
      *e.g.* [Travis CI][_trvs], [Circle][_crcl], or similar
- [ ] Insights tab on GitHub indicates a healthy software environment
  - [ ] Contributors shows a history of commits (not just one)
  - [ ] Dependency Graph does not flag security vulnerabilities
- [ ] Git branches are used appropriately

## Further Justification

In addition to the generic items selected above, this repository is *awesome*
because...

<!--References-->
[_brwf]: https://git-scm.com/book/en/v2/Git-Branching-Branching-Workflows
[_crcl]: https://circleci.com
[_dirl]: https://www.nist.gov/director/licensing
[_docs]: https://www.python.org/dev/peps/pep-0257/
[_doxy]: https://www.stack.nl/~dimitri/doxygen
[_ghrv]: https://help.github.com/articles/about-pull-request-reviews/
[_nstp]: https://pages.nist.gov
[_ntos]: https://github.nist.gov
[_rtfd]: https://readthedocs.org
[_smvr]: https://semver.org
[_stdl]: https://github.com/usnistgov/awesome-nist/blob/master/LICENSE.md
[_trvs]: https://travis-ci.org
