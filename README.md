# Python and Django- Contributing

<!--
https://docs.python.org/3/about.html | About these documents — Python 3.6.5 documentation

* [Foreword for "Programming Python" (1st ed.)](https://www.python.org/doc/essays/foreword) in which Guido van Rossum explains how and why Python came into existence.
* [Stack Overflow Post](https://stackoverflow.blog/2017/09/06/incredible-growth-python) about the incredible growth of Python.

Data Classes
https://github.com/ericvsmith | ericvsmith (Eric V. Smith)
https://pypi.python.org/pypi/dataclasses | dataclasses 0.3 : Python Package Index
https://www.python.org/dev/peps/pep-0557/ | PEP 557 -- Data Classes | Python.org

Dropping Support
http://python3statement.org/ | Sunsetting Python 2 support in scientific Python projects
https://twitter.com/pganssle/status/978256523909623809 | Paul Ganssle on Twitter: "For any #python folks who may use python-dateutil in your projects, I'm working out the schedule for dropping Python 2.7 support now. The issue for discussion is here: https://t.co/sWRIhe85qp RT appreciated for visibility (don't want anyone blindsided)"
https://github.com/dateutil/dateutil/issues/653 | Python 2 deprecation schedule · Issue #653 · dateutil/dateutil

PyPI
http://pyfound.blogspot.com/2018/03/warehouse-all-new-pypi-is-now-in-beta.html#livechat | Python Software Foundation News: Warehouse: All New PyPI is now in beta
http://pyfound.blogspot.com/2018/02/python-package-maintainers-help-test.html | Python Software Foundation News: Python package maintainers, help test the new PyPI!
https://docs.google.com/forms/d/e/1FAIpQLSczrATlexkR1_gBt727eGnc05FCt-75Mx2usMq1wvCm_cLddg/viewform | Conducting user tests on PyPI
https://gist.github.com/nlhkabu/a0b1ae0016a2641f6b79d9ace9110403 | Recruiting User Testers for PyPI

http://pyfound.blogspot.com/2018/01/the-python-software-foundation-is.html | Python Software Foundation News: The Python Software Foundation is looking for bloggers!

My CPython Issue and Pull Requests
http://bugs.python.org/user26332

https://www.slideshare.net/MariattaWijaya/automating-github-workflow-with-bots | Automating GItHub Workflow with Bots

https://github.com/Mariatta | Mariatta

http://mariatta.ca/reflections-2017.html | mariatta.ca – 2017

Mariatta
https://twitter.com/dbader_org/status/925764913041215489 | Dan Bader on Twitter: "BTW this is the foreword for Python Tricks: The Book by the amazing @mariatta (CPython core developer, PyLadies Vancouver organizer) https://t.co/kHYDw6uJRC"
https://www.blog.pythonlibrary.org/2017/09/25/pydev-of-the-week-mariatta-wijaya/ | PyDev of the Week: Mariatta Wijaya | The Mouse Vs. The Python
https://github.com/berkerpeksag/cpython-merge-bot
https://github.com/Mariatta/miss-islington/tree/master/backport | miss-islington/backport at master · Mariatta/miss-islington
https://www.slideshare.net/MariattaWijaya/pythonpowered-savage-garden-hotline | Python-Powered Savage Garden Hotline
https://github.com/Mariatta/mariatta-bot | Mariatta/mariatta-bot: Mariatta's GitHub bot
https://pypi.org/project/pytaco/ | pytaco · Warehouse (PyPI)
https://github.com/Mariatta/taco-py | Mariatta/taco-py: Figure out how many taco to order for your meetup
https://github.com/Mariatta/tic_tac_taco_pizza | GitHub - Mariatta/tic_tac_taco_pizza: Play tic tac toe, with taco and pizza
https://github.com/Mariatta/cloner
http://pmbaumgartner.github.io/slack-commands-with-python-and-flask.html | Creating Slack Slash Commands with Python and Flask: Part 1 - Blog
https://developer.github.com/v3/ | GitHub API v3 | GitHub Developer Guide
https://docs.google.com/spreadsheets/d/1JSX8fBmPb84emTmV0Kmyf0_r6R0kZM0h9Wdm91tn7Kg/edit#gid=0
http://distrowatch.com/table.php?distribution=mint
https://www.reddit.com/r/Python/comments/41kn28/looking_for_a_table_of_python_versions_shipped_by/
https://github.com/Mariatta/python_versions_and_distros
-->

Python
* [Python Front Page](https://wiki.python.org/moin)
* [Python GitHub](https://github.com/python)

Python Authorities
* [Python Packaging Authority (PyPA)](https://pypa.io) and [Python Packaging Authority GitHub](https://github.com/pypa) 
* [Python Authority Authority (PyAA) GitHub](https://github.com/pyaa)
* [Python Code Quality Authority (PyCQA) GitHub](https://github.com/PyCQA) and [Python Code Quality Authority (PyCQA) GitLab](https://gitlab.com/groups/pycqa)
* [Python Cryptographic Authority (PyCA) GitHub](https://github.com/pyca)

PEP Template
* [PEP 12 -- Sample reStructuredText PEP Template](https://www.python.org/dev/peps/pep-0012)

CPython GitHub Migration
* ["The history behind the decision to move Python to GitHub"](https://snarky.ca/the-history-behind-the-decision-to-move-python-to-github)
* ["CPython workflow changes"](https://paper.dropbox.com/doc/CPython-workflow-changes-mx1k8G6M0rg5JLy80F1r6)

CPython Contributing
* [CPython GitHub](https://github.com/python/cpython)
* [Bugs](http://bugs.python.org)
* [CPython Dev Guide](https://devguide.python.org), [Alternate URL: CPython Dev Guide Read the Docs](http://cpython-devguide.readthedocs.io), and [CPython Dev Guide GitHub](https://github.com/python/devguide)

Python Status
* [Python Status](https://status.python.org)
* [Python Status History](https://status.python.org/history)

<!--
https://travis-ci.org/python/cpython/
-->

Python 2 End of Life (EOL)
* [Python 2 End of Life (EOL) Python Developer email](https://mail.python.org/pipermail/python-dev/2018-March/152348.html)

Release
* [PEP 537 -- Python 3.7 Release Schedule](https://www.python.org/dev/peps/pep-0537)
* [PEP 429 -- Python 3.4 Release Schedule](https://www.python.org/dev/peps/pep-0429)

Core Workflow Tools
* [Core Workflow Tools GitHub](https://github.com/python/core-workflow)
* [cherry_picker](https://github.com/python/core-workflow/tree/master/cherry_picker) and [cherry picker PyPi](https://pypi.org/project/cherry-picker)
* [miss-islington](https://github.com/python/miss-islington)
* [Python Buildbot](https://www.python.org/dev/buildbot) and [Python Buildbot Wiki](https://wiki.python.org/moin/BuildBot)

Sphinx and Django-Sphinx
* [Python Docs Theme (Sphinx)](https://github.com/python/python-docs-theme)
* [Sphinx](http://sphinx-doc.org)  
* [Django-Sphinxdoc PyPi](https://pypi.python.org/pypi/django-sphinxdoc) 
* [Read the Docs Sphinx Theme GitHub](https://github.com/snide/sphinx_rtd_theme) 

Command Line
* [Click GitHub](https://github.com/pallets/click)
* [Chalk GitHub](https://github.com/chalk/chalk)

<!--
Python Release Managers
https://mail.python.org/pipermail/python-dev/2018-January/151949.html | [Python-Dev] Welcome the 3.8 and 3.9 Release Manager - Łukasz Langa!

Doc/build/html/index.html - Google Search
https://github.com/python/core-workflow/issues/174 | pip install blurb successfully installs with Python < 3.5 · Issue #174 · python/core-workflow
https://pypi.python.org/pypi/blurb

https://devguide.python.org/documenting/#building-the-documentation | 7. Documenting Python — Python Developer's Guide

https://github.com/python/miss-islington/issues

http://devdocs.io/python~3.6/ | DevDocs — Python 3.6 documentation

https://docs.python.org/devguide/ | Python Developer’s Guide — Python Developer's Guide
https://docs.python.org/devguide/docquality.html?highlight=sphinx | 6. Helping with Documentation — Python Developer's Guide

https://devguide.python.org/#quick-reference
https://devguide.python.org/#status-of-python-branches | Python Developer’s Guide — Python Developer's Guide
https://devguide.python.org/devcycle.html | 18. Development Cycle — Python Developer's Guide
https://devguide.python.org/pullrequest.html | 3. Lifecycle of a Pull Request — Python Developer's Guide
https://devguide.python.org/committing.html | 16. Committing and Pushing Changes — Python Developer's Guide

https://cloud.githubusercontent.com/assets/2680980/23276970/d14a380c-f9d1-11e6-883d-e13b6b211239.png
-->

Python- Packages/Libraries
* [Pre-Production Deployment of Warehouse](https://pypi.org), [Warehouse GitHub](https://github.com/pypa/warehouse), and [Warehouse Read the Docs](https://warehouse.readthedocs.io)
* [PyPi Python Package Index PyPi](https://pypi.python.org/pypi)  

<!--
https://wiki.python.org/moin/CheeseShop | CheeseShop - Python Wiki
https://warehouse.readthedocs.io/development/getting-started/#quickstart-for-developers-with-docker-experience | Getting started — Warehouse 15.0.dev0 documentation

https://github.com/pypa/warehouse
https://github.com/pypa/warehouse/issues
https://twitter.com/pypi_updates2 | PyPI Recent Updates (@pypi_updates2) | Twitter

Package Stats
* ["How to get PyPI download statistics"](https://kirankoduru.github.io/python/pypi-stats.html)

https://bigquery.cloud.google.com/table/the-psf:pypi.downloads | Google BigQuery
https://mail.python.org/pipermail/distutils-sig/2013-June/021344.html | [Distutils] Download Counts on PyPI
-->

Package Helpers
* [Twine GitHub](https://github.com/pypa/twine) and [Twine PyPi](https://pypi.python.org/pypi/twine)

Python Sprints
* [Python Sprints](https://python-sprints.github.io)

Mailing List and Permissions History
* [Python Core Workflow Mailing List](https://mail.python.org/mailman/listinfo/core-workflow)
* [Permissions History](https://devguide.python.org/developers/#permissions-history)
* [Developer Log](https://github.com/python/devguide/blob/bbd38631554165a64e187bd29815125098159a13/developers.rst)

Python Mentors
* [Python Mentors](http://pythonmentors.com)

Python Mentorship for Women (Guido van Rossum), Female Core Devs
* [Python Mentorship for Women](https://twitter.com/mariatta/status/737689052736978945)
* [Mariatta and Allison Randal](https://twitter.com/matrixise/status/865678978677223429)
* ["Imposter syndrome is real"](https://twitter.com/KatiMichel/status/865740929512071168)

python.org Contributing
* [python.org GitHub](https://github.com/python/pythondotorg)
* [python.org Issues](https://github.com/python/pythondotorg/issues)
* [python.org Staging](https://staging.python.org)
* [python.org Read the Docs](https://pythondotorg.readthedocs.io)
* [python.org Read the Docs Install](https://pythondotorg.readthedocs.io/install.html) and [python.org Read the Docs Contributing](https://pythondotorg.readthedocs.io/contributing.html)
* [Couldn't set up local environment](https://github.com/python/pythondotorg/issues/987)
* [python.org Contributors](https://github.com/python/pythondotorg/graphs/contributors)

Python and Django Git Bootcamps and Cheat Sheets
* [Python: Git Bootcamp and Cheat Sheet](https://docs.python.org/devguide/gitbootcamp.html)
* [Django: Working with Git and GitHub](https://docs.djangoproject.com/en/1.8/internals/contributing/writing-code/working-with-git)

Django Software
* [Django Submitting a Patch](https://docs.djangoproject.com/en/2.0/internals/contributing/writing-code/submitting-patches/)

djangoproject.com Contributing
* [djangoproject.com GitHub](https://github.com/django/djangoproject.com)
* [code.djangoproject.com](https://code.djangoproject.com)
* [dashboard.djangoproject.com](https://dashboard.djangoproject.com)

Django Contributing
* [Tickets](https://code.djangoproject.com/query)
* [Life of a Django Ticket](https://docs.google.com/presentation/d/1Ao0S3Z-VRn_pcT5T4mXIhv3t3liQ3ZrwqaGeDqz9XCQ/edit)

Django, Releases, Announcements, and Roadmaps
* [Django Releases](https://docs.djangoproject.com/en/stable/releases)
* [Django Announcements](https://groups.google.com/forum/#!forum/django-announce)
* [Django 2.0 Release Notes](https://docs.djangoproject.com/en/2.0/releases/2.0) and [Django 2.0 Blog Post](https://www.djangoproject.com/weblog/2017/dec/02/django-20-released)
* [Django 2.1 Roadmap](https://code.djangoproject.com/wiki/Version2.1Roadmap) 
* [DEPS (Django Enhancement Proposals) GitHub](https://github.com/django/deps)

<!--
https://code.djangoproject.com/wiki/Version2.0Roadmap | Version2.0Roadmap – Django
https://www.djangoproject.com/weblog/2015/jun/25/roadmap/ | Django's Roadmap | Weblog | Django

https://docs.djangoproject.com/en/2.0/internals/release-process/#internal-release-cadence | Django’s release process | Django documentation | Django
-->

Django Developers Forum and Slack
* [Django Google Developers Forum](https://groups.google.com/forum/#!forum/django-developers) 
* [Django Developers Slack](https://django-developers.herokuapp.com)

Django Mailing Lists and People
* [Django Mailing Lists](https://docs.djangoproject.com/en/dev/internals/mailing-lists)
* [Django Original Team List](https://www.djangoproject.com/foundation/teams/#original-team-list)
* [Django Core Developers (Old Version)](https://docs.djangoproject.com/en/1.7/internals/committers/#core-developers)
* [Django Organization Repo People](https://github.com/orgs/django/people)

Django Code of Conduct and Contributing
* [Django Code of Conduct](https://www.djangoproject.com/conduct)
* [Django Contributing](https://docs.djangoproject.com/en/dev/internals/contributing)
* [Django Contributor License Agreements](https://www.djangoproject.com/foundation/cla)
