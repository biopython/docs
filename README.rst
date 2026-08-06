Automatically generated Biopython documentation
===============================================

This is new as of Biopython 1.74, released 16 July 2019, initially covering
just the API documentation. With Biopython 1.84 released 28 June 2024 this
was expanded to hosting the main Tutorial as well - all built with Sphinx.

The idea is that code changes on https://github.com/biopython/biopython
already undergo continuous integration testing, and one of those jobs will
render the latest documentation, and for the master branch, push it to this
separate https://github.com/biopython/docs/ repository on the ``gh-pages``
branch, from where it can be automatically published using GitHub pages.

The intention is to use https://biopython.org/docs/dev/ for the documentation
for latest master branch, with ``/dev/`` replaced with the version for
releases, e.g. https://biopython.org/docs/1.88/ and a symlink such that
https://biopython.org/docs/latest/api/ points at the latest release (which
is updated with each release).

We would not expect or intend to edit the documentation directly in this
repository.

If you find a mistake in the documentation, please check the dev version,
and if it is still broken, please file an issue on the main repository:
https://github.com/biopython/biopython/issues
