# Python and Django- Contributing

<!--
My CPython Issue and Pull Requests
http://bugs.python.org/user26332

Mariatta
https://twitter.com/dbader_org/status/925764913041215489 | Dan Bader on Twitter: "BTW this is the foreword for Python Tricks: The Book by the amazing @mariatta (CPython core developer, PyLadies Vancouver organizer) https://t.co/kHYDw6uJRC"
https://www.blog.pythonlibrary.org/2017/09/25/pydev-of-the-week-mariatta-wijaya/ | PyDev of the Week: Mariatta Wijaya | The Mouse Vs. The Python
https://github.com/berkerpeksag/cpython-merge-bot
https://github.com/Mariatta/python_versions_and_distros
https://github.com/Mariatta/tic_tac_taco_pizza | GitHub - Mariatta/tic_tac_taco_pizza: Play tic tac toe, with taco and pizza
https://github.com/Mariatta/cloner
https://github.com/python/miss-islington | python/miss-islington: 🐍🍒⛏🤖 - A bot for backporting CPython pull requests
https://github.com/python/miss-islington/issues
http://pmbaumgartner.github.io/slack-commands-with-python-and-flask.html | Creating Slack Slash Commands with Python and Flask: Part 1 - Blog
https://developer.github.com/v3/ | GitHub API v3 | GitHub Developer Guide
https://docs.google.com/spreadsheets/d/1JSX8fBmPb84emTmV0Kmyf0_r6R0kZM0h9Wdm91tn7Kg/edit#gid=0
http://distrowatch.com/table.php?distribution=mint
https://www.reddit.com/r/Python/comments/41kn28/looking_for_a_table_of_python_versions_shipped_by/
-->

<!--
http://www.fullstackpython.com/deployment.html
http://masteringdjango.com/testing-in-django

https://pythonhosted.org/an_example_pypi_project/setuptools.html
-->

Python
* [Python Front Page](https://wiki.python.org/moin/FrontPage)
* [Python GitHub](https://github.com/python)

Python Authorities
* [Python Packaging Authority (PyPA)](https://pypa.io) and [Python Packaging Authority GitHub](https://github.com/pypa) 
* [Python Authority Authority (PyAA) GitHub](https://github.com/pyaa)
* [Python Code Quality Authority (PyCQA) GitHub](https://github.com/PyCQA) and [Python Code Quality Authority (PyCQA) GitLab](https://gitlab.com/groups/pycqa)
* [Python Cryptographic Authority (PyCA) GitHub](https://github.com/pyca)

CPython Contributing
* [CPython GitHub](https://github.com/python/cpython)
* [Bugs](http://bugs.python.org)
* [cherry_picker](https://github.com/python/core-workflow/tree/master/cherry_picker)

Dev Guides
* [Python Dev Guide](https://docs.python.org/devguide), [Python Dev Guide Read the Docs](http://cpython-devguide.readthedocs.io), and [Python Dev Guide GitHub](https://github.com/python/devguide)

<!--
https://snarky.ca/the-history-behind-the-decision-to-move-python-to-github/ | The history behind the decision to move Python to GitHub
CPython workflow changes
https://paper.dropbox.com/doc/CPython-workflow-changes-mx1k8G6M0rg5JLy80F1r6
Python Release Managers

https://devguide.python.org/developers
https://devguide.python.org/#quick-reference

https://devguide.python.org/#status-of-python-branches | Python Developer’s Guide — Python Developer's Guide
https://www.python.org/dev/peps/pep-0537/ | PEP 537 -- Python 3.7 Release Schedule | Python.org

https://docs.python.org/devguide/devcycle.html | 18. Development Cycle — Python Developer's Guide
https://docs.python.org/devguide/pullrequest.html | 3. Lifecycle of a Pull Request — Python Developer's Guide
https://docs.python.org/devguide/committing.html#working-with-git | 16. Committing and Pushing Changes — Python Developer's Guide

http://cpython-devguide.readthedocs.io/documenting.html#building-doc
http://cpython-devguide.readthedocs.io/#quick-reference

https://www.python.org/dev/buildbot/ | Python Buildbot | Python.org
https://wiki.python.org/moin/BuildBot

https://cloud.githubusercontent.com/assets/2680980/23276970/d14a380c-f9d1-11e6-883d-e13b6b211239.png
-->

Python- Packages/Libraries
* [Pre-Production Deployment of Warehouse](https://pypi.org) and [Warehouse GitHub](https://github.com/pypa/warehouse) 
* [PyPi Python Package Index PyPi](https://pypi.python.org/pypi)  

Python- Official Packaging Info
* [PyPa Core Packaging Utilities](https://github.com/pypa/packaging)  
* [PyPa Core Packaging Utilities Documents](https://packaging.pypa.io/en/latest/)  
* [Python Packaging User Guide](https://packaging.python.org) 
* [Python Packaging Tutorials](https://packaging.python.org/tutorials) 
* [Python Packaging and Distributing Projects Tutorial](https://packaging.python.org/tutorials/distributing-packages/)  

<!--
https://warehouse.readthedocs.io/development/getting-started/ | Getting started — Warehouse 15.0.dev0 documentation

Python- Creating Packages
* [Distributing Python Modules](https://docs.python.org/3/distributing/index.html)

https://packaging.python.org/guides/
https://packaging.python.org/new-tutorials | Maze Found | Read the Docs
https://packaging.python.org/tutorials/managing-dependencies/ | Managing Application Dependencies — Python Packaging User Guide
https://packaging.python.org/tutorials/installing-packages

https://github.com/pypa/python-packaging-user-guide/issues
-->

Python- Additional Packaging Tutorials
* [Digital Ocean Tutorial How to Package and Distribute Python Applications](https://www.digitalocean.com/community/tutorials/how-to-package-and-distribute-python-applications) 

Kenneth Reitz- Sample Module and setup.py
* [Sample Module for The Hitchhiker’s Guide to Python! GitHub](https://github.com/kennethreitz/samplemod)
* [Repository Structure and Python](https://www.kennethreitz.org/essays/repository-structure-and-python)
* [A Human's Ultimate Guide to setup.py GitHub](https://github.com/kennethreitz/setup.py)

<!--
Sample module for Python-Guide.org.
http://docs.python-guide.org/en/latest/

https://kirankoduru.github.io/python/pypi-stats.html | How to get PyPI download statistics

http://the-hitchhikers-guide-to-packaging.readthedocs.io/en/latest/contributing.html | Contribute Your Package to the World — The Hitchhiker's Guide to Packaging 1.0 documentation

https://pythonhosted.org/setuptools/formats.html
http://python-packaging-user-guide.readthedocs.io/en/latest/wheel_egg/
-->

Python- Cookiecutter Creating Packages
* [PyPi Release Checklist](https://gist.github.com/audreyr/5990987) and [PyPi Release Checklist 2](https://gist.github.com/audreyr/9f1564ea049c14f682f4)
* [Cookiecutter Django Package GitHub](https://github.com/pydanny/cookiecutter-djangopackage)
* [Cookiecutter PyPackage Read the Docs](https://cookiecutter.readthedocs.org/en/latest/tutorial1.html)
* [Cookiecutter PyPackage GitHub](https://github.com/audreyr/cookiecutter-pypackage)
* [Cookiecutter via Django Rest Framework: How to create a Third Party Package](http://www.django-rest-framework.org/topics/third-party-resources)

Python- Wheel (versus Egg!)
* [Wheel PyPi](https://pypi.python.org/pypi/wheel) and [Wheel Read the Docs](http://wheel.readthedocs.org)
* [Python Wheels](http://pythonwheels.com)

<!--
http://eldarion.com/blog/2017/10/17/how-we-maintain-high-levels-code-quality/
http://eldarion.com/blog/2017/07/13/5-reasons-you-should-care-about-code-coverage/

https://codecov.io/
https://circleci.com/
https://coverage.readthedocs.io/en/coverage-4.4.1/#quick-start
https://bitbucket.org/ned/coveragepy | ned / coverage.py — Bitbucket
coverage http://coverage.readthedocs.org/
https://github.com/FactoryBoy/factory_boy | FactoryBoy/factory_boy: A test fixtures replacement for Python
factory boy https://pypi.python.org/pypi/factory_boy
https://pypi.python.org/pypi/detox
Tox (Automation)
* [Tox Read the Docs](https://tox.readthedocs.org)
https://github.com/tox-dev/detox | tox-dev/detox: distributed tox
https://github.com/revsys/django-test-plus | revsys/django-test-plus: Useful additions to Django's default TestCase
http://django-test-plus.readthedocs.io/en/latest/
https://github.com/timothycrosley/isort
http://flake8.pycqa.org/en/latest/ | Flake8: Your Tool For Style Guide Enforcement — flake8 3.5.0 documentation
https://github.com/zheller/flake8-quotes | zheller/flake8-quotes: Flake8 extension for checking quotes in python


2.12 Writing your first patch for Django
https://docs.djangoproject.com/en/1.9/internals/contributing/writing-code/submitting-patches
https://docs.python.org/3.5/library/unittest.html
http://www.diveintopython.net/unit_testing

https://en.wikipedia.org/wiki/Code_coverage
https://martinfowler.com/bliki/TestCoverage.html

http://pythontesting.net/start-here | Start Here - Python Testing
http://toastdriven.com/blog/2011/apr/10/guide-to-testing-in-django

Test-Driven Development with Python<br>

pytest and Nose (Unit Test Extension)
* [Nose GitHub](https://github.com/nose-devs/nose)
* [Nose Docs Reads the Docs](https://nose.readthedocs.org/en/latest) 
* [Django Nose GitHub](https://github.com/django-nose/django-nose)
* [pytest](http://pytest.org)
* [pytest-django PyPi](https://pypi.python.org/pypi/pytest-django) and * [pytest-django Read the Docs](http://pytest-django.readthedocs.org)
* [mock PyPi](https://pypi.python.org/pypi/mock)

https://www.crowdcast.io/e/pytest-2 | Testing Python with pytest – Crowdcast
https://docs.pytest.org/en/latest/example/
https://github.com/pytest-dev/cookiecutter-pytest-plugin | pytest-dev/cookiecutter-pytest-plugin: A Cookiecutter to create pytest plugins with ease.
http://doc.pytest.org/en/latest/contents.html#toc

https://en.wikipedia.org/wiki/Kent_Beck | Kent Beck - Wikipedia
https://www.obeythetestinggoat.com/

http://www.drmaciver.com/2017/09/python-coverage-could-be-fast/ | Python Coverage could be fast | David R. MacIver

noqa - Google Search

http://www.pyinvoke.org/

model mommy https://pypi.python.org/pypi/model_mommy
 
Selenium
* [Selenium](http://www.seleniumhq.org)
-->


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
* [Couldn't set up local environment](https://github.com/python/pythondotorg/issues/987)

<!--
https://github.com/python/pythondotorg/graphs/contributors | Contributors to python/pythondotorg

https://github.com/python/pythondotorg/tree/master

https://pythondotorg.readthedocs.io/install.html
https://pythondotorg.readthedocs.io/contributing.html
https://pythondotorg.readthedocs.io
https://staging.python.org
-->

Python and Django Git Bootcamps and Cheat Sheets
* [Python: Git Bootcamp and Cheat Sheet](https://docs.python.org/devguide/gitbootcamp.html)
* [Django: Working with Git and GitHub](https://docs.djangoproject.com/en/1.8/internals/contributing/writing-code/working-with-git)

djangoproject.com Contributing
* [djangoproject.com GitHub](https://github.com/django/djangoproject.com)
* [code.djangoproject.com](https://code.djangoproject.com)
* [dashboard.djangoproject.com](https://dashboard.djangoproject.com)

Django Coding Style
* [Django Coding Style](https://docs.djangoproject.com/en/2.0/internals/contributing/writing-code/coding-style/)

Django Deployment
* [Deployment Checklist](https://docs.djangoproject.com/en/1.10/howto/deployment/checklist)

Django Contributing
* [Tickets](https://code.djangoproject.com/query)
* [Life of a Django Ticket](https://docs.google.com/presentation/d/1Ao0S3Z-VRn_pcT5T4mXIhv3t3liQ3ZrwqaGeDqz9XCQ/edit)

Django, Releases, Announcements, and Roadmaps
* [Django Releases](https://docs.djangoproject.com/en/stable/releases)
* [Django Announcements](https://groups.google.com/forum/#!forum/django-announce)
* [Django Enhancement Proposals](https://github.com/django/deps)
* [Django 2.1 Roadmap](https://code.djangoproject.com/wiki/Version2.1Roadmap) 
 
Django DEPS
* [DEPS (Django Enhancement Proposals) GitHub](https://github.com/django/deps)

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
