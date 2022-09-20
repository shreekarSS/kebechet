.. begin


========
.
.. image:: https://img.shields.io/github/v/tag/thoth-station/kebechet?style=plastic
  :target: https://github.com/thoth-station/kebechet/tags
  :alt: GitHub tag (latest by date)

.. image:: https://quay.io/repository/thoth-station/kebechet-job/status
  :target: https://quay.io/repository/thoth-station/kebechet-job?tab=tags
  :alt: Quay - Build

Kebechet is an extensible system of repository managers for GitHub, GitLab, and
Pagure.

To use it on your repository, all you have to do is set up the authentication
information and then run the following command::

    > pipenv run PYTHON_PATH=. kebecht-cli run-url -u <url-to-github-repo> -s <GITHUB|GITLAB|PAGURE>

Features
--------

- Python package dependency management (see update and thoth-advise manager)
- Version releases (version manager)
- and MORE

Contribute
----------

- Issue Tracker:`<github.com/thoth-station/kebechet/issues>`_
- Source Code: `<github.com/thoth-station/kebechet>`_

Support

Test
-------

If you are having issues, please let us know by opening an issue

License
-------

The project is licensed under the GPL-3.0 license.

.. end

Full documentation
------------------

For full documentation go `here
<https://thoth-station.ninja/docs/developers/kebechet>`__
