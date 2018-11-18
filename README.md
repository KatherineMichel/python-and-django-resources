# Python and Django- Contributing

<!--
Django Notes
https://code.djangoproject.com/wiki/TitleIndex
https://code.djangoproject.com/wiki/NewbieMistakes | NewbieMistakes – Django
https://www.python.org/download/releases/2.2/descrintro/#metaclasses | Unifying types and classes in Python 2.2 | Python.org
https://code.djangoproject.com/wiki/DynamicModels | DynamicModels – Django
https://code.djangoproject.com/wiki/DevModelCreation | DevModelCreation – Django

https://mail.python.org/pipermail/python-dev/2018-July/154703.html | [Python-Dev] Status of Python CIs (buildbots, Travis CI, AppVeyor): july 2018

https://docs.python.org/2/howto/doanddont.html | Idioms and Anti-Idioms in Python — Python 2.7.15 documentation

https://docs.python.org/3/reference/import.html#open-issues | 5. The import system — Python 3.7.0 documentation

https://docs.python-guide.org/writing/gotchas/ | Common Gotchas — The Hitchhiker's Guide to Python
http://django-gotchas.readthedocs.io/en/latest/ | Welcome to Django gotchas documentation! — Django gotchas 0.1 documentation


My CPython Issue and Pull Requests
http://bugs.python.org/user26332

http://pyfound.blogspot.com/2018/01/the-python-software-foundation-is.html | Python Software Foundation News: The Python Software Foundation is looking for bloggers!

https://mail.python.org/pipermail/python-announce-list/2018-June/011976.html | Python 3.7.0 is now available! (and so is 3.6.6)

Django Core
https://www.amazon.com/Mastering-Django-Core-Complete-Guide/dp/099461683X | Mastering Django: Core: The Complete Guide to Django 1.8 LTS: Nigel George: 9780994616838: Amazon.com: Books

https://www.amazon.com/Guido%20Van%20Rossum/e/B0034OPA4K/ref=la_B0034OPA4K_st?rh=n%3A283155%2Cp_82%3AB0034OPA4K&qid=1505705520&sort=date-desc-rank | Amazon.com: Guido Van Rossum: Books, Biography, Blog, Audiobooks, Kindle

https://www.python.org/doc/essays/list2str/ | Python Patterns - An Optimization Anecdote | Python.org

https://jakevdp.github.io/blog/2014/05/09/why-python-is-slow/ | Why Python is Slow: Looking Under the Hood | Pythonic Perambulations

https://devguide.python.org/coredev/ | 14. How to Become a Core Developer — Python Developer's Guide
Django Core Mentorship

https://legacy.python.org/dev/peps/ | PEP 0 -- Index of Python Enhancement Proposals (PEPs)

New functionality
https://www.python.org/dev/peps/pep-0553/ | PEP 553 -- Built-in breakpoint() | Python.org
https://www.python.org/dev/peps/pep-3107/ | PEP 3107 -- Function Annotations | Python.org
https://mail.python.org/pipermail/python-dev/2018-July/154554.html | [Python-Dev] Naming comprehension syntax [was Re: Informal educator feedback on PEP 572 ...]
https://github.com/python/cpython/pull/8122/files | WIP: use assignment expression in stdlib (combined PR) by vstinner · Pull Request #8122 · python/python
https://nedbatchelder.com/blog/201605/generator_comprehensions.html | Ned Batchelder: Generator comprehensions
https://twitter.com/squeaky_pl/status/1014855652362145792 | Squeaky on Twitter: "FYI @VictorStinner opened some pull requests to CPython for __demonstration purposes__ how PEP 572 assignment expression can be used to make Python library code more readable/shorter: https://t.co/Gc5IwdqwD1 https://t.co/IxkNMJvo9G https://t.co/eNPKiRgeI6… https://t.co/SjocXGITSS"
https://www.python.org/dev/peps/pep-0572/ | PEP 572 -- Assignment Expressions | Python.org

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

<!--
http://www2.ljworld.com/news/2018/jun/26/redesign-ljworld/ | A new and improved website; here are details on the redesign of LJWorld.com | News, Sports, Jobs - Lawrence Journal-World: news, information, headlines and events in Lawrence, Kansas
http://python-history.blogspot.com/2009/01/pythons-design-philosophy.html | The History of Python: Python's Design Philosophy
http://python-history.blogspot.com/2009/01/introduction-and-overview.html | The History of Python: Introduction and Overview
http://python-history.blogspot.com/2009/01/brief-timeline-of-python.html | The History of Python: A Brief Timeline of Python
https://mail.python.org/pipermail/python-list/1999-June/001951.html | "The Python Way"
-->

Python and Django BDFL
* [PEP 572 and decision-making in Python](https://lwn.net/Articles/757713)
* [Transfer of Power](https://mail.python.org/pipermail/python-committers/2018-July/005664.html)
* [Moratorium on Governance Decisions](https://mail.python.org/pipermail/python-committers/2018-July/005935.html)
* [Jacob Kaplan-Moss](https://jacobian.org/writing/retiring-as-bdfls)

Python Trends
* [Stack Overflow Post: the incredible growth of Python](https://stackoverflow.blog/2017/09/06/incredible-growth-python)
* [Hackernoon: "Could Python’s Popularity Outperform JavaScript in the Next Five Years?"](https://hackernoon.com/could-pythons-popularity-outperform-javascript-in-the-next-five-years-abed4e307224)

<!--
https://github.com/python/python-dev-survey | python/python-dev-survey: Place for gathering feedback from the public on the Python Developers Survey
https://surveys.jetbrains.com/s3/c12-python-developers-survey-2018 | Python developers survey 2018
https://www.jetbrains.com/research/devecosystem-2018/python/
https://www.jetbrains.com/research/python-developers-survey-2017/ | Python Developers Survey 2017 - Results
-->

Python 2 or 3
* [Python 2 or 3](https://wiki.python.org/moin/Python2orPython3)

<!--
https://www.djangopackages.com/python3/
http://python-future.org/ | Easy, clean, reliable Python 2/3 compatibility — Python-Future documentation
-->

Python 2 End of Life (EOL)
* [Python 2 End of Life (EOL) Python Developer email](https://mail.python.org/pipermail/python-dev/2018-March/152348.html)

Python 2 EOL Websites
* [Guido van Rossum: "Cool sites about the Python 3 transition"](https://twitter.com/gvanrossum/status/1012462042094002176)
* [Python Clock](https://pythonclock.org)
* [Python 3 Statement](http://python3statement.org)
* [Python 3 Readiness](https://py3readiness.org)
* [Python 3 Wall of Superpowers](https://python3wos.appspot.com)

<!--
http://python3porting.com/ | Welcome! — Supporting Python 3: An in-depth guide

Dropping Support
https://twitter.com/pganssle/status/978256523909623809 | Paul Ganssle on Twitter: "For any #python folks who may use python-dateutil in your projects, I'm working out the schedule for dropping Python 2.7 support now. The issue for discussion is here: https://t.co/sWRIhe85qp RT appreciated for visibility (don't want anyone blindsided)"
https://github.com/dateutil/dateutil/issues/653 | Python 2 deprecation schedule · Issue #653 · dateutil/dateutil
-->

High Profile/Performance Python Use
* [Dropbox](https://blogs.dropbox.com)
* Google
* [Instagram](https://engineering.instagram.com)
* Netflix
* Quora
* Reddit
* Spotify
* Uber

<!--
https://realpython.com/world-class-companies-using-python/
https://zapier.com

Python 3 at Facebook 
https://lwn.net/Articles/758159/
https://www.youtube.com/watch?v=H4SS9yVWJYA

https://blogs.dropbox.com/tech/2018/09/how-we-rolled-out-one-of-the-largest-python-3-migrations-ever/ | How we rolled out one of the largest Python 3 migrations ever | Dropbox Tech Blog
-->

Python Authorities
* [Python Packaging Authority (PyPA)](https://pypa.io) and [Python Packaging Authority GitHub](https://github.com/pypa) 
* [Python Authority Authority (PyAA) GitHub](https://github.com/pyaa)
* [Python Code Quality Authority (PyCQA) GitHub](https://github.com/PyCQA) and [Python Code Quality Authority (PyCQA) GitLab](https://gitlab.com/groups/pycqa)
* [Python Cryptographic Authority (PyCA) GitHub](https://github.com/pyca)

PEP Template
* [PEP 12 -- Sample reStructuredText PEP Template](https://www.python.org/dev/peps/pep-0012)

CPython Contributing
* [CPython GitHub](https://github.com/python/cpython)
* [Bugs](http://bugs.python.org)
* [CPython Dev Guide](https://devguide.python.org), [Alternate URL: CPython Dev Guide Read the Docs](http://cpython-devguide.readthedocs.io), and [CPython Dev Guide GitHub](https://github.com/python/devguide)
* [How to Become a Core Developer — Python Developer's Guide](https://devguide.python.org/coredev)

<!--
https://devguide.python.org/help/#office-hour | 2. Where to Get Help — Python Developer's Guide

http://devdocs.io/python~3.6/ | DevDocs — Python 3.6 documentation

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
* [Python Status](https://status.python.org)
* [Python Status History](https://status.python.org/history)

<!--
https://travis-ci.org/python/cpython/
-->

Release
* [PEP 537 -- Python 3.7 Release Schedule](https://www.python.org/dev/peps/pep-0537)
* [PEP 429 -- Python 3.4 Release Schedule](https://www.python.org/dev/peps/pep-0429)
* [PEP 373 -- Python 2.7 Release Schedule](https://www.python.org/dev/peps/pep-0373)

<!--
Python Release Managers
https://mail.python.org/pipermail/python-dev/2018-January/151949.html | [Python-Dev] Welcome the 3.8 and 3.9 Release Manager - Łukasz Langa!
-->

Python Performance

<!--
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

<!--
https://bugs.python.org/issue34605 | Issue 34605: Avoid master/slave terminology - Python tracker
https://github.com/python/cpython/pull/9101 | bpo-34605: Avoid master/slave terms by vstinner · Pull Request #9101 · python/cpython

https://wiki.python.org/moin/EuroPython2018/CPython | EuroPython2018/CPython - Python Wiki
https://twitter.com/europython/status/1019172899654119424 | EuroPython on Twitter: "Want to run a sprint at EuroPython 2018 

https://lwn.net/Articles/757950/ | Mentoring and diversity for Python [LWN.net]

https://lwn.net/Articles/754152/ | The 2018 Python Language Summit [LWN.net]

https://mariatta.ca/core-sprint-2018-part-1.html | mariatta.ca – Python Core Sprint 2018: Part One
https://mariatta.ca/core-sprint-2018-part-2.html | mariatta.ca – Python Core Sprint 2018: Part Two

https://twitter.com/VictorStinner/status/1041219533439217665 | Victor Stinner 🐍 on Twitter: "The 3rd CPython sprint at Microsoft was amazing! Many interesting talks in parallel, a lot about the new governance obviously. It is always a great pleasure to see my friends 🤗 I even heard something saying that core developers are a family 😍 Oh and we got 2 new core devs!… https://t.co/IxzLSwhyU3"

https://lwn.net/Articles/754779/ | Using GitHub Issues for Python [LWN.net]

http://lukasz.langa.pl/12/diversity-python-sprint-september/ | RE: Diversity on the Python sprint in September - lukasz.langa.pl

https://wirtel.be/post/2018/10/19/2018-october-week40-contributions-to-cpython/ | October - Week 40: Contributions to CPython · Stephane Wirtel
-->

Core Workflow Tools
* [Core Workflow Tools GitHub](https://github.com/python/core-workflow)
* [cherry_picker](https://github.com/python/core-workflow/tree/master/cherry_picker) and [cherry picker PyPi](https://pypi.org/project/cherry-picker)
* [miss-islington](https://github.com/python/miss-islington)
* [Python Buildbot](https://www.python.org/dev/buildbot) and [Python Buildbot Wiki](https://wiki.python.org/moin/BuildBot)

<!--
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

Python- Packages/Libraries
* [Pre-Production Deployment of Warehouse](https://pypi.org), [Warehouse GitHub](https://github.com/pypa/warehouse), and [Warehouse Read the Docs](https://warehouse.readthedocs.io)
* [PyPi Python Package Index PyPi](https://pypi.python.org/pypi)  

<!--
New
https://morepypy.blogspot.com/2018/09/the-first-15-years-of-pypy.html | PyPy Status Blog: The First 15 Years of PyPy — a Personal Retrospective
https://twitter.com/ewa_jodlowska/status/1034546348006277121 | Ewa Jodlowska on Twitter: "“PyPI’s new design is a reflection of the Python community - modern, welcoming and inclusive.”… "
https://www.youtube.com/watch?time_continue=1&v=QgZ7qv4Cd0Y | How To Publish A Package On PyPI - YouTube
https://www.google.com/search?q=pyproject.toml&oq=pyproject.toml&aqs=chrome..69i57j69i61j0l4.2199j0j7&sourceid=chrome&ie=UTF-8 | pyproject.toml - Google Search


https://packaging.python.org/guides/making-a-pypi-friendly-readme/ | Making a PyPI-friendly README — Python Packaging User Guide
https://www.python.org/dev/peps/pep-0438/ | PEP 438 -- Transitioning to release-file hosting on PyPI | Python.org
https://www.python.org/dev/peps/pep-0427/ | PEP 427 -- The Wheel Binary Package Format 1.0 | Python.org
https://packaging.python.org/ | Python Packaging User Guide — Python Packaging User Guide
https://github.com/pypa/sampleproject | pypa/sampleproject: A sample project that exists for PyPUG's "Tutorial on Packaging and Distributing Projects"
https://www.pyinstaller.org/ | Welcome to PyInstaller official website — PyInstaller
https://github.com/pypa/pipfile | pypa/pipfile
https://www.python.org/dev/peps/pep-0517/
https://www.python.org/dev/peps/pep-0518/
https://github.com/pypa/warehouse | pypa/warehouse: The Python Package Repository
https://github.com/pypa/packaging-problems/issues | Issues · pypa/packaging-problems
https://www.python.org/dev/peps/pep-0440/ | PEP 440 -- Version Identification and Dependency Specification | Python.org
https://pip.pypa.io/en/stable/reference/pip_install/#editable-installs | pip install — pip 18.1 documentation
-->

<!--
https://lwn.net/Articles/751458/ | A new package index for Python [LWN.net]

https://github.com/pypa/pipfile/issues/27
https://www.python.org/dev/peps/pep-0517/

https://dustingram.com/talks/2018/10/23/inside-the-cheeseshop | Inside the Cheeseshop: How Python Packaging Works - Dustin Ingram
Inside the Cheeseshop: How Python Packaging Works
PyCon 2018 · Dustin Ingram
https://www.youtube.com/watch?v=AQsZsgJ30AE
https://dustingram.com/articles/2018/04/16/pypi-is-dead-long-live-pypi | PyPI is dead. Long live PyPI! - Dustin Ingram
https://wiki.python.org/moin/CheeseShop | CheeseShop - Python Wiki

https://warehouse.readthedocs.io/development/getting-started/#quickstart-for-developers-with-docker-experience | Getting started — Warehouse 15.0.dev0 documentation

https://github.com/pypa/warehouse
https://github.com/pypa/warehouse/issues
https://twitter.com/pypi_updates2 | PyPI Recent Updates (@pypi_updates2) | Twitter

http://pyfound.blogspot.com/2018/08/redesigning-python-package-index.html
http://pyfound.blogspot.com/2018/03/warehouse-all-new-pypi-is-now-in-beta.html#livechat | Python Software Foundation News: Warehouse: All New PyPI is now in beta
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

Mailing List and Permissions History
* [Python Core Workflow Mailing List](https://mail.python.org/mailman/listinfo/core-workflow)
* [Permissions History](https://devguide.python.org/developers/#permissions-history)
* [Developer Log](https://github.com/python/devguide/blob/bbd38631554165a64e187bd29815125098159a13/developers.rst)

<!--
https://mail.python.org/mailman/listinfo/psf-community | PSF-Community Info Page
-->

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
* [Django Internals](https://docs.djangoproject.com/en/dev/internals)
* [Django Contributing](https://docs.djangoproject.com/en/dev/internals/contributing)
* [Tickets](https://code.djangoproject.com/query)
* [Life of a Django Ticket](https://docs.google.com/presentation/d/1Ao0S3Z-VRn_pcT5T4mXIhv3t3liQ3ZrwqaGeDqz9XCQ/edit)

Django, Releases, Announcements, and Roadmaps
* [Django Releases](https://docs.djangoproject.com/en/stable/releases)
* [Django Announcements](https://groups.google.com/forum/#!forum/django-announce)
* [Django 2.0 Release Notes](https://docs.djangoproject.com/en/2.0/releases/2.0) and [Django 2.0 Blog Post](https://www.djangoproject.com/weblog/2017/dec/02/django-20-released)
* [Django 2.1 Roadmap](https://code.djangoproject.com/wiki/Version2.1Roadmap) 
* [DEPS (Django Enhancement Proposals) GitHub](https://github.com/django/deps)

<!--
http://www2.ljworld.com/news/2015/jul/09/happy-birthday-django/

https://docs.djangoproject.com/en/dev/faq/general/#why-does-this-project-exist | FAQ: General | Django documentation | Django

https://www.djangoproject.com/weblog/2015/jun/25/roadmap/ | Django's Roadmap | Weblog | Django

https://docs.djangoproject.com/en/2.0/internals/release-process/#internal-release-cadence | Django’s release process | Django documentation | Django

https://docs.djangoproject.com/en/dev/internals/organization/ | Organization of the Django Project | Django documentation | Django
https://docs.djangoproject.com/en/dev/internals/contributing/bugs-and-features/#reporting-bugs | Reporting bugs and requesting features | Django documentation | Django

https://www.djangoproject.com/foundation/teams/ | Django Software Foundation | Django
-->

Your Framework Needs You
* [Carlton Gibson: Your Framework Needs You](https://2018.djangocon.us/talk/your-web-framework-needs-you)

<!--
https://www.youtube.com/watch?v=TrAFQW7Wza0&t=356s
https://2018.djangocon.us/talk/state-of-django-panel
State of Django
https://www.slideshare.net/jacobian/state-of-django/36-ORM_aggregationhttpdocsdjangoprojectcomendevtopicsdbaggregation | 
-->

Dissolving Django Core
* [On the Django core team - Google Groups](https://groups.google.com/forum/#!topic/dsf-members/GWOzvsOAGUs)
* [Draft proposal: dissolving "Django core" - Google Groups](https://groups.google.com/forum/#!topic/dsf-members/yqnWGII63mI)
* [Django DEP: Add draft DEP dissolving Django core. by ubernostrum](https://github.com/django/deps/pull/47)
* [Rough draft Django DEP: Dissolving Django Core](https://github.com/ubernostrum/deps/blob/draft-dissolve-core/draft/XXXX-dissolve-core.rst)

Mentorship
* [Django Core Mentorship Mailing List](https://docs.djangoproject.com/en/dev/internals/mailing-lists/#django-core-mentorship)

Django Developers Mailing Lists, Forum and Slack
* [Django Mailing Lists](https://docs.djangoproject.com/en/dev/internals/mailing-lists)
* [Django Google Developers Forum](https://groups.google.com/forum/#!forum/django-developers) 
* [Django Developers Slack](https://django-developers.herokuapp.com)

Django People
* [Django Original Team List](https://www.djangoproject.com/foundation/teams/#original-team-list)
* [Django Core Developers (Old Version)](https://docs.djangoproject.com/en/1.7/internals/committers/#core-developers)
* [Django Organization Repo People](https://github.com/orgs/django/people)

<!--
https://docs.djangoproject.com/en/dev/internals/organization/

https://www.djangoproject.com/foundation/committees/ | Django Software Foundation Committees | Django
-->

Django Code of Conduct and CLA
* [Django Code of Conduct](https://www.djangoproject.com/conduct)
* [Django Contributor License Agreements](https://www.djangoproject.com/foundation/cla)
