# Python and Django- Contributing

<!--
https://lwn.net/ | Welcome to LWN.net [LWN.net]

http://python-notes.curiousefficiency.org

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

https://www.amazon.com/Guido%20Van%20Rossum/e/B0034OPA4K/ref=la_B0034OPA4K_st?rh=n%3A283155%2Cp_82%3AB0034OPA4K&qid=1505705520&sort=date-desc-rank | Amazon.com: Guido Van Rossum: Books, Biography, Blog, Audiobooks, Kindle


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

## My Learning Priorities

* Python and Django contributing
* Packaging
* Mariatta's talks and workshops

## Python General

Python
* [Python Front Page](https://wiki.python.org/moin)
* [Python GitHub](https://github.com/python)

<!--
http://pyfound.blogspot.com/ | Python Software Foundation News
https://pythoninsider.blogspot.com/ | Python Insider: Python 3.7.2rc1 and 3.6.8rc1 now available for testing

https://docs.python.org/3/about.html | About these documents — Python 3.6.5 documentation
-->

Python History
* [The History of Python](http://python-history.blogspot.com)
* [Guido van Rossum: BDFL Python 3 retrospective, PyCascades 2018](https://www.youtube.com/watch?v=Oiw23yfqQy8)
* [Foreword for "Programming Python" (1st ed.)](https://www.python.org/doc/essays/foreword) in which Guido van Rossum explains how and why Python came into existence.
* ["The Python Way"](https://mail.python.org/pipermail/python-list/1999-June/001951.html)

<!--
http://bdfl-gift.pspython.com/ | PuPPy Annual Benefit

http://python-history.blogspot.com/2009/01/pythons-design-philosophy.html | The History of Python: Python's Design Philosophy
http://python-history.blogspot.com/2009/01/introduction-and-overview.html | The History of Python: Introduction and Overview
http://python-history.blogspot.com/2009/01/brief-timeline-of-python.html | The History of Python: A Brief Timeline of Python

https://twitter.com/jakevdp/status/956894158312030210 | Jake VanderPlas on Twitter: "On this day in 1994, Python version 1.0 was released! And today, you can try it yourself using conda: $ conda create -n py1env python=1.0 $ conda activate py1env $ python… https://t.co/wcFP2KDtJ4"
https://groups.google.com/forum/#!msg/comp.lang.python/mvSmZ3sLgKY/vFGVCVPf_SwJ;context-place=msg/comp.lang.python/mvSmZ3sLgKY/vFGVCVPf_SwJ | Python 1.5.2 beta 1 released - Google Groups
-->

## Python Trends and Surveys

Python Trends
* [Stack Overflow Post: the incredible growth of Python](https://stackoverflow.blog/2017/09/06/incredible-growth-python)
* [Hackernoon: "Could Python’s Popularity Outperform JavaScript in the Next Five Years?"](https://hackernoon.com/could-pythons-popularity-outperform-javascript-in-the-next-five-years-abed4e307224)

Python Rust/WebAssembly
* [Rust-Python GitHub](https://github.com/RustPython/RustPython) and [Rust Python Demo](https://rustpython.github.io/demo)
* [PyBee Ouroboros GitHub](https://github.com/pybee/ouroboros)
* [Łukasz Langa Twitter Thread](https://twitter.com/llanga/status/1091974732017266688)
* [My Tweet](https://twitter.com/KatiMichel/status/1092140998325497856)
* [Jeff's Tweet](https://twitter.com/webology/status/1092147352813613057)

Survey Results
* [JetBrains 2018 Python Developers Survey Results](https://www.jetbrains.com/research/python-developers-survey-2018)

<!--
* [JetBrains Python Developers Survey (2018)](https://www.jetbrains.com/research/devecosystem-2018/python) and [JetBrains Python Developers Survey (2018) GitHub](https://github.com/python/python-dev-survey)
* [JetBrains PPython Developers Survey (2017)](https://www.jetbrains.com/research/python-developers-survey-2017)
-->

## Python 2 or 3, Python 2 EoL

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

## Python Governance

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

Python and Django Governance and BDFL
* [PEP 8016- The Steering Council Model (Accepted)](https://www.python.org/dev/peps/pep-8016)
* [PEP 8016- The Steering Council Model (Runner Up)](https://www.python.org/dev/peps/pep-8012)
* [Python Governance Vote (December 2018)](https://discuss.python.org/t/python-governance-vote-december-2018-results/546)
* [PEP 8010- The Technical Leader Governance Model (Rejected)](https://www.python.org/dev/peps/pep-8010)
* [PEP 572 and decision-making in Python](https://lwn.net/Articles/757713)
* [Transfer of Power](https://mail.python.org/pipermail/python-committers/2018-July/005664.html)
* [Moratorium on Governance Decisions](https://mail.python.org/pipermail/python-committers/2018-July/005935.html)
* [Jacob Kaplan-Moss](https://jacobian.org/writing/retiring-as-bdfls)

<!--
https://www.europython-society.org/post/182445627020/announcing-the-guido-van-rossum-core-developer | EuroPython Society — Announcing the Guido van Rossum Core Developer...

https://github.com/python/steering-council | python/steering-council: Communications from the Steering Council
 
https://discuss.python.org/t/2019-steering-council-election-results/824 | 2019 Steering Council Election Results - Committers - Discussions on Python.org
https://mail.python.org/pipermail/python-committers/2019-February/006520.html | [python-committers] 2019 Steering Council Election Results
https://twitter.com/ThePSF/status/1092452576266801152 | Python Software on Twitter: "The Python Core Developers have elected their first Steering Council! @pumpichank, @brettsky, @WillingCarol, @gvanrossum, and @ncoghlan_dev will lead the project under the specifications in PEP 13. https://t.co/cN2wDLh5uH https://t.co/hCOahJQSWY"

PEP 8100 -- January 2019 steering council election
https://www.python.org/dev/peps/pep-8100/
https://discuss.python.org/t/steering-council-nomination-mariatta/670

https://snarky.ca/an-update-on-pythons-governance
https://lwn.net/Articles/775105

https://twitter.com/llanga/status/1074704443222958081 | Łukasz Langa on Twitter: "The governance race is over. I am very happy to see PEP 8016 win and PEP 8012 take the second place. The two are complementary. 1/4"
https://twitter.com/brettsky/status/1074690504682426368 | Brett Cannon on Twitter: "PEP 8016 won, so next step is an election for council membership that will take 4 weeks to hold and needs a start date to be scheduled… https://t.co/W9tM3aGc2J"

https://twitter.com/aymericaugustin/status/1074751907195949056 | Aymeric Augustin on Twitter: ""Substantial text was copied shamelessly from The Django project's governance document." It looks like https://t.co/QN7JaoXdFI just became my biggest contribution to Python :-)… https://t.co/CsC0LoxMRz"

https://groups.google.com/forum/#!topic/django-developers/8b-wxEzWO3c/discussion
https://github.com/django/django/pull/2947 | Team organization by aaugustin · Pull Request #2947 · django/django
-->

## Python Summits and Sprints

The 2018 Python Language Summit
* [The 2018 Python Language Summit](https://lwn.net/Articles/754152)

Python Core Sprint 2018
* [Python Blog "CPython Core Developer Sprint 2018"](http://pyfound.blogspot.com/2018/09/cpython-core-developer-sprint-2018.html)
* [Mariatta: Part 1](https://mariatta.ca/core-sprint-2018-part-1.html) and [Mariatta: Part 2](https://mariatta.ca/core-sprint-2018-part-2.html)
* [Victor Stinner](https://twitter.com/VictorStinner/status/1041219533439217665)

Python Core Sprint 2016
* [Lukasz Langa: Diversity on the Python Sprint in September](http://lukasz.langa.pl/12/diversity-python-sprint-september)

<!--
http://pycon.blogspot.com/2016/05/how-to-get-ready-for-pycon-development.html

https://wirtel.be/post/2018/10/19/2018-october-week40-contributions-to-cpython/ | October - Week 40: Contributions to CPython · Stephane Wirtel
-->

Python Sprints
* [Python Sprints](https://python-sprints.github.io)

<!--
https://wiki.python.org/moin/EuroPython2018/CPython | EuroPython2018/CPython - Python Wiki
https://twitter.com/europython/status/1019172899654119424 | EuroPython on Twitter: "Want to run a sprint at EuroPython 2018 
-->

## Python Mailing Lists, Permissions, Mentors, Diversity

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
https://twitter.com/mariatta/status/1084526997466828800 | Mariatta 🤦 on Twitter: "I appreciate people reaching out and asking me how they can contribute to Python. Thank you for your interest and enthusiasm! This might sound like a "quick question" to you but I've answered this at #PyConUS2018, and it is 45 minutes long: https://t.co/r6eY0tDNTm (1/3)"

What is a Python Core Developer?
https://www.youtube.com/watch?v=xvft-_8djUI | Keynote - Mariatta Wijaya - YouTube
https://www.youtube.com/watch?v=hhj7eb6TrtI&feature=youtu.be | Mariatta Wijaya - What is a Python Core Developer? - PyCon 2018 - YouTube

http://emilyemorehouse.com/blog/015-my-path-to-becoming-a-python-core-developer/ | My Path to Becoming a Python Core Developer
https://realpython.com/interview-emily-morehouse/ | Python Community Interview With Emily Morehouse – Real Python

https://discuss.python.org/t/steering-council-nomination-emily-morehouse/686/18 | Steering Council nomination: Emily Morehouse - Users - Discussions on Python.org
https://twitter.com/emilyemorehouse/status/1086682866094723078 | Emily Morehouse-Valcarcel on Twitter: "In a sadly unsurprising turn of events, an anonymous user account appeared to challenge my nomination and credentials, suggesting three males to replace me. Friendly reminder that it’s not easy being a woman in tech, and these things happen all the time. https://t.co/8YIe1WDqTF"

Mentoring
https://twitter.com/gvanrossum/status/1072535194131984386 | Guido van Rossum on Twitter: "All the time! Just now I had to look up how re.split() works with optional capturing groups in the regex.… "
https://twitter.com/jacobian/status/737441987587018752 | jacobian on Twitter: "@laceynwilliams @adriennefriend I've literally given up on ideas because I couldn't figure out how to get my dev env together."

Mentorship
https://mail.python.org/pipermail/python-committers/2018-May/005389.html | [python-committers] Proposing Mark Shannon to be a core developer
-->

Python Master/Slave Terminology
* [PR "Avoid master/slave terminology"](https://github.com/python/cpython/pull/9101)
* [Python Bug Tracker: "Avoid master/slave terminology"](https://bugs.python.org/issue34605)

## Python and Django Contributing Docs

CPython Contributing Guides
* [CPython Dev Guide](https://devguide.python.org), [Alternate URL: CPython Dev Guide Read the Docs](http://cpython-devguide.readthedocs.io), and [CPython Dev Guide GitHub](https://github.com/python/devguide)
* [How to Become a Core Developer- Python Developer's Guide](https://devguide.python.org/coredev)

Internals
* [Python Tutor](http://pythontutor.com)

Python Internals- Philip Guo
* [Philip Guo- CPython Internals](http://pgbovine.net/cpython-internals.htm) and [Philip Guo- CPython Internals YouTube](https://www.youtube.com/user/pgbovine/playlists)
* [Philip Guo- CPython Internals Course Website](http://courses.pgbovine.net/csc253)

Python Internals- General
* [Python’s Innards: Introduction](https://tech.blog.aknin.name/2010/04/02/pythons-innards-introduction) and [Python’s Innards: For My Wife](https://tech.blog.aknin.name/2010/07/04/pythons-innards-for-my-wife)

Method Resolution Order
* [C3 Linearization Wikipedia](https://en.wikipedia.org/wiki/C3_linearization)
* [The Python 2.3 Method Resolution Order](https://www.python.org/download/releases/2.3/mro)

Django and Python Contributing
* [Django Internals](https://docs.djangoproject.com/en/dev/internals)
* [Django Contributing](https://docs.djangoproject.com/en/dev/internals/contributing)

Django GitHub
* [Django GitHub](https://github.com/django/django)

<!--
https://developers.google.com/season-of-docs/terms/program-rules | Season of Docs 2019 Program Rules  |  Season of Docs  |  Google Developers
https://developers.google.com/season-of-docs/ | Season of Docs  |  Google Developers

https://groups.google.com/forum/#!forum/django-core-mentorship | (99+) Django Core Mentorship – Google Groups
-->

<!--
https://cpython-devguide.readthedocs.io/setup/#directory-structure
https://cpython-devguide.readthedocs.io/compiler/
https://cpython-devguide.readthedocs.io/en/latest/setup/#directory-structure

https://devguide.python.org/
https://pythondev.readthedocs.io/ (my most complete website)
https://pythondev.readthedocs.io/internals.html
https://cpython-core-tutorial.readthedocs.io/en/latest/ (my draft tutorial)

Very Important!!!!!
https://github.com/pyladies/pyladies-maintainers/issues/6 | Guided tour to the CPython source code · Issue #6 · pyladies/pyladies-maintainers

https://paper.dropbox.com/doc/Yet-another-guided-tour-of-CPython--AawmKdby8hJiAxFThbSAoJQfAg-XY7KgFGn88zMNivGJ4Jzv
https://paper.dropbox.com/doc/Yet-another-guided-tour-of-CPython-XY7KgFGn88zMNivGJ4Jzv
https://paper.dropbox.com/doc/CPython-Guide-m7BQyPth6AIDUdZ6EmBNM
https://paper.dropbox.com/doc/CPython-Guide--AX4Yimx33KaO7d4kBD7VIGVvAg-m7BQyPth6AIDUdZ6EmBNM

https://github.com/emilyemorehouse/cpython-notes
https://python.zulipchat.com/login/
https://mail.python.org/mailman3/lists/core-mentorship.python.org/
https://github.com/mitmproxy/mitmproxy/issues/1381
https://speakerdeck.com/matrixise/exploring-our-python-interpreter
https://mail.python.org/mailman/private/core-mentorship/2015-November/003274.html
https://twitter.com/jacobian/status/737441987587018752

http://python-history.blogspot.com/. A few highlights:
http://python-history.blogspot.com/2013/11/the-history-of-bool-true-and-false.html
http://python-history.blogspot.com/2013/11/story-of-none-true-false.html
http://python-history.blogspot.com/2010/06/method-resolution-order.html
http://python-history.blogspot.com/2010/06/inside-story-on-new-style-classes.html
http://python-history.blogspot.com/2009/04/metaclasses-and-extension-classes-aka.html
http://python-history.blogspot.com/2009/03/dynamically-loaded-modules.html

https://github.com/willingc/pyladies-cpython/blob/master/Notes%20on%20Lecture%201.ipynb
http://aosabook.org/en/500L/a-python-interpreter-written-in-python.html
http://opensourcebridge.org/sessions/1882
http://opensourcebridge.org/sessions/1881
https://github.com/larryhastings/gilectomy
https://en.wikipedia.org/wiki/Open_addressing
https://en.wikipedia.org/wiki/C_dynamic_memory_allocation
https://en.wikipedia.org/wiki/Locality_of_reference
https://docs.python.org/3.5//c-api/index.html


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

## Python Release and Workflow

CPython Repo and Bugs Dashboard
* [CPython GitHub](https://github.com/python/cpython)
* [Bugs](http://bugs.python.org)

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

Core Workflow Tools
* [Core Workflow Tools GitHub](https://github.com/python/core-workflow)
* [cherry_picker](https://github.com/python/core-workflow/tree/master/cherry_picker) and [cherry picker PyPi](https://pypi.org/project/cherry-picker)
* [miss-islington](https://github.com/python/miss-islington)
* [Python Buildbot](https://www.python.org/dev/buildbot) and [Python Buildbot Wiki](https://wiki.python.org/moin/BuildBot)

Issues PEP
* [PEP 581 -- Using GitHub Issues for CPython](https://www.python.org/dev/peps/pep-0581)
* [LWN: "Using GitHub Issues for Python"](https://lwn.net/Articles/754779)

<!--
Workshops

Mariatta- F-Strings

https://speakerdeck.com/mariatta/f-strings | F-strings - Speaker Deck
https://www.pydanny.com/python-f-strings-are-fun.html | Python F-Strings Are Fun!

https://twitter.com/beeenje/status/1032725285467312129 | Benjamin Bertrand on Twitter: "I really liked @mariatta Build-a-GitHub-Bot Workshop from #PyCon2018. So I decided to build a clone of gidgethub from @brettsky for @gitlab: https://t.co/qnjitIKR7X Thanks to both of you for the tutorial and library!"

Mariatta- Bots
* [Mariatta's Build-a-GitHub-Bot Workshop](https://github-bot-tutorial.readthedocs.io/en/latest)

https://github-bot-tutorial.readthedocs.io/en/latest/hall-of-fame.html | Hall of Fame: Bots By Students — github-bot-tutorial documentation
https://speakerdeck.com/mariatta/dont-be-a-robot-build-the-bot | Don't Be a Robot; Build the Bot - Speaker Deck
https://www.slideshare.net/MariattaWijaya/automating-github-workflow-with-bots | Automating GitHub Workflow with Bots
-->

<!--
https://github.com/Mariatta/cookiecutter_sprint_guide
https://github.com/Mariatta/pep_cookiecutter

https://mariatta.ca/
https://realpython.com/interview-mariatta-wijaya/ | Python Community Interview With Mariatta Wijaya – Real Python

https://mariatta.ca/weekly-update-feb-16-2019.html | mariatta.ca – Weekly Update, Feb 16, 2019

https://www.slideshare.net/MariattaWijaya | Mariatta Wijaya, Flawed & disordered at Platform engineer | SlideShare

https://github.com/Mariatta/gh_app_demo | Mariatta/gh_app_demo: GitHub App demo, with gidgethub, aiohttp, and Python 3.7

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

## Python and Django Git Assistance

Python and Django Git Bootcamps and Cheat Sheets
* [Python: Git Bootcamp and Cheat Sheet](https://docs.python.org/devguide/gitbootcamp.html)
* [Django: Working with Git and GitHub](https://docs.djangoproject.com/en/1.8/internals/contributing/writing-code/working-with-git)

## Python and Django Packages

Django
* [Django: How to write reusable apps](https://docs.djangoproject.com/en/2.0/intro/reusable-apps).

Python Docs- Packaging
* [Distributing Python Modules](https://docs.python.org/3/distributing/index.html)

Python- Official Packaging Info
* [Sample Project](https://github.com/pypa/sampleproject)
* [Python Packaging User Guide](https://packaging.python.org) and [Python Packaging User Guide GitHub](https://github.com/pypa/python-packaging-user-guide) 
* [Python Packaging Tutorials](https://packaging.python.org/tutorials) 
* [Python Packaging Guides](https://packaging.python.org/guides) 
* [Python Packaging Projects Tutorial](https://packaging.python.org/tutorials/packaging-projects)  
* [Python Packaging Key Projects](https://packaging.python.org/key_projects)

Python- Wheel (versus Egg!)
* [Python Packaging Wheel vs. Egg](http://python-packaging-user-guide.readthedocs.io/discussions/wheel-vs-egg)
* [Wheel PyPi](https://pypi.org/project/wheel) and [Wheel Read the Docs](http://wheel.readthedocs.org)
* [Python Wheels](http://pythonwheels.com)

Package Helpers
* [Twine GitHub](https://github.com/pypa/twine) and [Twine PyPi](https://pypi.python.org/pypi/twine)

Python- Packages/Libraries
* [Warehouse](https://pypi.org), [Warehouse GitHub](https://github.com/pypa/warehouse), and [Warehouse Read the Docs](https://warehouse.readthedocs.io)
 
Core Packaging Utilities
* [PyPa Core Packaging Utilities](https://github.com/pypa/packaging)  
* [PyPa Core Packaging Utilities Documents](https://packaging.pypa.io) 

Vinta Django Apps Checklist
* [Vinta Django Apps Checklist](http://djangoappschecklist.com)

Vinta API Checklist
* [Vinta API Checklist](http://python.apichecklist.com) and [Vinta API Checklist GitHub](https://github.com/vintasoftware/python-api-checklist)

<!--
Python and Django- Contributing- Packaging

DjangoCon Europe 2017 Vinta
https://www.youtube.com/watch?v=AMg4Iind90Q | (1) "Qualities of great reusable Django apps" by Flávio Juvenal da Silva Junior - YouTube
https://docs.google.com/presentation/d/1yapK1hYt8f64ztLCc7yFpCI4RG1vTMLhqwZ6cUBZIvI/edit#slide=id.p | Qualities of great reusable Django apps - DjangoCon Europe 2017 - Google Slides
https://www.vinta.com.br/blog/2017/djangocon-europe-2017-was-awesome/ | DjangoCon Europe 2017 was awesome! – Vinta Software

https://pip.pypa.io/en/stable/reference/pip_wheel

https://wiki.python.org/moin/CheeseShop | CheeseShop - Python Wiki

https://wiki.python.org/moin/Distutils | Distutils - Python Wiki

https://test.pypi.org/ | TestPyPI – the Python Package Index · TestPyPI
https://packaging.python.org/guides/using-testpypi/ | Using TestPyPI — Python Packaging User Guide

https://docs.python.org/3/distutils/introduction.html | 1. An Introduction to Distutils — Python 3.6.4rc1 documentation
https://docs.python.org/3/distutils/setupscript.html | 2. Writing the Setup Script — Python 3.6.4rc1 documentation
https://docs.python.org/3.1/distutils/uploading.html | 7. Uploading Packages to the Package Index — Python v3.1.5 documentation
https://docs.python.org/3.6/distutils/packageindex.html#package-index | 6. The Python Package Index (PyPI) — Python 3.6.4rc1 documentation
https://docs.python.org/3/distutils/sourcedist.html | 4. Creating a Source Distribution — Python 3.6.4rc1 documentation

https://www.python.org/dev/peps/pep-0566/ | PEP 566 -- Metadata for Python Software Packages 2.1 | Python.org
https://www.python.org/dev/peps/pep-0518/ | PEP 518 -- Specifying Minimum Build System Requirements for Python Projects | Python.org
https://www.python.org/dev/peps/pep-0496/ | PEP 496 -- Environment Markers | Python.org
https://www.python.org/dev/peps/pep-0508/#id23 | PEP 508 -- Dependency specification for Python Software Packages | Python.org

https://www.python.org/dev/peps/pep-0427/ | PEP 427 -- The Wheel Binary Package Format 1.0 | Python.org
https://www.python.org/dev/peps/pep-0438/ | PEP 438 -- Transitioning to release-file hosting on PyPI | Python.org
https://www.python.org/dev/peps/pep-0440/ | PEP 440 -- Version Identification and Dependency Specification | Python.org
https://www.python.org/dev/peps/pep-0517/

https://packaging.python.org/glossary/ | Glossary — Python Packaging User Guide
https://packaging.python.org/guides/distributing-packages-using-setuptools/ | Packaging and distributing projects — Python Packaging User Guide
https://packaging.python.org/key_projects/#setuptools | Project Summaries — Python Packaging User Guide
https://packaging.python.org/key_projects/#wheel | Project Summaries — Python Packaging User Guide
https://setuptools.readthedocs.io/en/latest/setuptools.html | Building and Distributing Packages with Setuptools — setuptools 39.2.0 documentation

https://packaging.python.org/tutorials/installing-packages/
https://packaging.python.org/tutorials/distributing-packages/ | Packaging and distributing projects
https://packaging.python.org/tutorials/distributing-packages/#project-urls

https://docs.python-guide.org/shipping/packaging/ | Packaging Your Code — The Hitchhiker's Guide to Python
https://docs.python-guide.org/shipping/freezing/#freezing-your-code-ref | Freezing Your Code — The Hitchhiker's Guide to Python

https://www.youtube.com/watch?v=AQsZsgJ30AE

https://www.youtube.com/watch?v=EdD6Ifjlle4 | DjangoCon US 2018 - Packaging Django Apps for Distribution on PyPI by Laura Hampton - YouTube

https://www.youtube.com/watch?time_continue=1&v=QgZ7qv4Cd0Y | How To Publish A Package On PyPI - YouTube

https://packaging.python.org/guides/making-a-pypi-friendly-readme/ | Making a PyPI-friendly README — Python Packaging User Guide

Tools
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

https://pyup.io/ | Manage your Python dependencies with pyup.io
https://docs.travis-ci.com/user/deployment/pypi/ | PyPI deployment - Travis CI
http://www.pyinstaller.org/ | Welcome to PyInstaller official website — PyInstaller

https://github.com/pypa/warehouse/issues
https://github.com/pypa/packaging-problems/issues | Issues · pypa/packaging-problems

https://pip.pypa.io/en/stable/reference/pip_install/#editable-installs | pip install — pip 18.1 documentation

https://twitter.com/pypi_updates2 | PyPI Recent Updates (@pypi_updates2) | Twitter
-->

PyPi History
* ["Redesigning the Python Package Index"](http://pyfound.blogspot.com/2018/08/redesigning-python-package-index.html)
* ["A new package index for Python"](https://lwn.net/Articles/751458/)
* ["Warehouse: All New PyPI is now in beta"](http://pyfound.blogspot.com/2018/03/warehouse-all-new-pypi-is-now-in-beta.html)

Dustin Ingram
* ["Inside the Cheeseshop: How Python Packaging Works" (PyCon 2018)](https://dustingram.com/talks/2018/10/23/inside-the-cheeseshop)
* ["PyPI is dead. Long live PyPI!"](https://dustingram.com/articles/2018/04/16/pypi-is-dead-long-live-pypi)

Tutorials
* [The Sheer Joy of Packaging! Scipy 2018 Tutorial](https://python-packaging-tutorial.readthedocs.io/en/latest)

Python- Cookiecutter Creating Packages
* [PyPi Release Checklist](https://gist.github.com/audreyr/5990987) and [PyPi Release Checklist 2](https://gist.github.com/audreyr/9f1564ea049c14f682f4)
* [Cookiecutter Django Package GitHub](https://github.com/pydanny/cookiecutter-djangopackage)
* [Cookiecutter PyPackage Read the Docs](https://cookiecutter.readthedocs.org/en/latest)
* [Cookiecutter PyPackage GitHub](https://github.com/audreyr/cookiecutter-pypackage)
* [Cookiecutter via Django Rest Framework: How to create a Third Party Package](http://www.django-rest-framework.org/topics/third-party-resources)

Python- Additional Packaging Tutorials
* [Digital Ocean Tutorial "How to Package and Distribute Python Applications"](https://www.digitalocean.com/community/tutorials/how-to-package-and-distribute-python-applications) 
* [Free Code Camp "How to publish your own Python Package on PyPi"](https://medium.freecodecamp.org/how-to-publish-a-pyton-package-on-pypi-a89e9522ce24)

<!--
https://twitter.com/di_codes/status/1097217474603438080 | Dustin Ingram @ PyCaribbean on Twitter: "First you just have to understand all these things... 🤐… "

Tutorials
http://the-hitchhikers-guide-to-packaging.readthedocs.io/en/latest/contributing.html | Contribute Your Package to the World — The Hitchhiker's Guide to Packaging 1.0 documentation

https://pythonhosted.org/setuptools/formats.html
https://pythonhosted.org/an_example_pypi_project/setuptools.html

https://blog.jetbrains.com/pycharm/2017/05/how-to-publish-your-package-on-pypi/ | How to Publish Your Package on PyPI | PyCharm Blog
https://tom-christie.github.io/articles/pypi/ | Uploading to PyPI – Tom Christie

https://github.com/twoscoops/Creating-and-Distributing-Python-Packages | twoscoops/Creating-and-Distributing-Python-Packages
https://courses.twoscoopspress.com/courses/take/creating-and-distributing-python-packages | Two Scoops Press

New PyPI
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

## python.org Contributing

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

## Django

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

Django fellows
* [Mariusz Felisiak GitHub](https://github.com/felixxm)
* [Carlton Gibson GitHub](https://github.com/carltongibson)
* [Tim Graham GitHub](https://github.com/timgraham)

<!--
Carlton Gibson and William S. Vincent
https://djangochat.com/ | Django Chat Podcast
-->

Django Software
* [Django Reporting Bugs and Requesting Features](https://docs.djangoproject.com/en/dev/internals/contributing/bugs-and-features/#reporting-bugs)
* [Django Submitting a Patch](https://docs.djangoproject.com/en/dev/internals/contributing/writing-code/submitting-patches/)

djangoproject.com Contributing
* [djangoproject.com GitHub](https://github.com/django/djangoproject.com)
* [code.djangoproject.com](https://code.djangoproject.com)
* [dashboard.djangoproject.com](https://dashboard.djangoproject.com)

DEPS (Django Enhancement Proposals)
* [DEPS (Django Enhancement Proposals) GitHub](https://github.com/django/deps)

Django Tickets
* [Tickets](https://code.djangoproject.com/query)
* [Life of a Django Ticket](https://docs.google.com/presentation/d/1Ao0S3Z-VRn_pcT5T4mXIhv3t3liQ3ZrwqaGeDqz9XCQ/edit)

Release Cadence
* [Django Release Cadence](https://docs.djangoproject.com/en/dev/internals/release-process/#internal-release-cadence)

Django, Releases, Announcements, and Roadmaps
* [Django Releases](https://docs.djangoproject.com/en/stable/releases)
* [Django Announcements](https://groups.google.com/forum/#!forum/django-announce)
* [Django 2.1 Roadmap](https://code.djangoproject.com/wiki/Version2.1Roadmap) 
* [Django 2.1 Release Notes](https://docs.djangoproject.com/en/2.1/releases/2.1)
* [Django Roadmap to 2.0](https://www.djangoproject.com/weblog/2015/jun/25/roadmap) 

Your Framework Needs You
* [Carlton Gibson: Your Framework Needs You](https://2018.djangocon.us/talk/your-web-framework-needs-you)

<!--
https://2019.djangocon.eu/talks/feeding-the-pony-contributing-back-to-django-how-t/ | Feeding the Pony: Contributing back to Django & How to make that work for you • DjangoCon Europe 2019
-->

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
-->
