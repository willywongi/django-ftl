============
Contributing
============

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.

You can contribute in many ways:

Types of Contributions
----------------------

Report Bugs
~~~~~~~~~~~

Report bugs at https://github.com/django-ftl/django-ftl/issues.

If you are reporting a bug, please include:

* Your operating system name and version.
* Any details about your local setup that might be helpful in troubleshooting.
* Detailed steps to reproduce the bug.

Fix Bugs
~~~~~~~~

Look through the GitHub issues for bugs. Anything tagged with "bug"
is open to whoever wants to implement it.

Implement Features
~~~~~~~~~~~~~~~~~~

Look through the GitHub issues for features. Anything tagged with "feature"
is open to whoever wants to implement it.

Write Documentation
~~~~~~~~~~~~~~~~~~~

django-ftl could always use more documentation, whether as part of the
official django-ftl docs, in docstrings, or even on the web in blog posts,
articles, and such.

Submit Feedback
~~~~~~~~~~~~~~~

The best way to send feedback is to file an issue at https://github.com/django-ftl/django-ftl/issues.

If you are proposing a feature:

* Explain in detail how it would work.
* Keep the scope as narrow as possible, to make it easier to implement.
* Remember that this is a volunteer-driven project, and that contributions
  are welcome :)

Get Started!
------------

Ready to contribute? Here's how to set up ``django-ftl`` for local development.

1. Fork the ``django-ftl`` repo on GitHub.
2. Clone your fork locally::

    $ git clone git@github.com:your_name_here/django-ftl.git

3. Install your local copy into a virtualenv. Assuming you have virtualenvwrapper installed, this is how you set up your fork for local development::

    $ mkvirtualenv django-ftl
    $ cd django-ftl/
    $ python setup.py develop

4. Create a branch for local development::

    $ git checkout -b name-of-your-bugfix-or-feature

   Now you can make your changes locally.

5. When you're done making changes, check that your changes pass flake8 and the
   tests, including testing other Python versions with tox::

        $ pip install -r requirements_test.txt
        $ pytest
        $ flake8 src tests

    To run tests against all supported versions::

        $ pip install tox
        $ tox


6. Commit your changes and push your branch to GitHub::

    $ git add .
    $ git commit -m "Your detailed description of your changes."
    $ git push origin name-of-your-bugfix-or-feature

7. Submit a pull request through the GitHub website.

We also have several linters and code formatters that we require use of,
including `flake8 <http://flake8.pycqa.org/en/latest/>`_, `isort
<https://github.com/timothycrosley/isort#readme>`_ and `black
<https://github.com/psf/black>`_. These are most easily add by using `pre-commit
<https://pre-commit.com/>`_:

* Install pre-commit globally e.g. ``pipx install pre-commit`` if you already
  have `pipx <https://github.com/pypa/pipx>`_.

* Do ``pre-commit install`` in the repo.

Now all the linters will run when you commit changes.

Pull Request Guidelines
-----------------------

Before you submit a pull request, check that it meets these guidelines:

1. The pull request should include tests.
2. If the pull request adds functionality, the docs should be updated. Put
   your new functionality into a function with a docstring, and add the
   feature to the list in README.rst.
3. The pull request should work for Python 3.6 at least. Check
   https://travis-ci.org/django-ftl/django-ftl/pull_requests and make sure that
   the tests pass for all supported Python versions.
