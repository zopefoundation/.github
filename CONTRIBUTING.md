# Contributing to zopefoundation projects

The projects under the zopefoundation GitHub organization are open source and
welcome contributions in different forms:

* bug reports
* code improvements and bug fixes
* documentation improvements
* pull request reviews

For any changes in the repository besides trivial typo fixes you are required
to sign the contributor agreement. See
https://www.zope.org/developer/becoming-a-committer.html for details.

Please note that all contributions require assigning rights to your contributed
code, such as copyright, to the Plone Foundation. It follows that you must hold
these rights for the contribution, which is true for all code you wrote and
authored yourself. You may only contribute code from other authors if these
authors have signed the contributor agreement themselves, which means
"vendoring in" of third party code is not allowed.

## Contributing code changes

Once you are a contributor you can create branches inside the zopefoundation
repositories. Please use repository branches instead of creating private forks,
that makes it much easier for maintainers to try out or change pull requests
you create. (This is not required for your first pull request.)

See [Zope Development Culture](https://www.zope.org/developer/development-culture.html)
for details about coding standards.

Please try to write tests for your changes and fix tests your code changes break.
You should run the repository's tests locally, usually via
[tox](https://pypi.org/project/tox/). Most repositories will have a `tox.ini`
configuration for that purpose.

If you create a pull request please wait for approval from at least one other
contributor before merging. You should do that merge yourself, as it will
prove to everyone that you have signed the contributor agreement and thus have
the merge permission.
