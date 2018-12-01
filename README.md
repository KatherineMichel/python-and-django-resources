# Python and Django- Contributing

<!--
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

Python and Django BDFL
* [PEP 572 and decision-making in Python](https://lwn.net/Articles/757713)
* [Transfer of Power](https://mail.python.org/pipermail/python-committers/2018-July/005664.html)
* [Moratorium on Governance Decisions](https://mail.python.org/pipermail/python-committers/2018-July/005935.html)
* [Jacob Kaplan-Moss](https://jacobian.org/writing/retiring-as-bdfls)

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

<!--
https://www.youtube.com/watch?v=AQsZsgJ30AE

New
https://www.youtube.com/watch?time_continue=1&v=QgZ7qv4Cd0Y | How To Publish A Package On PyPI - YouTube

https://packaging.python.org/guides/making-a-pypi-friendly-readme/ | Making a PyPI-friendly README — Python Packaging User Guide

https://www.python.org/dev/peps/pep-0427/ | PEP 427 -- The Wheel Binary Package Format 1.0 | Python.org
https://www.python.org/dev/peps/pep-0438/ | PEP 438 -- Transitioning to release-file hosting on PyPI | Python.org
https://www.python.org/dev/peps/pep-0440/ | PEP 440 -- Version Identification and Dependency Specification | Python.org
https://www.python.org/dev/peps/pep-0517/

https://www.pyinstaller.org/ | Welcome to PyInstaller official website — PyInstaller

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

Python and Django Git Bootcamps and Cheat Sheets
* [Python: Git Bootcamp and Cheat Sheet](https://docs.python.org/devguide/gitbootcamp.html)
* [Django: Working with Git and GitHub](https://docs.djangoproject.com/en/1.8/internals/contributing/writing-code/working-with-git)

Lawrence Journal World
* [Happy Birthday Django](http://www2.ljworld.com/news/2015/jul/09/happy-birthday-django)
* [LJWorld Redesign](http://www2.ljworld.com/news/2018/jun/26/redesign-ljworld)

State of Django
* [State of Django Panel (DjangoCon 2018)](https://2018.djangocon.us/talk/state-of-django-panel)
* [State of Django Panel Video (DjangoCon 2018)](https://www.youtube.com/watch?v=TrAFQW7Wza0&t=356s)
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

Django People- Current
* [Django Organization](https://docs.djangoproject.com/en/dev/internals/organization)
* [DSF Committees](https://www.djangoproject.com/foundation/committees)
* [Django Team List (Old?)](https://www.djangoproject.com/foundation/teams)

Django People- Historical
* [Django Core Developers (Old Version)](https://docs.djangoproject.com/en/1.7/internals/committers/#core-developers)
* [Django Organization Repo People](https://github.com/orgs/django/people)

Django Code of Conduct and CLA
* [Django Code of Conduct](https://www.djangoproject.com/conduct)
* [Django Contributor License Agreements](https://www.djangoproject.com/foundation/cla)
