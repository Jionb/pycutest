## Contributing to PyCUTEst

Contributions to PyCUTEst are always welcome - thanks for your interest in getting this far!

### Reporting Bugs / Feature Suggestions

If you find a bug in PyCUTEst, or have a suggestion about how PyCUTEst can be improved, please
[create a Github issue](https://docs.github.com/en/issues/tracking-your-work-with-issues/creating-an-issue).
It would be helpful if you first check the [existing list of open issues](https://github.com/jfowkes/pycutest/issues)
to see if someone else has reported the same thing - in this case it would be better to comment on the existing issue
rather than creating a new one.

When reporting a bug, it would be helpful if you could include:

* An informative title and clear description
* A code snippet showing how the error occurred
* Any relevant Python output messages
* Information about your installation (e.g. operating system, Python version/distribution, PyCUTEst version)

### Submitting code changes

We are happy to accept code contributions from the PyCUTEst community.
If you have made a change (bugfix, new feature, documentation improvement, etc), then please
[submit a pull request](https://github.com/jfowkes/pycutest/pulls).
Github has [more information on pull requests](https://docs.github.com/en/pull-requests).
Please ensure that:

* Your description clearly explains your changes
* You have updated the documentation in `docs`.
We use [Sphinx](https://www.sphinx-doc.org/en/master/) to create our documentation.
You will need to install both the Sphinx and sphinx-rtd-theme packages.
* You have included relevant unit tests in `pycutest/tests`.
We use [nose](https://nose.readthedocs.io/en/latest/) to run our unit tests
but we do also provide a `tox.ini` for local testing using [tox](https://tox.wiki/en/latest/).

If you are fixing an issue, please reference the issue number in the pull request.

### Code of Conduct
We expect everyone in the PyCUTEst community to show respect to each other and behave appropriately at all times.
Abusive language, harassment and inappropriate/unprofessional language is not acceptable.
Instances of unacceptable behavior can be reported to the PyCUTEst team
([Jari](mailto:jaroslav.fowkes@stfc.ac.uk) and [Lindon](mailto:lindon.roberts@sydney.edu.au)).

Thanks!

PyCUTEst team (Jari & Lindon)