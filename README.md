# Python and Django- Contributing

<!--
https://lwn.net/ | Welcome to LWN.net [LWN.net]

https://www.google.com/search?q=Stephen+Simmons%2C+Neil+Slinger+python+at+massive+scale&oq=Stephen+Simmons%2C+Neil+Slinger+python+at+massive+scale&aqs=chrome..69i57j33l2.3499j0j7&sourceid=chrome&ie=UTF-8 | Stephen Simmons, Neil Slinger python at massive scale - Google Search
https://www.youtube.com/watch?v=H4SS9yVWJYA | Jason Fried - Fighting the Good Fight: Python 3 in your organization - PyCon 2018 - YouTube

http://python-notes.curiousefficiency.org

https://nedbatchelder.com/blog/201711/toxic_experts.html

Django Notes
https://code.djangoproject.com/wiki/TitleIndex
https://code.djangoproject.com/wiki/NewbieMistakes | NewbieMistakes – Django
https://www.python.org/download/releases/2.2/descrintro/#metaclasses | Unifying types and classes in Python 2.2 | Python.org
https://code.djangoproject.com/wiki/DynamicModels | DynamicModels – Django
https://code.djangoproject.com/wiki/DevModelCreation | DevModelCreation – Django

https://docs.python.org/3/reference/import.html#open-issues | 5. The import system — Python 3.7.0 documentation

https://docs.python.org/2/howto/doanddont.html | Idioms and Anti-Idioms in Python — Python 2.7.15 documentation
https://docs.python-guide.org/writing/gotchas/ | Common Gotchas — The Hitchhiker's Guide to Python
http://django-gotchas.readthedocs.io/en/latest/ | Welcome to Django gotchas documentation! — Django gotchas 0.1 documentation


My CPython Issue and Pull Requests
http://bugs.python.org/user26332

http://pyfound.blogspot.com/2018/01/the-python-software-foundation-is.html | Python Software Foundation News: The Python Software Foundation is looking for bloggers!

http://pyfound.blogspot.com/2018/10/pypi-security-and-accessibility-q1-2019.html | Python Software Foundation News: PyPI Security and Accessibility Q1 2019 Request for Information period opens.
https://www.djangoproject.com/weblog/2018/nov/04/individual-membership-system-cfp/ | DSF Individual membership - call for implementation proposals | Weblog | Django

Django Core
https://www.amazon.com/Mastering-Django-Core-Complete-Guide/dp/099461683X | Mastering Django: Core: The Complete Guide to Django 1.8 LTS: Nigel George: 9780994616838: Amazon.com: Books

https://www.amazon.com/Guido%20Van%20Rossum/e/B0034OPA4K/ref=la_B0034OPA4K_st?rh=n%3A283155%2Cp_82%3AB0034OPA4K&qid=1505705520&sort=date-desc-rank | Amazon.com: Guido Van Rossum: Books, Biography, Blog, Audiobooks, Kindle

https://devguide.python.org/coredev/ | 14. How to Become a Core Developer — Python Developer's Guide
Django Core Mentorship


New functionality
https://www.python.org/dev/peps/pep-0553/ | PEP 553 -- Built-in breakpoint() | Python.org
https://www.python.org/dev/peps/pep-3107/ | PEP 3107 -- Function Annotations | Python.org
https://mail.python.org/pipermail/python-dev/2018-July/154554.html | [Python-Dev] Naming comprehension syntax [was Re: Informal educator feedback on PEP 572 ...]
https://github.com/python/cpython/pull/8122/files | WIP: use assignment expression in stdlib (combined PR) by vstinner · Pull Request #8122 · python/python
https://nedbatchelder.com/blog/201605/generator_comprehensions.html | Ned Batchelder: Generator comprehensions
https://twitter.com/squeaky_pl/status/1014855652362145792 | Squeaky on Twitter: "FYI @VictorStinner opened some pull requests to CPython for __demonstration purposes__ how PEP 572 assignment expression can be used to make Python library code more readable/shorter: https://t.co/Gc5IwdqwD1 https://t.co/IxkNMJvo9G https://t.co/eNPKiRgeI6… https://t.co/SjocXGITSS"
https://www.python.org/dev/peps/pep-0572/ | PEP 572 -- Assignment Expressions | Python.org

https://twitter.com/freakboy3742/status/999286561626877957 | Russell Keith-Magee on Twitter: "TIL: Python 3.6 f-strings and Dynamic Django querysets are a match made in heaven. It’s kinda obvious when you think about it, but it took @maribedran pointing it out before this 12-year Django core team veteran made the connection. #djangocon"

https://twitter.com/llanga/status/999318672098320384 | Łukasz Langa on Twitter: "i'm surprised dict views aren't more popular. Real world example: https://t.co/sOVvUgeJRc I think this is really elegant. For explanation read below.… https://t.co/kqXSQajFZr"

Setup.py Kenneth Reitz
-->

Python
* [Python Front Page](https://wiki.python.org/moin)
* [Python GitHub](https://github.com/python)

<!--
https://docs.python.org/3/about.html | About these documents — Python 3.6.5 documentation
-->

Python History
* [The History of Python](http://python-history.blogspot.com)
* [Guido van Rossum: BDFL Python 3 retrospective, PyCascades 2018](https://www.youtube.com/watch?v=Oiw23yfqQy8)
* [Foreword for "Programming Python" (1st ed.)](https://www.python.org/doc/essays/foreword) in which Guido van Rossum explains how and why Python came into existence.
* ["The Python Way"](https://mail.python.org/pipermail/python-list/1999-June/001951.html)

<!--
http://python-history.blogspot.com/2009/01/pythons-design-philosophy.html | The History of Python: Python's Design Philosophy
http://python-history.blogspot.com/2009/01/introduction-and-overview.html | The History of Python: Introduction and Overview
http://python-history.blogspot.com/2009/01/brief-timeline-of-python.html | The History of Python: A Brief Timeline of Python
-->

Python and Django Governance and BDFL
* [PEP 8016- The Steering Council Model (Accepted)](https://www.python.org/dev/peps/pep-8016)
* [Python Governance Vote (December 2018)](https://discuss.python.org/t/python-governance-vote-december-2018-results/546)
* [PEP 8010- The Technical Leader Governance Model (Rejected)](https://www.python.org/dev/peps/pep-8010)
* [PEP 572 and decision-making in Python](https://lwn.net/Articles/757713)
* [Transfer of Power](https://mail.python.org/pipermail/python-committers/2018-July/005664.html)
* [Moratorium on Governance Decisions](https://mail.python.org/pipermail/python-committers/2018-July/005935.html)
* [Jacob Kaplan-Moss](https://jacobian.org/writing/retiring-as-bdfls)

<!--
https://twitter.com/brettsky/status/1074690504682426368 | Brett Cannon on Twitter: "PEP 8016 won, so next step is an election for council membership that will take 4 weeks to hold and needs a start date to be scheduled… https://t.co/W9tM3aGc2J"

https://groups.google.com/forum/#!topic/django-developers/8b-wxEzWO3c/discussion
https://github.com/django/django/pull/2947 | Team organization by aaugustin · Pull Request #2947 · django/django
https://twitter.com/aymericaugustin/status/1074751907195949056 | Aymeric Augustin on Twitter: ""Substantial text was copied shamelessly from The Django project's governance document." It looks like https://t.co/QN7JaoXdFI just became my biggest contribution to Python :-)… https://t.co/CsC0LoxMRz"
-->

Python Trends
* [Stack Overflow Post: the incredible growth of Python](https://stackoverflow.blog/2017/09/06/incredible-growth-python)
* [Hackernoon: "Could Python’s Popularity Outperform JavaScript in the Next Five Years?"](https://hackernoon.com/could-pythons-popularity-outperform-javascript-in-the-next-five-years-abed4e307224)

Surveys
* [JetBrains Python Developers Survey (2018)](https://www.jetbrains.com/research/devecosystem-2018/python) and [JetBrains Python Developers Survey (2018) GitHub](https://github.com/python/python-dev-survey)
* [JetBrains PPython Developers Survey (2017)](https://www.jetbrains.com/research/python-developers-survey-2017)

Python 2 or 3
* [Python 2 or 3](https://wiki.python.org/moin/Python2orPython3)

Python 2 End of Life (EOL)
* [Python 2 End of Life (EOL) Python Developer email](https://mail.python.org/pipermail/python-dev/2018-March/152348.html)

Python 2 EOL Websites
* [Guido van Rossum: "Cool sites about the Python 3 transition"](https://twitter.com/gvanrossum/status/1012462042094002176)
* [Python Clock](https://pythonclock.org)
* [Python 3 Statement](http://python3statement.org)
* [Python 3 Readiness](https://py3readiness.org)
* [Python Readiness](https://pyreadiness.org)
* [Python 3 Wall of Superpowers](https://python3wos.appspot.com)
* [Python 3 Porting](http://python3porting.com)

Django and Python 3
* [Django Packages Python 3](https://www.djangopackages.com/python3)

<!--
http://python-future.org/ | Easy, clean, reliable Python 2/3 compatibility — Python-Future documentation

Dropping Support
https://twitter.com/pganssle/status/978256523909623809 | Paul Ganssle on Twitter: "For any #python folks who may use python-dateutil in your projects, I'm working out the schedule for dropping Python 2.7 support now. The issue for discussion is here: https://t.co/sWRIhe85qp RT appreciated for visibility (don't want anyone blindsided)"
https://github.com/dateutil/dateutil/issues/653 | Python 2 deprecation schedule · Issue #653 · dateutil/dateutil
-->

Python Authorities
* [Python Packaging Authority (PyPA)](https://pypa.io) and [Python Packaging Authority GitHub](https://github.com/pypa) 
* [Python Authority Authority (PyAA) GitHub](https://github.com/pyaa)
* [Python Code Quality Authority (PyCQA) GitHub](https://github.com/PyCQA) and [Python Code Quality Authority (PyCQA) GitLab](https://gitlab.com/groups/pycqa)
* [Python Cryptographic Authority (PyCA) GitHub](https://github.com/pyca)

Python- PEP
* [PEP Index](https://www.python.org/dev/peps)
* [Legacy PEP Index](https://legacy.python.org/dev/peps)

PEP Template
* [PEP 12 -- Sample reStructuredText PEP Template](https://www.python.org/dev/peps/pep-0012)

CPython Contributing
* [CPython GitHub](https://github.com/python/cpython)
* [Bugs](http://bugs.python.org)
* [CPython Dev Guide](https://devguide.python.org), [Alternate URL: CPython Dev Guide Read the Docs](http://cpython-devguide.readthedocs.io), and [CPython Dev Guide GitHub](https://github.com/python/devguide)
* [How to Become a Core Developer — Python Developer's Guide](https://devguide.python.org/coredev)

<!--
http://pythondev.readthedocs.io/ | Python Development Documentation — Python Development 1.0 documentation
http://devdocs.io/python~3.6/ | DevDocs — Python 3.6 documentation

https://docs.python.org/devguide/motivations.html
https://devguide.python.org/help/#office-hour | 2. Where to Get Help — Python Developer's Guide

https://docs.python.org/devguide/docquality.html?highlight=sphinx | 6. Helping with Documentation — Python Developer's Guide

https://devguide.python.org/#quick-reference
https://devguide.python.org/#branchstatus
https://devguide.python.org/#status-of-python-branches | Python Developer’s Guide — Python Developer's Guide
https://devguide.python.org/devcycle.html | 18. Development Cycle — Python Developer's Guide
https://devguide.python.org/pullrequest.html | 3. Lifecycle of a Pull Request — Python Developer's Guide
https://devguide.python.org/committing.html | 16. Committing and Pushing Changes — Python Developer's Guide

https://cloud.githubusercontent.com/assets/2680980/23276970/d14a380c-f9d1-11e6-883d-e13b6b211239.png
-->

Python Status
* ["Status of Python CIs (buildbots, Travis CI, AppVeyor): July 2018"](https://mail.python.org/pipermail/python-dev/2018-July/154703.html)
* [Python Status](https://status.python.org)
* [Python Status History](https://status.python.org/history)

<!--
 https://travis-ci.org/python/cpython/
-->

Release
* [PEP 537 -- Python 3.7 Release Schedule](https://www.python.org/dev/peps/pep-0537)
* [PEP 429 -- Python 3.4 Release Schedule](https://www.python.org/dev/peps/pep-0429)
* [PEP 373 -- Python 2.7 Release Schedule](https://www.python.org/dev/peps/pep-0373)

Release Managers
* ["Welcome the 3.8 and 3.9 Release Manager - Łukasz Langa!"](https://mail.python.org/pipermail/python-dev/2018-January/151949.html)

Python Performance

<!--
https://www.python.org/doc/essays/list2str/ | Python Patterns - An Optimization Anecdote | Python.org

https://jakevdp.github.io/blog/2014/05/09/why-python-is-slow/ | Why Python is Slow: Looking Under the Hood | Pythonic Perambulations

https://github.com/python/performance | python/performance: Python Performance Benchmark Suite

Regression Test Suite For Python Core Developers
26.8. test — Regression tests package for Python
https://docs.python.org/3/library/test.html
26.9. test.support — Utilities for the Python test suite
https://docs.python.org/3/library/test.html#module-test.support
-->

CPython GitHub Migration
* ["The history behind the decision to move Python to GitHub"](https://snarky.ca/the-history-behind-the-decision-to-move-python-to-github)
* ["CPython workflow changes"](https://paper.dropbox.com/doc/CPython-workflow-changes-mx1k8G6M0rg5JLy80F1r6)

Issues PEP
* [PEP 581 -- Using GitHub Issues for CPython](https://www.python.org/dev/peps/pep-0581)
* [LWN: "Using GitHub Issues for Python"](https://lwn.net/Articles/754779)

The 2018 Python Language Summit
* [The 2018 Python Language Summit](https://lwn.net/Articles/754152)

Python Core Sprint 2018
* [Mariatta: Part 1](https://mariatta.ca/core-sprint-2018-part-1.html) and [Mariatta: Part 2](https://mariatta.ca/core-sprint-2018-part-2.html)
* [Victor Stinner](https://twitter.com/VictorStinner/status/1041219533439217665)

Python Core Sprint 2016
* [Lukasz Langa: Diversity on the Python Sprint in September](http://lukasz.langa.pl/12/diversity-python-sprint-september)

<!--
http://pycon.blogspot.com/2016/05/how-to-get-ready-for-pycon-development.html

https://www.youtube.com/watch?v=hhj7eb6TrtI&feature=youtu.be | Mariatta Wijaya - What is a Python Core Developer? - PyCon 2018 - YouTube

http://pyfound.blogspot.com/2018/09/cpython-core-developer-sprint-2018.html

https://wirtel.be/post/2018/10/19/2018-october-week40-contributions-to-cpython/ | October - Week 40: Contributions to CPython · Stephane Wirtel
-->

Core Workflow Tools
* [Core Workflow Tools GitHub](https://github.com/python/core-workflow)
* [cherry_picker](https://github.com/python/core-workflow/tree/master/cherry_picker) and [cherry picker PyPi](https://pypi.org/project/cherry-picker)
* [miss-islington](https://github.com/python/miss-islington)
* [Python Buildbot](https://www.python.org/dev/buildbot) and [Python Buildbot Wiki](https://wiki.python.org/moin/BuildBot)

<!--
https://www.youtube.com/watch?v=xvft-_8djUI | Keynote - Mariatta Wijaya - YouTube
https://www.slideshare.net/MariattaWijaya | Mariatta Wijaya, Flawed & disordered at Platform engineer | SlideShare

Mariatta
https://twitter.com/dbader_org/status/925764913041215489 | Dan Bader on Twitter: "BTW this is the foreword for Python Tricks: The Book by the amazing @mariatta (CPython core developer, PyLadies Vancouver organizer) https://t.co/kHYDw6uJRC"
https://www.blog.pythonlibrary.org/2017/09/25/pydev-of-the-week-mariatta-wijaya/ | PyDev of the Week: Mariatta Wijaya | The Mouse Vs. The Python
http://mariatta.ca/reflections-2017.html | mariatta.ca – 2017

https://github.com/python/miss-islington/issues
https://github.com/python/miss-islington/issues/130 | Don't wait for unrequired status checks. · Issue #130 · python/miss-islington

https://github.com/Mariatta/close-all-pr | Mariatta/close-all-pr
https://github.com/Mariatta/black_out | Mariatta/black_out: 🐍🌚🤖 GitHub bot that formats code with `black`
https://github.com/Mariatta/miss-islington/tree/master/backport | miss-islington/backport at master · Mariatta/miss-islington
https://www.slideshare.net/MariattaWijaya/pythonpowered-savage-garden-hotline | Python-Powered Savage Garden Hotline
https://github.com/Mariatta/mariatta-bot | Mariatta/mariatta-bot: Mariatta's GitHub bot
https://pypi.org/project/pytaco/ | pytaco · Warehouse (PyPI)
https://github.com/Mariatta/taco-py | Mariatta/taco-py: Figure out how many taco to order for your meetup
https://github.com/Mariatta/tic_tac_taco_pizza | GitHub - Mariatta/tic_tac_taco_pizza: Play tic tac toe, with taco and pizza
https://github.com/Mariatta/cloner

https://zapier.com/ | Zapier | The easiest way to automate your work
https://www.google.com/search?q=Nexmo+Voice+API&oq=Nexmo+Voice+API&aqs=chrome..69i57j0l2.241j0j7&sourceid=chrome&ie=UTF-8 | Nexmo Voice API - Google Search
https://aiohttp.readthedocs.io/en/stable/ | Welcome to AIOHTTP — aiohttp 3.4.4 documentation
https://github.com/brettcannon/gidgethub | brettcannon/gidgethub: An async GitHub API library for Python
https://developer.github.com/v3/ | GitHub API v3 | GitHub Developer Guide
https://developer.github.com/v3/repos/branches/#get-required-status-checks-of-protected-branch | Branches | GitHub Developer Guide
https://github.com/berkerpeksag/cpython-merge-bot

https://docs.google.com/spreadsheets/d/1JSX8fBmPb84emTmV0Kmyf0_r6R0kZM0h9Wdm91tn7Kg/edit#gid=0
http://distrowatch.com/table.php?distribution=mint
https://www.reddit.com/r/Python/comments/41kn28/looking_for_a_table_of_python_versions_shipped_by/
https://github.com/Mariatta/python_versions_and_distros
-->

Sphinx and Django-Sphinx
* [Python Docs Theme (Sphinx)](https://github.com/python/python-docs-theme)
* [Sphinx](http://sphinx-doc.org)  
* [Django-Sphinxdoc PyPi](https://pypi.python.org/pypi/django-sphinxdoc) 
* [Read the Docs Sphinx Theme GitHub](https://github.com/snide/sphinx_rtd_theme) 

<!--
Doc/build/html/index.html - Google Search
https://github.com/python/core-workflow/issues/174 | pip install blurb successfully installs with Python < 3.5 · Issue #174 · python/core-workflow
https://pypi.python.org/pypi/blurb

https://devguide.python.org/documenting/#building-the-documentation | 7. Documenting Python — Python Developer's Guide
-->

Python Docs- Packaging
* [Distributing Python Modules](https://docs.python.org/3/distributing/index.html)

Python- Official Packaging Info
* [Sample Project](https://github.com/pypa/sampleproject)
* [Python Packaging User Guide](https://packaging.python.org) and [Python Packaging User Guide GitHub](https://github.com/pypa/python-packaging-user-guide) 
* [Python Packaging Tutorials](https://packaging.python.org/tutorials) 
* [Python Packaging Guides](https://packaging.python.org/guides) 
* [Python Packaging Projects Tutorial](https://packaging.python.org/tutorials/packaging-projects)  
* [Python Packaging Key Projects](https://packaging.python.org/key_projects)
* [The Sheer Joy of Packaging! Scipy 2018 Tutorial](https://python-packaging-tutorial.readthedocs.io/en/latest)

Python- Wheel (versus Egg!)
* [Python Packaging Wheel vs. Egg](http://python-packaging-user-guide.readthedocs.io/discussions/wheel-vs-egg)
* [Wheel PyPi](https://pypi.python.org/pypi/wheel) and [Wheel Read the Docs](http://wheel.readthedocs.org)
* [Python Wheels](http://pythonwheels.com)

Python- Packages/Libraries
* [Pre-Production Deployment of Warehouse](https://pypi.org), [Warehouse GitHub](https://github.com/pypa/warehouse), and [Warehouse Read the Docs](https://warehouse.readthedocs.io)
* [PyPi Python Package Index PyPi](https://pypi.python.org/pypi)  

Core Packaging Utilities
* [PyPa Core Packaging Utilities](https://github.com/pypa/packaging)  
* [PyPa Core Packaging Utilities Documents](https://packaging.pypa.io/en/latest/) 

PyPi History
* ["Redesigning the Python Package Index"](http://pyfound.blogspot.com/2018/08/redesigning-python-package-index.html)
* ["A new package index for Python"](https://lwn.net/Articles/751458/)
* ["Warehouse: All New PyPI is now in beta"](http://pyfound.blogspot.com/2018/03/warehouse-all-new-pypi-is-now-in-beta.html)

Dustin Ingram
* ["Inside the Cheeseshop: How Python Packaging Works" (PyCon 2018)](https://dustingram.com/talks/2018/10/23/inside-the-cheeseshop)
* ["PyPI is dead. Long live PyPI!"](https://dustingram.com/articles/2018/04/16/pypi-is-dead-long-live-pypi)

Python- Cookiecutter Creating Packages
* [PyPi Release Checklist](https://gist.github.com/audreyr/5990987) and [PyPi Release Checklist 2](https://gist.github.com/audreyr/9f1564ea049c14f682f4)
* [Cookiecutter Django Package GitHub](https://github.com/pydanny/cookiecutter-djangopackage)
* [Cookiecutter PyPackage Read the Docs](https://cookiecutter.readthedocs.org/en/latest)
* [Cookiecutter PyPackage GitHub](https://github.com/audreyr/cookiecutter-pypackage)
* [Cookiecutter via Django Rest Framework: How to create a Third Party Package](http://www.django-rest-framework.org/topics/third-party-resources)

Python- Additional Packaging Tutorials
* [Digital Ocean Tutorial "How to Package and Distribute Python Applications"](https://www.digitalocean.com/community/tutorials/how-to-package-and-distribute-python-applications) 
* [Free Code Camp "How to publish your own Python Package on PyPi"](https://medium.freecodecamp.org/how-to-publish-a-pyton-package-on-pypi-a89e9522ce24)

Django
* [Django: How to write reusable apps](https://docs.djangoproject.com/en/2.0/intro/reusable-apps).

<!--
Check core developer repo info

https://www.python.org/dev/peps/pep-0518/ | PEP 518 -- Specifying Minimum Build System Requirements for Python Projects | Python.org
https://www.python.org/dev/peps/pep-0496/ | PEP 496 -- Environment Markers | Python.org
https://www.python.org/dev/peps/pep-0508/#id23 | PEP 508 -- Dependency specification for Python Software Packages | Python.org

https://docs.python-guide.org/shipping/packaging/ | Packaging Your Code — The Hitchhiker's Guide to Python
https://docs.python-guide.org/shipping/freezing/#freezing-your-code-ref | Freezing Your Code — The Hitchhiker's Guide to Python

https://packaging.python.org/glossary/ | Glossary — Python Packaging User Guide
https://packaging.python.org/guides/distributing-packages-using-setuptools/ | Packaging and distributing projects — Python Packaging User Guide
https://packaging.python.org/key_projects/#setuptools | Project Summaries — Python Packaging User Guide
https://packaging.python.org/key_projects/#wheel | Project Summaries — Python Packaging User Guide
https://setuptools.readthedocs.io/en/latest/setuptools.html | Building and Distributing Packages with Setuptools — setuptools 39.2.0 documentation

https://packaging.python.org/tutorials/installing-packages/
https://packaging.python.org/tutorials/distributing-packages/ | Packaging and distributing projects
https://packaging.python.org/tutorials/distributing-packages/#project-urls

https://packaging.python.org/discussions/install-requires-vs-requirements/ | install_requires vs requirements files — Python Packaging User Guide

pip is the The PyPA recommended tool for installing Python packages.
https://packaging.python.org/guides/tool-recommendations/

https://pip.pypa.io/en/stable/user_guide/#requirements-files

http://www.kennethreitz.org/essays/a-better-pip-workflow
https://docs.pipenv.org/advanced/#pipfile-vs-setup-py
https://github.com/pypa/pipfile#the-concept
https://github.com/pypa/pipfile

Pyenv and Pipenv
https://github.com/pyenv/pyenv-virtualenv | pyenv/pyenv-virtualenv: a pyenv plugin to manage virtualenv (a.k.a. python-virtualenv)
https://pipenv.readthedocs.io/en/latest/ | Pipenv: Python Dev Workflow for Humans — pipenv 8.3.2 documentation
https://github.com/kennethreitz/pipenv | kennethreitz/pipenv: Python Development Workflow for Humans.

pyproject.toml
https://github.com/pypa/pipfile/issues/27
-->

<!--
https://wiki.python.org/moin/Distutils | Distutils - Python Wiki

https://docs.python.org/3.6/distutils/introduction.html | 1. An Introduction to Distutils — Python 3.6.4rc1 documentation
https://docs.python.org/3/distutils/setupscript.html | 2. Writing the Setup Script — Python 3.6.4rc1 documentation
https://docs.python.org/3.1/distutils/uploading.html | 7. Uploading Packages to the Package Index — Python v3.1.5 documentation
https://docs.python.org/3.6/distutils/packageindex.html#package-index | 6. The Python Package Index (PyPI) — Python 3.6.4rc1 documentation
https://docs.python.org/3.6/distutils/sourcedist.html | 4. Creating a Source Distribution — Python 3.6.4rc1 documentation

https://pip.pypa.io/en/stable/reference/pip_wheel

https://pyup.io/ | Manage your Python dependencies with pyup.io
https://docs.travis-ci.com/user/deployment/pypi/ | PyPI deployment - Travis CI
http://www.pyinstaller.org/ | Welcome to PyInstaller official website — PyInstaller

https://blog.jetbrains.com/pycharm/2017/05/how-to-publish-your-package-on-pypi/ | How to Publish Your Package on PyPI | PyCharm Blog
https://tom-christie.github.io/articles/pypi/ | Uploading to PyPI – Tom Christie

http://the-hitchhikers-guide-to-packaging.readthedocs.io/en/latest/contributing.html | Contribute Your Package to the World — The Hitchhiker's Guide to Packaging 1.0 documentation

https://pythonhosted.org/setuptools/formats.html
https://pythonhosted.org/an_example_pypi_project/setuptools.html

https://github.com/twoscoops/Creating-and-Distributing-Python-Packages | twoscoops/Creating-and-Distributing-Python-Packages
https://courses.twoscoopspress.com/courses/take/creating-and-distributing-python-packages | Two Scoops Press


https://www.youtube.com/watch?v=AQsZsgJ30AE

New
https://www.youtube.com/watch?time_continue=1&v=QgZ7qv4Cd0Y | How To Publish A Package On PyPI - YouTube

https://packaging.python.org/guides/making-a-pypi-friendly-readme/ | Making a PyPI-friendly README — Python Packaging User Guide

https://www.python.org/dev/peps/pep-0427/ | PEP 427 -- The Wheel Binary Package Format 1.0 | Python.org
https://www.python.org/dev/peps/pep-0438/ | PEP 438 -- Transitioning to release-file hosting on PyPI | Python.org
https://www.python.org/dev/peps/pep-0440/ | PEP 440 -- Version Identification and Dependency Specification | Python.org
https://www.python.org/dev/peps/pep-0517/

https://pip.pypa.io/en/stable/reference/pip_install/#editable-installs | pip install — pip 18.1 documentation

https://github.com/pypa/warehouse/issues
https://github.com/pypa/packaging-problems/issues | Issues · pypa/packaging-problems

https://twitter.com/pypi_updates2 | PyPI Recent Updates (@pypi_updates2) | Twitter

https://wiki.python.org/moin/CheeseShop | CheeseShop - Python Wiki

Testing
http://pyfound.blogspot.com/2018/02/python-package-maintainers-help-test.html | Python Software Foundation News: Python package maintainers, help test the new PyPI!
https://docs.google.com/forms/d/e/1FAIpQLSczrATlexkR1_gBt727eGnc05FCt-75Mx2usMq1wvCm_cLddg/viewform | Conducting user tests on PyPI
https://gist.github.com/nlhkabu/a0b1ae0016a2641f6b79d9ace9110403 | Recruiting User Testers for PyPI
https://docs.google.com/forms/d/e/1FAIpQLSfABpsRcVYt7RDJEsbL_2CnyH-IKXRCRwaBhCm4sYnNI6yB3A/viewform | Buy a feature
http://whoisnicoleharris.com/2018/05/17/warehouse-accessibility.html

Package Stats
* ["How to get PyPI download statistics"](https://kirankoduru.github.io/python/pypi-stats.html)

https://bigquery.cloud.google.com/table/the-psf:pypi.downloads | Google BigQuery
https://mail.python.org/pipermail/distutils-sig/2013-June/021344.html | [Distutils] Download Counts on PyPI
-->

Package Helpers
* [Twine GitHub](https://github.com/pypa/twine) and [Twine PyPi](https://pypi.python.org/pypi/twine)

Python Sprints
* [Python Sprints](https://python-sprints.github.io)

<!--
https://wiki.python.org/moin/EuroPython2018/CPython | EuroPython2018/CPython - Python Wiki
https://twitter.com/europython/status/1019172899654119424 | EuroPython on Twitter: "Want to run a sprint at EuroPython 2018 
-->

Mailing List and Permissions History
* [Python Core Workflow Mailing List](https://mail.python.org/mailman/listinfo/core-workflow)
* [Permissions History](https://devguide.python.org/developers/#permissions-history)
* [Developer Log](https://github.com/python/devguide/blob/bbd38631554165a64e187bd29815125098159a13/developers.rst)

<!--
https://www.python.org/psf/fellows/ | PSF Fellow Membership | Python.org

https://mail.python.org/mailman/listinfo/psf-community | PSF-Community Info Page
-->

Python Mentors
* [Python Mentors](http://pythonmentors.com)

Mentoring and diversity for Python (2018)
* [Mentoring and diversity for Python](https://lwn.net/Articles/757950)

Python Mentorship for Women (Guido van Rossum), Female Core Devs (2016)
* [Python Mentorship for Women](https://twitter.com/mariatta/status/737689052736978945)
* [Mariatta and Allison Randal](https://twitter.com/matrixise/status/865678978677223429)
* ["Imposter syndrome is real"](https://twitter.com/KatiMichel/status/865740929512071168)

<!--
Mentorship
https://mail.python.org/pipermail/python-committers/2018-May/005389.html | [python-committers] Proposing Mark Shannon to be a core developer
-->

Python Master/Slave Terminology
* [PR "Avoid master/slave terminology"](https://github.com/python/cpython/pull/9101)
* [Python Bug Tracker: "Avoid master/slave terminology"](https://bugs.python.org/issue34605)

python.org Contributing
* [python.org GitHub](https://github.com/python/pythondotorg)
* [python.org Issues](https://github.com/python/pythondotorg/issues)
* [python.org Staging](https://staging.python.org)
* [python.org Read the Docs](https://pythondotorg.readthedocs.io)
* [python.org Read the Docs Install](https://pythondotorg.readthedocs.io/install.html) and [python.org Read the Docs Contributing](https://pythondotorg.readthedocs.io/contributing.html)
* [Couldn't set up local environment](https://github.com/python/pythondotorg/issues/987)
* [python.org Contributors](https://github.com/python/pythondotorg/graphs/contributors)

<!--
https://github.com/python/pycon-code-of-conduct
https://mail.python.org/pipermail/psf-community/2018-April/000488.html | [PSF-Community] PSF Code of Conduct Work Group: call for membership applications
-->

Python and Django Git Bootcamps and Cheat Sheets
* [Python: Git Bootcamp and Cheat Sheet](https://docs.python.org/devguide/gitbootcamp.html)
* [Django: Working with Git and GitHub](https://docs.djangoproject.com/en/1.8/internals/contributing/writing-code/working-with-git)

Django History
* [Jul 13, 2005 "Created basic repository structure"](https://github.com/django/django/commit/d6ded0e91bcdd2a8f7a221f6a5552a33fe545359)
* [Born in the LFK](https://pyvideo.org/django-birthday/born-in-the-lfk.html)
* [Django Birthday Event](https://djangobirthday.com)
* [Django Project Tweet: Happy 10th Birthday Django](https://twitter.com/djangoproject/status/620639689599516672)
* [Django Project Blog: Happy 10th Birthday Django](https://www.djangoproject.com/weblog/2015/jul/13/happy-10th-birthday-django)
* [LJWorld: Happy Birthday Django](http://www2.ljworld.com/news/2015/jul/09/happy-birthday-django)
* [LJWorld Redesign](http://www2.ljworld.com/news/2018/jun/26/redesign-ljworld)

State of Django
* [State of Django Panel (DjangoCon US 2018)](https://2018.djangocon.us/talk/state-of-django-panel)
* [State of Django Panel Video (DjangoCon US 2018)](https://www.youtube.com/watch?v=TrAFQW7Wza0&t=356s)
* [Jacob Kaplan-Moss State of Django (PyCon 2009)](https://www.slideshare.net/jacobian/state-of-django)

About Django 
* [Why this Project Exists](https://docs.djangoproject.com/en/dev/faq/general/#why-does-this-project-exist)

Django Software
* [Django Reporting Bugs and Requesting Features](https://docs.djangoproject.com/en/dev/internals/contributing/bugs-and-features/#reporting-bugs)
* [Django Submitting a Patch](https://docs.djangoproject.com/en/dev/internals/contributing/writing-code/submitting-patches/)

djangoproject.com Contributing
* [djangoproject.com GitHub](https://github.com/django/djangoproject.com)
* [code.djangoproject.com](https://code.djangoproject.com)
* [dashboard.djangoproject.com](https://dashboard.djangoproject.com)

DEPS (Django Enhancement Proposals)
* [DEPS (Django Enhancement Proposals) GitHub](https://github.com/django/deps)

Django Contributing
* [Django Internals](https://docs.djangoproject.com/en/dev/internals)
* [Django Contributing](https://docs.djangoproject.com/en/dev/internals/contributing)
* [Tickets](https://code.djangoproject.com/query)
* [Life of a Django Ticket](https://docs.google.com/presentation/d/1Ao0S3Z-VRn_pcT5T4mXIhv3t3liQ3ZrwqaGeDqz9XCQ/edit)

Release Cadence
* [Django Release Cadence](https://docs.djangoproject.com/en/dev/internals/release-process/#internal-release-cadence)

Django, Releases, Announcements, and Roadmaps
* [Django Releases](https://docs.djangoproject.com/en/stable/releases)
* [Django Announcements](https://groups.google.com/forum/#!forum/django-announce)
* [Django 2.1 Roadmap](https://code.djangoproject.com/wiki/Version2.1Roadmap) 
* [Django 2.0 Release Notes](https://docs.djangoproject.com/en/2.0/releases/2.0) and [Django 2.0 Blog Post](https://www.djangoproject.com/weblog/2017/dec/02/django-20-released)
* [Django Roadmap to 2.0](https://www.djangoproject.com/weblog/2015/jun/25/roadmap) 

Your Framework Needs You
* [Carlton Gibson: Your Framework Needs You](https://2018.djangocon.us/talk/your-web-framework-needs-you)

Dissolving Django Core
* [James Bennett: Core No More](https://www.b-list.org/weblog/2018/nov/20/core)
* [Django DEP: Add draft DEP dissolving Django core. by ubernostrum](https://github.com/django/deps/pull/47)
* [Rough draft Django DEP: Dissolving Django Core](https://github.com/ubernostrum/deps/blob/draft-dissolve-core/draft/XXXX-dissolve-core.rst)
* [Draft proposal: dissolving "Django core" - Google Groups](https://groups.google.com/forum/#!topic/dsf-members/yqnWGII63mI)
* [On the Django core team - Google Groups](https://groups.google.com/forum/#!topic/dsf-members/GWOzvsOAGUs)

Mentorship
* [Django Core Mentorship Mailing List](https://docs.djangoproject.com/en/dev/internals/mailing-lists/#django-core-mentorship)

Django Developers Mailing Lists, Forum and Slack
* [Django Mailing Lists](https://docs.djangoproject.com/en/dev/internals/mailing-lists)
* [Django Google Developers Forum](https://groups.google.com/forum/#!forum/django-developers) 
* [Django Developers Slack](https://django-developers.herokuapp.com)

<!--
https://groups.google.com/forum/#!forum/django-announce | (99+) django-announce – Google Groups
https://groups.google.com/forum/#!forum/django-core-mentorship | Django Core Mentorship - Google Groups
https://groups.google.com/forum/#!forum/django-updates | (99+) Django updates – Google Groups
-->

Django People- Current
* [Django Organization](https://docs.djangoproject.com/en/dev/internals/organization)
* [DSF Committees](https://www.djangoproject.com/foundation/committees)
* [DSF Developer Members](https://www.djangoproject.com/foundation/developer-members)
* [Django Team List (Old?)](https://www.djangoproject.com/foundation/teams)

Django People- Historical
* [Django Core Developers (Old Version)](https://docs.djangoproject.com/en/1.7/internals/committers/#core-developers)
* [Django Organization Repo People](https://github.com/orgs/django/people)

Django Code of Conduct and CLA
* [Django Code of Conduct](https://www.djangoproject.com/conduct)
* [Django Contributor License Agreements](https://www.djangoproject.com/foundation/cla)

<!--
https://github.com/django/code-of-conduct
-->

<!--
https://people.djangoproject.com

https://www.djangoproject.com/foundation/

Django 

Django committers: The original team
Adrian Holovaty
http://www.holovaty.com
Simon Willison
https://simonwillison.net
Jacob Kaplan-Moss
https://jacobian.org
Wilson Miner
https://wilsonminer.com

Teams

Adam Johnson
https://adamj.eu
Andrew Godwin
https://www.aeracode.org
Aymeric Augustin
https://myks.org/en
Carl Meyer
Carlton Gibson
Claude Paroz
Collin Anderson
Florian Apolloner
Jannis Leidel
James Bennett
https://www.b-list.org
Josh Smeaton
Julien Phalip
Karen Tracey
Loïc Bistuer
Luke Plant
Marc Tamlyn
Mariusz Felisiak
Markus Holtermann
Michael Manfre
Paul McMillan
Sasha Romijn
Sergey Fedoseev
Shai Berger
Simon Charette
Tim Graham
Tobias McNulty
Tom Christie

Django committers past

Current developers

Alex Gaynor
Anssi Kääriäinen
Baptiste Mispelon
Brian Rosner
Bryan Veloso
Chris Beaven
Daniel Lindsley
Daniele Procida
Donald Stufft
Gabriel Hurley
Gary Wilson
Honza Král
Ian Kelly
Idan Gazit
James Tauber
Jeremy Dunck
Joseph Kocherhans
Julien Phalip
Justin Bronn
Matt Boersma
Preston Holmes
Paul McMillan
Ramiro Morales
Russell Keith-Magee
Simon Meers

Developers Emeritus
Georg “Hugo” Bauer
Robert Wittams

Additonal Org Members
Adrienne Lowe
Andreas Pelme
Artem Malyshev
Avelino
Frank Wiles
Gary Wilson Jr.
Greg Chapple
Jeff Triplett
Jon Dufresne
Katie McLaughlin
Paul Hallett

Trey Hunner
https://treyhunner.com
Lacey Williams Henschel
https://www.laceyhenschel.com


Python Push Access

TGP: Tim Peters
GFB: Georg Brandl
BAC: Brett Cannon
BCP: Benjamin Peterson
NCN: Neal Norwitz
DJG: David Goodger
MvL: Martin v. Loewis
GvR: Guido van Rossum
RDH: Raymond Hettinger

Nick Coghlan
http://python-notes.curiousefficiency.org

Lisa Roach
Emily Morehouse
Pablo Galindo Salgado
Mark Shannon
Petr Viktorin
Nathaniel J. Smith
Julien Palard
Ivan Levkivskyi
Carol Willing
Mariatta Wijaya
Maciej Szulik
Xiang Zhang
INADA Naoki
Xavier de Gaye
Davin Potts
Martin Panter
Paul Moore
Chris Angelico
Santoso Wijaya
Stefan Richthofer
Robert Collins
Darjus Loktevic
Berker Peksağ
Steve Dower
Kushal Das
Steven d’Aprano
Yury Selivanov
Zachary Ware
Donald Stufft
Ethan Furman
Roger Serwy
Serhiy Storchaka
Chris Jerdonek
Daniel Holth
Eric Snow
Jeff Allen
Peter Moody
Hynek Schlawack
Richard Oudkerk
Andrew Svetlov
Petri Lehtinen
Meador Inge
Sandro Tosi
Charles-François Natali
Nadeem Vawda
Carl Friedrich Bolz
Alexis Métaireau, Elson Rodriguez, Kelsey Hightower, Michael Mulich and Walker Hale
Jeff Hardy
Alex Gaynor and Maciej Fijalkowski
Ross Lagerwall
Eli Bendersky
Ned Deily
David Malcolm
Tal Einat
Łukasz Langa
Daniel Stutzbach
Ask Solem
George Boutsioukis
Éric Araujo
Terry Reedy
Brian Quinlan
Reid Kleckner
Alexander Belopolsky
Tim Golden
Giampaolo Rodolà
Jean-Paul Calderone
Brian Curtin
Florent Xicluna
Dino Viehland
Larry Hastings
Victor Stinner
Stefan Krah
Doug Hellmann
Ezio Melotti
Paul Kippes
Ron DuPlain
Allison Randal (Parrot), Michael Foord (IronPython), Jim Baker, Philip Jenvey, and Frank Wierzbicki (all Jython)
R. David Murray
Chris Withers
Tarek Ziadé
Hirokazu Yamamoto
Antoine Pitrou
Jesse Noller
Gregor Lingl
Robert Schuppenies
Rodrigo Bernardo Pimentel
Heiko Weinen
Jesús Cea
Guilherme Polo
Thomas Lee
Jeroen Ruigrok van der Werven
Josiah Carlson
Benjamin Peterson
Jerry Seutter
Jeff Rush
David Wolever
Trent Nelson
Mark Dickinson
Amaury Forgeot d’Arc
Christian Heimes
Chris Monson
Bill Janssen
Jeffrey Yasskin
Mark Summerfield
Armin Ronacher
Senthil Kumaran
Alexandre Vassalotti
Travis Oliphant
Ziga Seilnacht
Pete Shinners
Pat Maupin and Eric V. Smith
Steven Bethard
Josiah Carlson
Collin Winter
Lars Gustaebel
Matt Fleming
Jackilyn Hoxworth
Mateusz Rukowicz
Andrew Dalke Christian Tismer Jack Diederich John Benediktsson Kristján V. Jónsson Martin Blais Richard Emslie Richard Jones Runar Petursson Steve Holden Richard M. Tew
Steven Bethard
Talin
George Yoshida
Ronald Oussoren
Bob Ippolito
Gregory K Johnson
Floris Bruynooghe
Georg Brandl
Terry Reedy
Armin Rigo
Eric Price
Eric S. Raymond

15.2. Permissions Dropped on Request¶
Xavier de Gaye’s privileges were dropped on 25 January 2018 by Brett Cannon per his request.
Andrew MacIntyre’s privileges were dropped on 2 January 2016 by BCP per his request.
Skip Montanaro’s permissions were removed on 21 April 2015 by BCP per his request.
Armin Rigo permissions were removed on 2012.
Roy Smith, Matt Fleming and Richard Emslie sent drop requests. 4 Aug 2008 GFB
Per note from Andrew Kuchling, the permissions for Gregory K Johnson and the Summer Of Code project are no longer needed. 4 Aug 2008 GFB
Per note from Andrew Kuchling, the permissions for Gregory K Johnson and the Summer Of Code project are no longer needed. AMK will make any future checkins directly. 16 Oct 2005 RDH
Johannes Gijsbers sent a drop request. 27 July 2005 RDH
Floris Bruynooghe sent a drop request. 14 July 2005 RDH
Paul Prescod sent a drop request. 30 Apr 2005 RDH
Finn Bock sent a drop request. 13 Apr 2005 RDH
Eric Price sent a drop request. 10 Apr 2005 RDH
Irmen de Jong requested dropping CVS access while keeping tracker access. 10 Apr 2005 RDH
Moshe Zadka and Ken Manheimer sent drop requests. 8 Apr 2005 by RDH
Steve Holden, Gerhard Haring, and David Cole sent email stating that they no longer use their access. 7 Apr 2005 RDH

PSF Fellows

Officers
President: Guido van Rossum
Chair: Naomi Ceder
Vice Chairs: Van Lindberg, Thomas Wouters
Director of Operations: Ewa Jodlowska
Secretary: Ewa Jodlowska, Betsy Waliszewski
Treasurer: Kurt B. Kaiser
Communications: Kushal Das, Lorena Mesa
General Counsel: Van Lindberg
Event Coordinator: Ewa Jodlowska, Betsy Waliszewski
PyCon Chair: Ernest W. Durbin III

Board of Directors
Naomi Ceder
Kushal Das
Eric Holscher
Ewa Jodlowska
Jackie Kazil
Van Lindberg
Lorena Mesa
Katie McLaughlin
Marlene Mhangami
Christopher Neugebauer
Anna Ossowski
Jeff Triplett
Thomas Wouters
Also see: Duties & Responsibilities of Directors and History of PSF Officers & Directors.

PSF Bloggers
A Jesse Jiryu Davis
Anwesha Das
Christy Heaton
Jonatas Baldin
Quan Nguyen
Tania Allard (Sanchez Monroy)
Craig Lang

Fellows

The year the member was elected is in parentheses.

Aisha Bello (2017)

Alex Martelli (2002)
Alex Willmer (2010)
Allison Randal (2010)
Amaury Forgeot d'Arc (2008)
Amber Brown (2018)
Anand Chitipothu (2012)
Anand Pillai (2010)
Andreas Jung (2012)
Andrew Dalke (2004)

Andrew Kuchling (2003)
Anna Martelli Ravenscroft (2006)
Anne Gentle (2012)
Anthony Baxter (2002)
Anthony Scopatz (2013)
Anthony Shaw (2018)
Antoine Pitrou (2010)
Antonio Cuni (2012)
Arc Riley (2010)
Armin Ronacher (2012)
Armin Stroß-Radschinski (2012)
Asheesh Laroia (2011)
Audrey Roy (2011)
Barbara Shaurette (2013)
Barry Warsaw (2001)
Belinda Weaver (2017)
Ben Bangert (2009)
Benjamin Peterson (2009)
Benoit Chesneau (2012)
Brandon Rhodes (2010)
Brett Cannon (2003)
Brian Costlow (2017)
Brian Curtin (2011)
Brian K. Jones (2011)
Brian Zimmer (2005)
Bruno Rocha (2012)
C. Titus Brown (2008)
Cameron Laird (2002)
Carl F. Karsten (2010)
Carl Friedrich Bolz (2010)

Carol Willing (2017)
Carrie Anne Philbin (2017)
Catherine Devlin (2007)
Chris McDonough (2010)
Chris Neugebauer (2013)
Chris Withers (2012)
Christian Barra (2018)
Christian Heimes (2008)
Christian Scholz (2010)
Christian Theune (2012)
Christian Tismer (2001)
Christopher Armstrong (2009)
Christopher MacGowan (2012)
Chukwudi Nwachukwu (2017)
Claudiu Popa (2018)
Cory Benfield (2017)
Damien George (2017)
Dana Bauer (2012)
Daniel Greenfeld (2011)
Daniel Pope (2017)

Dave Malcolm (2012)
David Goodger (2003)
David M. Beazley (2002)
David Markey (2018)
David Mertz (2008)
Dean Troyer (2012)
Diana Clarke (2013)
Dino Viehland (2009)
Don Sheu (2017)
Donald Beaudry (2002)

Doug Hellmann (2009)
Doug Napoleone (2007)
Duncan McGreggor (2009)
Dusty Phillips (2017)
Eduardo Mendes (2018)
Emmanuelle Gouillart (2013)
Eric Holscher (2013)
Eric Jones (2002)
Eric S. Raymond (2001)
Eric V. Smith (2010)
Érico Andrei (2013)
Ernest W. Durbin III (2018)
Ewa Jodlowska (2012)
Eyitemi Egbejule (2018)
Fabio Pliger (2011)
Facundo Batista (2005)
Fernando Masanori Ashikaga (2017)
Fernando Perez (2010)
Filip Kłębczyk (2017)
Finn Bock (2001)
Frank Wierzbicki (2009)
Fred L. Drake, Jr. (2001)
Fredrik Lundh (2001)
Gael Varoquaux (2013)
Gavin M. Roy (2011)
Georg Brandl (2006)
George Paci (2006)
Giles Thomas (2012)
Giovanni Bajo (2011)
Glyph Lefkowitz (2009)
Graham Dumpleton (2009)
Greg Ewing (2002)
Greg Stein (2001)
Greg Ward (2001 - converted to emeritus in 2008, re-activated in 2013)
Greg Wilson (2010)
Gregory Smith (2011)
Guido van Rossum (2001)
Gustavo Niemeyer (2004)
Hanno Schlichting (2012)
Harald Armin Massa (2010)
Henrique Bastos (2012)
Hye-Shik Chang (2004)
Hynek Schlawack (2013)
Ian Bicking (2010)
Ivaylo Bachvarov (2017)
Jack Diederich (2010)
Jack Jansen (2001)
Jackie Kazil (2017)
Jacob Hallén (2010)

James Blair (2012)

Jan Ulrich Hasecke (2012)

Jason Pellerin (2013)
Jason Tishler (2003)
Jean-Paul Calderone (2009)
Jeff Elkner (2004)
Jeff Reback (2018)
Jeff Rush (2007)

Jeremy Hylton (2001)
Jesse Noller (2009)
Jessica McKellar (2011)
Jim Baker (2009)
Jim Fulton (2001)
Jim Hugunin (2006)
Jonathan Hartley (2011)
Jonathan LaCour (2011)
Joris Van den Bossche (2018)
Joshua McKenty (2012)
Juan Luis Cano (2017)
Just van Rossum (2002)
Ka-Ping Yee (2001)
Kamon Ayeva (2013)
Katie Cunningham (2013)
Katie McLaughlin (2018)
Ken Manheimer (2001)
Kenneth Reitz (2012)
Kevin Altis (2003)
Kirby Urner (2009)
Kurt B. Kaiser (2004)
Kushal Das (2013)
Lance Ellinghaus (2010)
Larry Hastings (2012)
Laura Cassell (2017)
Laura Creighton (2007)
Laurens Van Houtven (2010)
Lennart Regebro (2011)
Lorena Mesa (2017)
Luciano Ramalho (2012)
Łukasz Langa (2017)
Lynn Root (2013)
Mabel Delgado (2017)
Mai Giménez (2017)
Manuel Kaufmann (2017)
Marc Garcia (2018)
Marc-André Lemburg (2001)
Mariano Reingart (2012)
Mario Corchero (2017)
Mário Sérgio Oliveira de Queiroz (2017)
Mark Dickinson (2008)
Mark Hammond (2001)
Mark Lutz (2002)
Mark McLoughlin (2012)
Mark Ramm (2009)
Martijn Faassen (2009)
Martin Aspeli (2012)
Martin von Löwis (2001)
Massimo DiPierro (2011)
Mathieu Leduc-Hamel (2013)
Matthew Dixon Cowles (2003)
Matthias Klose (2009)
Michael Bayer (2010)
Michael Foord (2009)
Michael Hudson (2002)
Michael Kennedy (2018)
Michael Sparks (2010)
Michelle Rowley (2012)
Mike Driscoll (2011)
Mike Fletcher (2009)
Mike McLay (2002)
Mike Müller (2010)
Mike Olson (2002)
Mike Orr (2011)
Monty Taylor (2012)
Moshe Zadka (2001)
Naomi Ceder (2011)
Nathaniel Smith (2018)
Neal Norwitz (2002)
Ned Batchelder (2011)
Ned Deily (2013)
Neil Schemenauer (2001)
Nicholas H. Tollervey (2012)
Nick Barcet (2012)
Nick Coghlan (2007)
Nicolas Chauvat (2010)
Noah Gift (2010)
Noah Kantrowitz (2012)
Noufal Ibrahim (2012)
Ola Sendecka (2017)
Ola Sitarska (2017)
Olivier Grisel (2013)
Osvaldo Santana (2013)
Paul Everitt (2006)

Paulo Nuin (2011)
Peter Inglesby (2017)
Peter Kropf (2012)
Peter Schneider-Kamp (2001)
Phil Thompson (2009)
Philip Jenvey (2011)
Prabhu Ramachandran (2010)
Quentin Wright (2010)
R. David Murray (2010)
Ralph Green (2010)
Raymond Hettinger (2003)
Reimar Bauer (2013)
Richard Jones (2003)
Richard Kellner (2017)
Richard Taylor (2011)
Rick Copeland (2011)
Rizky Ariestiyansyah (2018)
Robert Collins (2013)
Robert Kern (2010)
Robin Dunn (2002)
Ronald Oussoren (2011)
Ruben Orduz (2017)

Samuele Pedroni (2001)
Sean Reifschneider (2007)
Selena Deckelman (2017)
Simon Cross (2013)

Sjoerd Mullender (2001)
Stefan Behnel (2018)
Stefan van der Walt (2013)
Stephan Deibel (2003)
Stephane Wirtel (2013)
Stephen Hawkes (2012)
Stephen Thorne (2010)
Steve Holden (2003)
Steven d’Aprano (2010)
Ted Pollari (2009)
Terri Oda (2013)
Terry Peppers (2010)
Terry Reedy (2010)
Tetsuya Morimoto (2011)
Thierry Carrez (2012)
Tom Augspurger (2018)
Thomas Waldmann (2009)
Thomas Wouters (2001)
Tim Ansell (2012)
Tim Couper (2010)
Tim Golden (2010)
Tim Peters (2001)
Travis Oliphant (2006)
Trent Mick (2001)
Tres Seaver (2012)
Trevor Toenjes (2004)
Uche Ogbuji (2002)
Van Lindberg (2008)
Vasudev Ram (2010)
Vicky Twomey-Lee (2012)
Victor Stinner (2010)
Vinay Sajip (2003)
Vish Ishaya (2012)
Walter Dörwald (2003)
Wes McKinney (2018)
Wesley Chun (2010)
Wilfredo Sanchez Vega (2012)
Yamila Moreno (2017)
Yannick Gingras (2011)
Yury Selivanov (2018)
Zeth Green (2010)

Emeritus Fellows
These are our emeritus members (year of election / year of emeritus conversion):
David Abrahams (2002/2008)
Paul Boddie (2010/2015)
Paul F. Dubois (2002/2008) Paul Dubois was an original contributor to Numerical Python, and its coordinator for five years. Paul also hosted the Fourth International Python Conference in 1996.
Lars Marius Garshol (2001/2005)
Charles G. Waldman (2001/2005)
Skip Montanaro (2001/2008)
Sam Rushing (2002/2008)
Danny Yoo (2004/2008)
Thomas Heller (2001/2009)
Neil Hodgson (2002/2009)
Armin Rigo (2004/2010)
David Ascher (2001/2011)
Steven Bethard (2007/2011)
Maciej Fijalkowski (2011/2012)
Paul Prescod (2001/2013)
André Roberge (2010/2013)
Tarek Ziadé (2010/2013)
Gloria W. Jacobs (2010/2013)
Aahz (2002/2013)
Holger Krekel (2010/2018)

Deceased Fellows
John Pinner (member from 2008-2015)
Malcolm Tredinnick (member since 2009)
-->
