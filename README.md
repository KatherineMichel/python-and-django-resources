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
http://pmbaumgartner.github.io/slack-commands-with-python-and-flask.html | Creating Slack Slash Commands with Python and Flask: Part 1 - Blog
https://developer.github.com/v3/ | GitHub API v3 | GitHub Developer Guide
https://docs.google.com/spreadsheets/d/1JSX8fBmPb84emTmV0Kmyf0_r6R0kZM0h9Wdm91tn7Kg/edit#gid=0
http://distrowatch.com/table.php?distribution=mint
https://www.reddit.com/r/Python/comments/41kn28/looking_for_a_table_of_python_versions_shipped_by/
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
* [CPython Dev Guide](https://devguide.python.org), [Alternate URL: CPython Dev Guide Read the Docs](http://cpython-devguide.readthedocs.io), and [CPython Dev Guide GitHub](https://github.com/python/devguide)

CPython GitHub Migration
* ["The history behind the decision to move Python to GitHub"](https://snarky.ca/the-history-behind-the-decision-to-move-python-to-github)
* ["CPython workflow changes"](https://paper.dropbox.com/doc/CPython-workflow-changes-mx1k8G6M0rg5JLy80F1r6)

Release
* [PEP 537 -- Python 3.7 Release Schedule](https://www.python.org/dev/peps/pep-0537)
* [PEP 429 -- Python 3.4 Release Schedule](https://www.python.org/dev/peps/pep-0429)

Core Workflow Tools
* [Core Workflow Tools GitHub](https://github.com/python/core-workflow)
* [cherry_picker](https://github.com/python/core-workflow/tree/master/cherry_picker)
* [miss-islington](https://github.com/python/miss-islington)
* [Python Buildbot](https://www.python.org/dev/buildbot) and [Python Buildbot Wiki](https://wiki.python.org/moin/BuildBot)

<!--
Python Release Managers

https://github.com/python/miss-islington/issues

https://devguide.python.org/#quick-reference

https://devguide.python.org/#status-of-python-branches | Python Developer’s Guide — Python Developer's Guide

https://devguide.python.org/devcycle.html | 18. Development Cycle — Python Developer's Guide
https://devguide.python.org/pullrequest.html | 3. Lifecycle of a Pull Request — Python Developer's Guide
https://devguide.python.org/committing.html | 16. Committing and Pushing Changes — Python Developer's Guide

https://devguide.python.org/documenting.html#building-doc

https://cloud.githubusercontent.com/assets/2680980/23276970/d14a380c-f9d1-11e6-883d-e13b6b211239.png
-->

Python- Packages/Libraries
* [Pre-Production Deployment of Warehouse](https://pypi.org), [Warehouse GitHub](https://github.com/pypa/warehouse), and [Warehouse Read the Docs](https://warehouse.readthedocs.io)
* [PyPi Python Package Index PyPi](https://pypi.python.org/pypi)  

Python Docs- Packaging
* [Distributing Python Modules](https://docs.python.org/3/distributing/index.html)

Python- Official Packaging Info
* [PyPa Core Packaging Utilities](https://github.com/pypa/packaging)  
* [PyPa Core Packaging Utilities Documents](https://packaging.pypa.io/en/latest/)  
* [Python Packaging User Guide](https://packaging.python.org) 
* [Python Packaging Tutorials](https://packaging.python.org/tutorials) 
* [Python Packaging Guides](https://packaging.python.org/guides) 
* [Python Packaging and Distributing Projects Tutorial](https://packaging.python.org/tutorials/distributing-packages/)  

<!--
https://github.com/pypa/python-packaging-user-guide/issues
-->

Kenneth Reitz- Sample Module and setup.py
* [Sample Module for The Hitchhiker’s Guide to Python! GitHub](https://github.com/kennethreitz/samplemod)
* [Repository Structure and Python](https://www.kennethreitz.org/essays/repository-structure-and-python)
* [A Human's Ultimate Guide to setup.py GitHub](https://github.com/kennethreitz/setup.py)

<!--
https://github.com/kennethreitz/setup.py/blob/master/setup.py | setup.py/setup.py at master · kennethreitz/setup.py
-->

Package Helpers
* [Twine GitHub](https://github.com/pypa/twine) and [Twine PyPi](https://pypi.python.org/pypi/twine)

Package Stats
* ["How to get PyPI download statistics"](https://kirankoduru.github.io/python/pypi-stats.html)

<!--
https://media.readthedocs.org/pdf/python-packaging-user-guide/latest/python-packaging-user-guide.pdf | Python Packaging User Guide

https://wiki.python.org/moin/Distutils | Distutils - Python Wiki

https://docs.python.org/3.6/distutils/introduction.html | 1. An Introduction to Distutils — Python 3.6.4rc1 documentation
https://docs.python.org/3.6/library/distutils.html | 28.1. distutils — Building and installing Python modules — Python 3.6.4rc1 documentation
https://docs.python.org/3/distutils/setupscript.html | 2. Writing the Setup Script — Python 3.6.4rc1 documentation

https://docs.python.org/3.1/distutils/uploading.html | 7. Uploading Packages to the Package Index — Python v3.1.5 documentation
https://docs.python.org/3.6/distutils/packageindex.html#package-index | 6. The Python Package Index (PyPI) — Python 3.6.4rc1 documentation
https://docs.python.org/3.6/distutils/sourcedist.html | 4. Creating a Source Distribution — Python 3.6.4rc1 documentation


Python- Additional Packaging Tutorials
* [Digital Ocean Tutorial "How to Package and Distribute Python Applications"](https://www.digitalocean.com/community/tutorials/how-to-package-and-distribute-python-applications) 
* [Free Code Camp "How to publish your own Python Package on PyPi"](https://medium.freecodecamp.org/how-to-publish-a-pyton-package-on-pypi-a89e9522ce24)

https://blog.jetbrains.com/pycharm/2017/05/how-to-publish-your-package-on-pypi/ | How to Publish Your Package on PyPI | PyCharm Blog
https://tom-christie.github.io/articles/pypi/ | Uploading to PyPI – Tom Christie

Sample module for Python-Guide.org.
http://docs.python-guide.org

http://the-hitchhikers-guide-to-packaging.readthedocs.io/en/latest/contributing.html | Contribute Your Package to the World — The Hitchhiker's Guide to Packaging 1.0 documentation

https://pythonhosted.org/setuptools/formats.html
https://pythonhosted.org/an_example_pypi_project/setuptools.html

https://pip.pypa.io/en/stable/reference/pip_wheel
-->

Python- Cookiecutter Creating Packages
* [PyPi Release Checklist](https://gist.github.com/audreyr/5990987) and [PyPi Release Checklist 2](https://gist.github.com/audreyr/9f1564ea049c14f682f4)
* [Cookiecutter Django Package GitHub](https://github.com/pydanny/cookiecutter-djangopackage)
* [Cookiecutter PyPackage Read the Docs](https://cookiecutter.readthedocs.org/en/latest/tutorial1.html)
* [Cookiecutter PyPackage GitHub](https://github.com/audreyr/cookiecutter-pypackage)
* [Cookiecutter via Django Rest Framework: How to create a Third Party Package](http://www.django-rest-framework.org/topics/third-party-resources)

Python- Wheel (versus Egg!)
* [Python Packaging Wheel vs. Egg](http://python-packaging-user-guide.readthedocs.io/discussions/wheel-vs-egg)
* [Wheel PyPi](https://pypi.python.org/pypi/wheel) and [Wheel Read the Docs](http://wheel.readthedocs.org)
* [Python Wheels](http://pythonwheels.com)

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
* [Django 2.0 Release Notes](https://docs.djangoproject.com/en/2.0/releases/2.0) and [Django 2.0 Blog Post](https://www.djangoproject.com/weblog/2017/dec/02/django-20-released)
* [Django 2.1 Roadmap](https://code.djangoproject.com/wiki/Version2.1Roadmap) 
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
