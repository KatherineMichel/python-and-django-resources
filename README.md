# Python and Django- Contributing

<!--
https://twitter.com/cfactoid/status/1180599186913296384

My CPython Issue and Pull Requests
http://bugs.python.org/user26332

https://twitter.com/ncoghlan_dev/status/1164868943493791744 | Nick Coghlan on Twitter: "Current GitHub language stats for the main CPython repo: * Python 63.9% * C 28.9% * Objective-C 4.4% * C++ 1.2% * HTML 0.4% * M4 0.4% * Other 0.8% The autoconf scripts are large enough to make it onto the list :)" / Twitter

Notable Talks

Keynote: Python 2020 - Łukasz Langa - PyLondinium19
https://www.youtube.com/watch?v=KDXhu4rxTNY&t=2028s


https://twitter.com/brettsky/status/1154908949956554752


https://famicol.in/language_checklist.html | Programming Language Checklist
https://twitter.com/davecheney/status/1032519492641816576 | Dave Cheney on Twitter: "… "

https://medium.com/@Captain_Joannah/so-you-want-to-contribute-to-cpython-gather-here-5a2694148ca4 | So, You want to Contribute to Cpython : Gather here !!
https://medium.com/mergify/case-study-cpython-development-workflow-472ae5843188 | Case Study: CPython Development Workflow – mergify – Medium

https://github.com/pypa/gh-action-pypi-publish | pypa/gh-action-pypi-publish: GitHub Action to publish a package to PyPI

https://mail.python.org/pipermail/python-dev/2018-May/153296.html | [Python-Dev] Python startup time

http://rahmonov.me/posts/write-python-framework-part-one/ | How to write a Python web framework. Part I.	

Very important!!!!!!!
https://github.com/python-leap/book | python-leap/book: Pythonic Application Architecture Patterns, the Book
https://twitter.com/hjwp/status/1124403310721753088 | Harry Percival on Twitter: "@KatiMichel @brandon_rhodes new book - https://t.co/F9aJA1zWZH feedback high or low level much appreciated!"
-->

## Releases

<!--
Python Insider
https://blog.python.org
https://pythoninsider.blogspot.com/
https://discuss.python.org Discussions on Python.org
-->

General
* [Downloads](https://www.python.org/downloads)
* [What's New](https://docs.python.org/dev/whatsnew/)

By OS
* [The Microsoft Store Package](https://docs.python.org/3.7/using/windows.html#windows-store)
* ["Who put Python in the Windows 10 May 2019 Update?"](https://devblogs.microsoft.com/python/python-in-the-windows-10-may-2019-update/)
* ["Future versions of macOS won't include scripting language runtimes by default... "](https://developer.apple.com/documentation/macos_release_notes/macos_catalina_10_15_beta_5_release_notes)
* ["This is a huge step forward in #Python 3 adoption on Linux!"](https://twitter.com/hroncok/status/1147223223572058114)

<!--
https://twitter.com/raymondh/status/1136076427218964480 | Raymond Hettinger on Twitter: "#Python 3.8 news: The beta release out. Please download it and try out the new features: shared memory multiprocessing, walrus operator, positional-only notation ... Let us know if anything can be made better. But no complaints that it is too fast ;-) https://t.co/9mlvs0luFv"
https://realpython.com/python37-new-features/ | Cool New Features in Python 3.7 – Real Python
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
* [Python 3 Readiness](https://tiran.github.io/py3readiness)
* [Python Readiness](https://pyreadiness.org)
* [Python 3 Wall of Superpowers](https://python3wos.appspot.com)
* [Python 3 Porting](http://python3porting.com)
* [Can I Use Python 3?](https://caniusepython3.com) and [Can I Use Python 3? GitHub](https://github.com/caniusepython3/caniusepython3.com)

Django and Python 3
* [Django Packages Python 3](https://www.djangopackages.com/python3)

Changeset Python 2 Sunsetting Initiative
* [Kickoff for Communications Work on the Python 2 Sunsetting](https://www.harihareswara.net/sumana/2019/08/05/0)

<!--
https://pypi.org/project/six/ | six · PyPI

https://twitter.com/ncoghlan_dev/status/1137520803283529728 | Nick Coghlan on Twitter: "This is an excellent post from @hawkieowl on the trade-offs of dropping support for older language versions. Controversial opinion though: if you have a service that has had stable requirements for years, trading runtime inefficiency for ease of code changes is a bad trade-off.… https://t.co/e3xKksW7bq"

http://python-future.org/ | Easy, clean, reliable Python 2/3 compatibility — Python-Future documentation

Dropping Support
https://www.anaconda.com/end-of-life-eol-for-python-2-7-is-coming-are-you-ready/ | End of Life (EOL) for Python 2.7 is coming. Are you ready? - Anaconda
https://twitter.com/pganssle/status/978256523909623809 | Paul Ganssle on Twitter: "For any #python folks who may use python-dateutil in your projects, I'm working out the schedule for dropping Python 2.7 support now. The issue for discussion is here: https://t.co/sWRIhe85qp RT appreciated for visibility (don't want anyone blindsided)"
https://github.com/dateutil/dateutil/issues/653 | Python 2 deprecation schedule · Issue #653 · dateutil/dateutil
https://twitter.com/BokehPlots/status/1138961281480704000 | Bokeh Plot Library on Twitter: "It's a few months out, but the preparations for a Bokeh 2.0 release are already apace. Besides dropping Pyhon 2 support, there will be some other small changes made at the same time. We will lay out everything to expect in this major number bump in a blog post soon.… https://t.co/8KThwKBqtS"
-->

## Python Contributing Info and Docs

CPython
* [CPython GitHub](https://github.com/python/cpython) and [CPython Wikipedia](http://en.wikipedia.org/wiki/CPython) 

CPython Bugs Dashboard
* [Bugs](http://bugs.python.org)

CPython Pull Requests
* [CPython Pull Requests](https://github.com/python/cpython/pulls)
* [Core PR Tool](https://github.com/CuriousLearner/pulls)

Official CPython Contributing Guides
* [CPython Dev Guide](https://devguide.python.org), [Alternate URL: CPython Dev Guide Read the Docs](http://cpython-devguide.readthedocs.io), and [CPython Dev Guide GitHub](https://github.com/python/devguide)
* [How to Become a Core Developer- Python Developer's Guide](https://devguide.python.org/coredev)
* [PEP 0007 Style Guide for C Code](https://www.python.org/dev/peps/pep-0007)

Victor Stinner CPython Contributing Guides
* [Victor Stinner: Python Development Documentation](https://pythondev.readthedocs.io/)
* [Victor Stinner: "Welcome to Tutorial to contribute to the CPython project’s documentation!"](https://cpython-core-tutorial.readthedocs.io)

Python Status
* ["Status of Python CIs (buildbots, Travis CI, AppVeyor): July 2018"](https://mail.python.org/pipermail/python-dev/2018-July/154703.html)
* [Python Status](https://status.python.org)
* [Python Status History](https://status.python.org/history)
* [CPython Travis CI](https://travis-ci.org/python/cpython/)

Release
* [PEP 537 -- Python 3.7 Release Schedule](https://www.python.org/dev/peps/pep-0537)
* [PEP 429 -- Python 3.4 Release Schedule](https://www.python.org/dev/peps/pep-0429)
* [PEP 373 -- Python 2.7 Release Schedule](https://www.python.org/dev/peps/pep-0373)

Release Managers
* ["Welcome the 3.8 and 3.9 Release Manager - Łukasz Langa!"](https://mail.python.org/pipermail/python-dev/2018-January/151949.html)

<!--
https://pythondev.readthedocs.io/internals.html

http://devdocs.io/python~3.6/ | DevDocs — Python 3.6 documentation

https://www.python.org/dev/buildbot/

https://devguide.python.org/#quick-reference
https://devguide.python.org/#branchstatus
https://devguide.python.org/#status-of-python-branches | Python Developer’s Guide — Python Developer's Guide
https://devguide.python.org/devcycle.html | 18. Development Cycle — Python Developer's Guide
https://devguide.python.org/pullrequest.html | 3. Lifecycle of a Pull Request — Python Developer's Guide
https://devguide.python.org/committing.html | 16. Committing and Pushing Changes — Python Developer's Guide

https://devguide.python.org/fixingissues/ | 9. Fixing “easy” Issues (and Beyond) — Python Developer's Guide
https://devguide.python.org/runtests/ | 4. Running & Writing Tests — Python Developer's Guide

https://cloud.githubusercontent.com/assets/2680980/23276970/d14a380c-f9d1-11e6-883d-e13b6b211239.png
-->

<!--
https://devguide.python.org/triaging/ | 11. Triaging an Issue — Python Developer's Guide
https://devguide.python.org/devcycle/#devcycle | 17. Development Cycle — Python Developer's Guide

https://devguide.python.org/setup/#compiling | 1. Getting Started — Python Developer's Guide

https://devguide.python.org/pullrequest/#good-prs | 3. Lifecycle of a Pull Request — Python Developer's Guide
https://devguide.python.org/pullrequest/#patchcheck | 3. Lifecycle of a Pull Request — Python Developer's Guide
https://devguide.python.org/pullrequest/#good-commits | 3. Lifecycle of a Pull Request — Python Developer's Guide

https://devguide.python.org/runtests/#runtests | 4. Running & Writing Tests — Python Developer's Guide

https://devguide.python.org/gitbootcamp/#git-pr | 31. Git Bootcamp and Cheat Sheet — Python Developer's Guide

https://www.python.org/dev/peps/pep-0387/ | PEP 387 -- Backwards Compatibility Policy | Python.org
-->

## CPython Experts, Mailing Lists, Core Developer Info, Permissions, Mentors

CPython Experts Index
* [CPython Experts Index](https://devguide.python.org/experts/)

Mailing List and Permissions History
* [Python Core Workflow Mailing List](https://mail.python.org/mailman/listinfo/core-workflow)
* [Permissions History](https://devguide.python.org/developers/#permissions-history)
* [Developer Log](https://github.com/python/devguide/blob/bbd38631554165a64e187bd29815125098159a13/developers.rst)
* [Core Developer Motivations and Affiliations](https://docs.python.org/devguide/motivations.html)
* [Core Developer Office Hours](https://devguide.python.org/help/#office-hour)

Help and Communication
* [Where to Get Help](https://devguide.python.org/help/)
* [Communication](https://devguide.python.org/communication/)

Core Developer Perspectives
* [Raymond Hettinger, "Being a Core Developer in Python", PyBay2016](https://www.youtube.com/watch?list=PL85KuAjbN_gtGn4v1ELSWJlTFZF_5Ciog&v=voXVTjwnn-U)
* [Emily Morehouse: "My Path to Becoming a Python Core Developer"](http://emilyemorehouse.com/blog/015-my-path-to-becoming-a-python-core-developer/) and ["My path to becoming a core developer, @emilyemorehouse #pytexas2019… "](https://www.youtube.com/watch?v=rOzUMQW4p0Y&list=PL5E-19VITtmT0foFkn2Yn25YSnREyZmeJ&index=2&t=0s)
* [Mariatta Wijaya "What is a Python Core Developer?" (North Bay Python)](https://www.youtube.com/watch?v=xvft-_8djUI) and [Mariatta Wijaya "What is a Python Core Developer?" (PyCon 2018)](https://www.youtube.com/watch?v=hhj7eb6TrtI&feature=youtu.be)

<!--
https://twitter.com/TalEinat/status/1156898504884785157
https://twitter.com/gvanrossum/status/1156984705771683840

http://pyfound.blogspot.com/2019/05/python-core-developer-mentorship.html | Python Software Foundation News: Python Core Developer Mentorship
https://github.com/vstinner/conf/blob/master/2019-Pycon/mentoring.pdf | conf/mentoring.pdf at master · vstinner/conf

python core developer mailing list - Google Search

https://mail.python.org/mailman3/lists/core-mentorship.python.org/
https://mail.python.org/mailman/private/core-mentorship/2015-November/003274.html

https://twitter.com/VictorStinner/status/1136236361307045889 | Victor Stinner 🐍 on Twitter: "python-ideas and python-dev mailing lists migrated to Mailman 3: say hello to the new shiny HyperKitty web UI to read *and* post emails to these lists: https://t.co/h6oJ5bBcJ8 Post emails directly in the web UI, nicer UI, stats, single password for multiple lists & more!… https://t.co/4nIxrLTKG5"
-->

Python Mentors
* [Python Mentors](http://pythonmentors.com)

Python Google Summer of Code
* [Python Google Summer of Code](http://python-gsoc.org/)

<!--
Season of Docs
https://code.djangoproject.com/wiki/2019SeasonOfDocs | 2019SeasonOfDocs – Django
https://developers.google.com/season-of-docs/terms/program-rules | Season of Docs 2019 Program Rules  |  Season of Docs  |  Google Developers
https://developers.google.com/season-of-docs/ | Season of Docs  |  Google Developers
https://developers.google.com/season-of-docs/docs/participants/ | Season of Docs  |  Google Developers
https://numfocus.org/blog/numfocus-projects-to-apply-for-inaugural-google-season-of-docs | NumFOCUS Projects Accepted to Inaugural Google Season of Docs - NumFOCUS
-->

## Python Performance, Speed, and Security

Security
* [OpenSSL](https://www.openssl.org/)
* [Python Security](https://python-security.readthedocs.io/)

Speed
* [Python Speed Center](https://speed.python.org/)

<!--
Tools
https://pypy.org/ | PyPy - Welcome to PyPy
https://cython.org/ | Cython: C-Extensions for Python
https://wiki.python.org/moin/Pyrex | Pyrex - Python Wiki
https://cffi.readthedocs.io/en/latest/ | CFFI documentation — CFFI 1.12.3 documentation

https://www.python.org/dev/peps/pep-0578/ | PEP 578 -- Python Runtime Audit Hooks | Python.org
https://speakerdeck.com/tiran/europython-2019-auditing-hooks-and-security-transparency-for-cpython | EuroPython 2019: Auditing hooks and security transparency for CPython - Speaker Deck

https://www.python.org/doc/essays/list2str/ | Python Patterns - An Optimization Anecdote | Python.org

https://twitter.com/randal_olson/status/958389805259214849 | Randy Olson on Twitter: "One of the major reasons that #Python has been so successful is because it's an easy language to develop in and understand. Even if Python is sometimes slower than other languages, programmer time is always more expensive than compute time. https://t.co/x3rJHLrmvK #programming… https://t.co/TYhF2J4vfJ"
https://developers.redhat.com/blog/2017/11/16/speed-python-using-rust/ | Speed up your Python using Rust - RHD Blog

https://jakevdp.github.io/blog/2014/05/09/why-python-is-slow/ | Why Python is Slow: Looking Under the Hood | Pythonic Perambulations

https://github.com/python/performance/blob/master/README.rst | performance/README.rst at master · python/performance
https://github.com/python/performance | python/performance: Python Performance Benchmark Suite
-->

## CPython Workflow Choices and Tools

Core Workflow Tools
* [Core Workflow Tools GitHub](https://github.com/python/core-workflow)
* [cherry_picker](https://github.com/python/core-workflow/tree/master/cherry_picker) and [cherry picker PyPi](https://pypi.org/project/cherry-picker)
* [miss-islington](https://github.com/python/miss-islington)

Issues PEP
* [PEP 581 -- Using GitHub Issues for CPython](https://www.python.org/dev/peps/pep-0581)
* [PEP 581 -- Using GitHub Issues for CPython is Accepted](https://mail.python.org/pipermail/python-dev/2019-May/157399.html)
* [PEP 588 -- GitHub Issues Migration Plan](https://www.python.org/dev/peps/pep-0588/)
* [LWN: "Using GitHub Issues for Python"](https://lwn.net/Articles/754779)

CPython GitHub Migration
* ["The history behind the decision to move Python to GitHub"](https://snarky.ca/the-history-behind-the-decision-to-move-python-to-github)
* ["CPython workflow changes"](https://paper.dropbox.com/doc/CPython-workflow-changes-mx1k8G6M0rg5JLy80F1r6)

Python Environment
* [xkcd: Python Environment](https://xkcd.com/1987)
* [Brett Cannon: Deconstructions xkcd: Python Environment](https://snarky.ca/deconstructing-xkcd-com-1987/)
* [Guido van Rossum on Python Environment](https://twitter.com/Transition/timelines/988219487571898368)

Reality
* [Guido van Rossum: "All the time! Just now I had to... "](https://twitter.com/gvanrossum/status/1072535194131984386)
* [Jacob Kaplan-Moss: "I've literally given up on ideas... "](https://twitter.com/jacobian/status/737441987587018752 )
* [Carlton Gibson: "I have to force push about 8 times every time... "](https://twitter.com/carltongibson/status/1135628987106025478)

<!--
Mariatta Tools
https://github.com/bots-for-humanity

https://github.com/python/miss-islington/issues
https://github.com/python/miss-islington/issues/130 | Don't wait for unrequired status checks. · Issue #130 · python/miss-islington

https://github.com/Mariatta/close-all-pr | Mariatta/close-all-pr
https://github.com/Mariatta/miss-islington/tree/master/backport | miss-islington/backport at master · Mariatta/miss-islington
https://www.slideshare.net/MariattaWijaya/pythonpowered-savage-garden-hotline | Python-Powered Savage Garden Hotline
https://github.com/Mariatta/mariatta-bot | Mariatta/mariatta-bot: Mariatta's GitHub bot
https://pypi.org/project/pytaco/ | pytaco · Warehouse (PyPI)
https://github.com/Mariatta/taco-py | Mariatta/taco-py: Figure out how many taco to order for your meetup
https://github.com/Mariatta/tic_tac_taco_pizza | GitHub - Mariatta/tic_tac_taco_pizza: Play tic tac toe, with taco and pizza
https://github.com/Mariatta/cloner

https://github.com/Mariatta/cookiecutter_sprint_guide
https://github.com/Mariatta/pep_cookiecutter
-->

## C Programming Language 

C Programming Language 
* [C Wikipedia](http://en.wikipedia.org/wiki/C_(programming_language))  
* [C Wikibook](http://en.wikibooks.org/wiki/C_Programming)  
* [Learn to Code the Hard Way- C](https://learncodethehardway.org/c) 
* [C Standard Library Wikipedia](https://en.wikipedia.org/wiki/C_standard_library) 

<!--
https://www.amazon.com/Programming-Language-2nd-Brian-Kernighan/dp/0131103628 | Amazon.com: C Programming Language, 2nd Edition (8601410794231): Brian W. Kernighan, Dennis M. Ritchie: Books
https://www.dipmat.univpm.it/~demeio/public/the_c_programming_language_2.pdf | The C Programming Language (Second Edition)

https://www.geeksforgeeks.org/c-language-set-1-introduction/ | C Language Introduction - GeeksforGeeks
https://www.tutorialspoint.com/cprogramming/c_overview.htm | C Language Overview

http://web.archive.org/web/20150203160832/http://c.learncodethehardway.org/book/
-->

<!-- 
https://github.com/willingc/pyladies-cpython/blob/master/Notes%20on%20Lecture%201.ipynb

http://python-history.blogspot.com/. A few highlights:
http://python-history.blogspot.com/2013/11/the-history-of-bool-true-and-false.html
http://python-history.blogspot.com/2013/11/story-of-none-true-false.html
http://python-history.blogspot.com/2009/03/dynamically-loaded-modules.html

Various Topics
http://opensourcebridge.org/sessions/1881
http://opensourcebridge.org/sessions/1882
https://en.wikipedia.org/wiki/Locality_of_reference
https://en.wikipedia.org/wiki/Open_addressing

https://github.com/mitmproxy/mitmproxy/issues/1381
-->

## CPython Interpreter and Internals

Visualizing How Python Works  		
* [Python Tutor](http://pythontutor.com)

CPython Source Code Guide
* [CPython Source Code Guide](https://realpython.com/cpython-source-code-guide)

PyLadies CPython Source Code Resource Issue
* [PyLadies CPython Source Code Resource Issue](https://github.com/pyladies/pyladies-maintainers/issues/6 )

Yet another guided tour of CPython
* [Yet another guided tour of CPython](https://paper.dropbox.com/doc/Yet-another-guided-tour-of-CPython--Aa3JxpUCv8jV2bO0P8tDYiBzAg-XY7KgFGn88zMNivGJ4Jzv | Yet another guided tour of CPython – Dropbox Paper)

CPython Internals
* [Pablo Salgado: "The Soul of the Beast" YouTube](https://www.youtube.com/watch?v=ELI8WKiUmBY&feature=youtu.be&t=3893) and [Pablo Salgado: "The Soul of the Beast"](https://ep2019.europython.eu/talks/ZJ7mNEK-the-soul-of-the-beast/)
* [Philip Guo- CPython Internals](http://pgbovine.net/cpython-internals.htm) and [Philip Guo- CPython Internals YouTube](https://www.youtube.com/user/pgbovine/playlists)
* [Philip Guo- CPython Internals Course Website](http://courses.pgbovine.net/csc253)
* [Yaniv Aknin: Python’s Internals Tag](https://tech.blog.aknin.name/tag/internals/), [Yaniv Aknin: Python’s Innards: Introduction](https://tech.blog.aknin.name/2010/04/02/pythons-innards-introduction), [Python’s Innards](https://tech.blog.aknin.name/category/my-projects/pythons-innards/), and [Python’s Innards: For My Wife](https://tech.blog.aknin.name/2010/07/04/pythons-innards-for-my-wife)
* [Stéphane Wirtel: "Exploring Our Python Interpreter"](https://speakerdeck.com/matrixise/exploring-our-python-interpreter)
* [Larry Hastings: "Stepping Through CPython"](https://www.youtube.com/watch?v=XGF3Qu4dUqk)
* [Allison Kaptur: "Bytes in the Machine: Inside the CPython interpreter"](https://www.youtube.com/watch?v=HVUTjQzESeo)
* [Eli Bendersky: Python Internals Tag](https://eli.thegreenplace.net/tag/python-internals)
* [Emily Morehouse CPython Guide](https://paper.dropbox.com/doc/CPython-Guide-m7BQyPth6AIDUdZ6EmBNM) and [CPython Notes](https://github.com/emilyemorehouse/cpython-notes)

Byterun
* [Ned Batchelder Byterun GitHub](https://github.com/nedbat/byterun)
* [Allison Kaptur at NYCPython: "Byterun, a Python Bytecode Interpreter"](https://www.slideshare.net/akaptur/byterun-a-python-bytecode-interpreter-at-nycpython)
	
Core- Design of the CPython Compiler
* [Design of the CPython Compiler](https://www.python.org/dev/peps/pep-0339/)

PEG Parser
* [Guido van Rossum: PEG Parsers](https://medium.com/@gvanrossum_83706/peg-parsers-7ed72462f97c)
* [Guido van Rossum: "Generating a PEG Parser"](https://medium.com/@gvanrossum_83706/generating-a-peg-parser-520057d642a9)

Types of Parsers
* [LL Parser Wikipedia](https://en.wikipedia.org/wiki/LL_parser)
* [Top-Down Parsing Wikipedia](https://en.wikipedia.org/wiki/Top-down_parsing)
* [Parsing Expression Grammar Wikipedia](https://en.wikipedia.org/wiki/Parsing_expression_grammar)

Python Virtual Machine
* [Inside the Python Virtual Machine](https://leanpub.com/insidethepythonvirtualmachine/read)

Python Internals
* [Stack Overflow Python Internals Questions Sorted by Votes](https://stackoverflow.com/questions/tagged/python-internals?sort=votes)

<!--
https://medium.com/@gvanrossum_83706/peg-at-the-core-developer-sprint-8b23677b91e6
https://medium.com/@gvanrossum_83706/a-meta-grammar-for-peg-parsers-3d3d502ea332
https://medium.com/@gvanrossum_83706/adding-actions-to-a-peg-grammar-d5e00fa1092f

https://medium.com/@gvanrossum_83706/peg-parsing-series-de5d41b2ed60
https://medium.com/@gvanrossum_83706/left-recursive-peg-grammars-65dab3c580e1 | Left-recursive PEG grammars - Guido van Rossum - Medium
https://medium.com/@gvanrossum_83706/visualizing-peg-parsing-93a36f259423 | Visualizing PEG Parsing - Guido van Rossum - Medium
https://github.com/gvanrossum/pegen
https://github.com/gvanrossum/ctok | gvanrossum/ctok: Expose CPython's tokenizer as a Python class

https://realpython.com/cpython-source-code-guide/#the-python-language-specification | Your Guide to the CPython Source Code – Real Python


https://intopythoncom.files.wordpress.com/2017/04/internalsofcpython3-6-1.pdf

https://devguide.python.org/#resources
https://devguide.python.org/exploring/
https://devguide.python.org/grammar/
https://devguide.python.org/compiler/ | 25. Design of CPython’s Compiler — Python Developer's Guide
https://devguide.python.org/compiler/#abstract | 25. Design of CPython’s Compiler — Python Developer's Guide
https://devguide.python.org/setup/
https://devguide.python.org/setup/#directory-structure

https://github.com/aosabook/500lines | aosabook/500lines: 500 Lines or Less	
https://github.com/aosabook/500lines/tree/master/interpreter	
http://www.aosabook.org/en/500L/a-python-interpreter-written-in-python.html | 500 Lines or Less | A Python Interpreter Written in Python	
https://github.com/aosabook/500lines/blob/master/interpreter/code/byterun/pyvm2.py | 500lines/pyvm2.py at master · aosabook/500lines	
	
https://www.amazon.com/Compilers-Principles-Techniques-Tools-2nd/dp/0321486811 | Compilers: Principles, Techniques, and Tools: Alfred V. Aho, Ravi Sethi, Jeffrey D. Ullman: 9780201100884: Amazon.com: Books

Blogs
https://nedbatchelder.com/blog/201803/is_python_interpreted_or_compiled_yes.html | Ned Batchelder: Is Python interpreted or compiled? Yes.
https://www.curiousefficiency.org/posts/2015/10/languages-to-improve-your-python.html | 27 languages to improve your Python | Curious Efficiency
https://vstinner.github.io/asyncio-proactor-cancellation-from-hell.html | Asyncio: Proactor Cancellation From Hell
https://tirkarthi.github.io/programming/2019/05/08/f-string-debugging.html | f-string debugging in Python 3.8
https://tirkarthi.github.io/programming/2019/05/23/pep-578-overview.html | Overview of runtime audits in PEP 578

Internals
https://twitter.com/anthonypjshaw/status/1129228029698252800 | Anthony Shaw (アントニー・ショー) on Twitter: "Announcement: I’m writing a book on CPython internals. Hopefully published late 2019 or early 2020"

https://tech.blog.aknin.name/2010/07/03/pythons-innards-code-objects/ | Python’s Innards: Code Objects | NIL: .to write(1) ~ help:about

Eli Bendersky
https://eli.thegreenplace.net/ | Eli Bendersky's website
https://eli.thegreenplace.net/2009/11/28/python-internals-working-with-python-asts | Python internals: Working with Python ASTs - Eli Bendersky's website	
https://eli.thegreenplace.net/2010/09/18/python-internals-symbol-tables-part-1 | Python internals: Symbol tables, part 1 - Eli Bendersky's website	
https://eli.thegreenplace.net/2019/to-orm-or-not-to-orm/ | To ORM or not to ORM - Eli Bendersky's website
-->

## CPython Helpers

Regression Test Suite For Python Core Developers
* [Regression Test Suite](https://docs.python.org/3/library/test.html)
* [test.support — Utilities for the Python test suite](https://docs.python.org/3/library/test.html#module-test.support)

Disassember
* [Disassembler Wikipedia](https://en.wikipedia.org/wiki/Disassembler)

<!--
https://github.com/python/pyperformance | python/pyperformance: Python Performance Benchmark Suite

https://docs.python.org/3/library/os.html | os — Miscellaneous operating system interfaces — Python 3.7.4rc2 documentation
https://docs.python.org/3/reference/datamodel.html | 3. Data model — Python 3.7.4rc2 documentation
https://docs.python.org/3/reference/executionmodel.html | 4. Execution model — Python 3.7.4rc2 documentation

https://docs.python.org/3/library/dis.html | dis — Disassembler for Python bytecode — Python 3.7.4rc2 documentation
https://docs.python.org/3/library/dis.html#dis.Instruction | dis — Disassembler for Python bytecode — Python 3.7.4rc2 documentation

https://docs.python.org/3/library/inspect.html	
		
2. Using the Python Interpreter	

https://speakerdeck.com/tiran/europython-2019-introduction-to-low-level-profiling-and-tracing | EuroPython 2019: Introduction to low-level profiling and tracing - Speaker Deck

https://github.com/0xAX/linux-insides | 0xAX/linux-insides: A little bit about a linux kernel

https://github.com/microsoft/WSLv2-Linux-Kernel | microsoft/WSLv2-Linux-Kernel: The Linux kernel underpinning the new Windows Subsystem for Linux v2

Linux
https://twitter.com/brendangregg/status/1150796412931600384/photo/2
https://twitter.com/brendangregg/status/1150796412931600384 | Brendan Gregg on Twitter: "Announcing my next book: BPF Performance Tools: Linux System and Application Observability, for which I developed over 100 new tools https://t.co/GiYiBPICo5… https://t.co/bhGDofUj7Z"
http://www.brendangregg.com/blog/2019-07-15/bpf-performance-tools-book.html | BPF Performance Tools: Linux System and Application Observability (book)
https://www.google.com/search?q=linux+performance+tools&source=lnms&tbm=isch&sa=X&ved=0ahUKEwj6xP6t27fjAhWEZs0KHQd_D0wQ_AUIECgB&biw=1365&bih=614#imgrc=ZXehEkMmqZ0v3M: | linux performance tools - Google Search
http://man7.org/linux/man-pages/man2/ptrace.2.html | ptrace(2) - Linux manual page
https://en.wikipedia.org/wiki/Ptrace | ptrace - Wikipedia
http://man7.org/linux/man-pages/ | Linux man pages online
https://www.tutorialspoint.com/unix/unix-manpage-help | Unix / Linux Shell Manpage Help
-->

## CPython and Django Docs

CPython Docs
* [About These Documents](https://docs.python.org/3/about.html)

Django Docs
* [Writing Documentation](https://docs.djangoproject.com/en/dev/internals/contributing/writing-documentation/)
* [Writing Documentation: How Documentation is Organized](https://docs.djangoproject.com/en/dev/internals/contributing/writing-documentation/#how-the-documentation-is-organized)

<!--
https://devguide.python.org/#contributing
https://twitter.com/mariatta/status/1154436363946737664
https://devguide.python.org/documenting/#building-the-documentation | 7. Documenting Python — Python Developer's Guide
https://docs.python.org/devguide/docquality.html?highlight=sphinx | 6. Helping with Documentation — Python Developer's Guide

https://docs.python-guide.org/writing/style/ | Code Style — The Hitchhiker's Guide to Python
https://github.com/realpython/python-guide | realpython/python-guide: Python best practices guidebook, written for humans.

Doc/build/html/index.html - Google Search
https://github.com/python/core-workflow/issues/174 | pip install blurb successfully installs with Python < 3.5 · Issue #174 · python/core-workflow
https://pypi.python.org/pypi/blurb
-->

## Django Contributing Info and Docs

Django GitHub
* [Django GitHub](https://github.com/django/django)

Django Pull Requests
* [Django Pull Requests](https://github.com/django/django/pulls)

Django Bug Tracker, Wiki, and Development Dashboard
* [Django Bug Tracker and Wiki](https://code.djangoproject.com)
* [Django Development Dashboard](https://dashboard.djangoproject.com)

Django and Python Contributing
* [Django Internals](https://docs.djangoproject.com/en/dev/internals)
* [Django Contributing](https://docs.djangoproject.com/en/dev/internals/contributing)

Django Core Mentorship
* [Django Core Mentorship Google Group](https://groups.google.com/forum/#!forum/django-core-mentorship)
* [Django Core Mentorship Mailing List](https://docs.djangoproject.com/en/dev/internals/mailing-lists/#django-core-mentorship)

Django Developers Mailing Lists, Forum and Slack
* [Django Mailing Lists](https://docs.djangoproject.com/en/dev/internals/mailing-lists)
* [Django Google Developers Forum](https://groups.google.com/forum/#!forum/django-developers) 
* [Django Developers Slack](https://django-developers.herokuapp.com)

Django Software
* [Django Reporting Bugs and Requesting Features](https://docs.djangoproject.com/en/dev/internals/contributing/bugs-and-features/#reporting-bugs)
* [Django Submitting a Patch](https://docs.djangoproject.com/en/dev/internals/contributing/writing-code/submitting-patches/)

Django Tickets
* [Tickets](https://code.djangoproject.com/query)
* [Life of a Django Ticket](https://docs.google.com/presentation/d/1Ao0S3Z-VRn_pcT5T4mXIhv3t3liQ3ZrwqaGeDqz9XCQ/edit)

<!--
https://groups.google.com/forum/#!forum/django-updates | (99+) Django updates – Google Groups
-->

Django Roadmaps
* [Django 2.1 Roadmap](https://code.djangoproject.com/wiki/Version2.1Roadmap) 
* [Django Roadmap to 2.0](https://www.djangoproject.com/weblog/2015/jun/25/roadmap) 

Release Process
* [Django’s Release Process](https://docs.djangoproject.com/en/dev/internals/release-process/)

Release Cadence
* [Django Release Cadence](https://docs.djangoproject.com/en/dev/internals/release-process/#internal-release-cadence)

Django Blog and Announcements
* [Django Blog](https://www.djangoproject.com/weblog/)
* [Django Announcements](https://groups.google.com/forum/#!forum/django-announce)

New Releases
* [Django Releases](https://docs.djangoproject.com/en/stable/releases)

Release Notes
* [Release Notes](https://docs.djangoproject.com/en/dev/releases/)
* [Django 2.2 Release Notes](https://docs.djangoproject.com/en/2.2/releases/2.2/)
* [Django 2.1 Release Notes](https://docs.djangoproject.com/en/2.1/releases/2.1)
* [Django 2.0 Release Notes](https://docs.djangoproject.com/en/2.2/releases/2.0/)
* [Django 1.11 Release Notes](https://docs.djangoproject.com/en/2.2/releases/1.11/)

Supported Versions
* [Supported Versions](https://www.djangoproject.com/download/#supported-versions)
* [Supported Versions Policy](https://docs.djangoproject.com/en/dev/internals/release-process/#supported-versions-policy)

Depreciation
* [Depreciation](https://docs.djangoproject.com/en/dev/internals/deprecation/)

Upgrading and Choices
* [Upgrading Django to a Newer Version](https://docs.djangoproject.com/en/dev/howto/upgrade-version/)
* [What Python Version Should I Use with Django](https://docs.djangoproject.com/en/dev/faq/install/#what-python-version-should-i-use-with-django)
* [Should I Use the Stable Version or Development Version](https://docs.djangoproject.com/en/dev/faq/install/#should-i-use-the-stable-version-or-development-version)

<!--
https://twitter.com/andrewgodwin/status/1158258293141172225 | Andrew Godwin on Twitter: "Lots of good Django progress at the #pyconau sprints so far - async views branch has less than 10 failures, asgiref has had several fixes, and several parts of the community pages are getting cleaned up!" / Twitter
https://twitter.com/carltongibson/status/1158345931491819520 | Carlton Gibson on Twitter: "From far away, my #pyconau sprints hero is @rixxtr for giving much needed love to https://t.co/tJXlvbdFNW and related projects such as djangopeople. Super stuff! 🏅 https://t.co/regbuogwiU✓&amp;q=+is%3Apr+author%3Arixx+" / Twitter

https://docs.djangoproject.com/en/dev/releases/dev/#python-compatibility | Django 2.0 release notes | Django documentation | Django

https://code.djangoproject.com/wiki/Reports | Reports – Django
https://docs.djangoproject.com/en/dev/internals/contributing/ | Contributing to Django | Django documentation | Django

https://docs.djangoproject.com/en/dev/internals/contributing/writing-code/working-with-git/ | Working with Git and GitHub | Django documentation | Django

https://docs.djangoproject.com/en/dev/internals/contributing/writing-code/coding-style/ | Coding style | Django documentation | Django

https://docs.djangoproject.com/en/dev/internals/contributing/committing-code/ | Committing code | Django documentation | Django
https://docs.djangoproject.com/en/dev/internals/contributing/committing-code/#committing-guidelines | Committing code | Django documentation | Django

https://docs.djangoproject.com/en/dev/topics/testing/overview/ | Writing and running tests | Django documentation | Django
https://docs.djangoproject.com/en/dev/internals/contributing/writing-code/unit-tests/ | Unit tests | Django documentation | Django
https://docs.djangoproject.com/en/dev/internals/contributing/writing-code/unit-tests/#running-unit-tests | Unit tests | Django documentation | Django

https://docs.djangoproject.com/en/dev/internals/contributing/writing-code/javascript/#javascript-patches | JavaScript | Django documentation | Django

https://docs.djangoproject.com/en/dev/internals/release-process/#supported-versions-policy | Django’s release process | Django documentation | Django
https://docs.djangoproject.com/en/dev/internals/release-process/#internal-release-deprecation-policy | Django’s release process | Django documentation | Django
https://docs.djangoproject.com/en/dev/internals/contributing/writing-code/submitting-patches/#deprecating-a-feature | Submitting patches | Django documentation | Django

https://docs.djangoproject.com/en/dev/internals/contributing/writing-documentation/ | Writing documentation | Django documentation | Django
https://docs.djangoproject.com/en/dev/internals/contributing/writing-documentation/#documenting-new-features | Writing documentation | Django documentation | Django
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

Vinta Django Apps Checklist	
* [Vinta Django Apps Checklist](https://devchecklists.com/django-apps-checklist)	

 Vinta API Checklist	
* [Vinta API Checklist](https://devchecklists.com/python-api-checklist) and [Vinta API Checklist GitHub](https://github.com/vintasoftware/python-api-checklist)

Python- Wheel (versus Egg!)
* [Python Packaging Wheel vs. Egg](http://python-packaging-user-guide.readthedocs.io/discussions/wheel-vs-egg)
* [Wheel PyPi](https://pypi.org/project/wheel) and [Wheel Read the Docs](http://wheel.readthedocs.org)
* [Python Wheels](http://pythonwheels.com)

TestPyPI
* [TestPyPI](https://test.pypi.org)
* [Using TestPyPI](https://packaging.python.org/guides/using-testpypi)

Package Helpers
* [Twine GitHub](https://github.com/pypa/twine) and [Twine PyPi](https://pypi.python.org/pypi/twine)

Python- Packages/Libraries
* [Warehouse](https://pypi.org), [Warehouse GitHub](https://github.com/pypa/warehouse), and [Warehouse Read the Docs](https://warehouse.readthedocs.io)
 
Core Packaging Utilities
* [PyPa Core Packaging Utilities](https://github.com/pypa/packaging)  
* [PyPa Core Packaging Utilities Documents](https://packaging.pypa.io) 

<!--
https://devchecklists.com/production-launch-checklist/ | Devchecklists | Production Launch Checklist

DjangoCon Europe 2017 Vinta
https://www.youtube.com/watch?v=AMg4Iind90Q | (1) "Qualities of great reusable Django apps" by Flávio Juvenal da Silva Junior - YouTube
https://docs.google.com/presentation/d/1yapK1hYt8f64ztLCc7yFpCI4RG1vTMLhqwZ6cUBZIvI/edit#slide=id.p | Qualities of great reusable Django apps - DjangoCon Europe 2017 - Google Slides
https://www.vinta.com.br/blog/2017/djangocon-europe-2017-was-awesome/ | DjangoCon Europe 2017 was awesome! – Vinta Software
-->

<!--
https://github.com/pypa/integration-test | pypa/integration-test: ensure core packaging tools work well with each other

https://twitter.com/ncoghlan_dev/status/1146177537497714688 | Nick Coghlan on Twitter: "You won't settle that debate easily: https://t.co/62cgLT9f1w :)… "

https://packaging.python.org/overview/ | An Overview of Packaging for Python — Python Packaging User Guide
https://docs.python.org/3/distutils/configfile.html | 3. Writing the Setup Configuration File — Python 3.7.3rc1 documentation
https://docs.python.org/3/tutorial/modules.html#packages | 6. Modules — Python 3.7.3rc1 documentation

https://wiki.python.org/psf/PackagingWG | PackagingWG - PSF Wiki

Seeking a new maintainer for packaging.python.org and Twine.
https://mail.python.org/archives/list/distutils-sig@python.org/thread/M7VRNT5KP4YQ6UPVI4MN4IIWM2Z3IXCH/

https://hynek.me/articles/python-app-deps-2018/ | Python Application Dependency Management in 2018 · Homepage of Hynek Schlawack

https://twitter.com/di_codes/status/1135628015147388928 | Dustin Ingram on Twitter: "Ever wondered what is going on when you `pip install numpy` and it downloads some file with a name like `numpy-1.16.4-cp37-cp37m-manylinux1_x86_64.whl `? This is a built distribution, and @brettsky just published a great explanation of what every part of that filename means.… https://t.co/yJAXS13a2J"
https://snarky.ca/the-challenges-in-designing-a-library-for-pep-425/ | The challenges in designing a library for PEP 425 (aka wheel tags)

https://pypi.org/project/check-manifest/ | check-manifest · PyPI

https://pypi.org/classifiers/ | Classifiers · PyPI
https://packaging.python.org/specifications/core-metadata/#description-content-type-optional | Core metadata specifications — Python Packaging User Guide

https://packaging.python.org/guides/distributing-packages-using-setuptools/ | Packaging and distributing projects — Python Packaging User Guide
https://pypi.org/project/keyring/ | keyring · PyPI


https://twitter.com/di_codes/status/1137014821923241986 | Dustin Ingram on Twitter: "Ask anyone about packaging, and they'll tell you the same thing: "it sucks". Now, I don't think it sucks. I think it's challenging, hard to grasp, complicated, has some rough edges, has a lot of historical baggage. I think it was built by people, and people aren't perfect. 5/16"

https://www.python.org/dev/peps/pep-0566/ | PEP 566 -- Metadata for Python Software Packages 2.1 | Python.org
https://www.python.org/dev/peps/pep-0518/ | PEP 518 -- Specifying Minimum Build System Requirements for Python Projects | Python.org
https://www.python.org/dev/peps/pep-0496/ | PEP 496 -- Environment Markers | Python.org
https://www.python.org/dev/peps/pep-0508/#id23 | PEP 508 -- Dependency specification for Python Software Packages | Python.org

https://www.python.org/dev/peps/pep-0427/ | PEP 427 -- The Wheel Binary Package Format 1.0 | Python.org
https://www.python.org/dev/peps/pep-0438/ | PEP 438 -- Transitioning to release-file hosting on PyPI | Python.org
https://www.python.org/dev/peps/pep-0440/ | PEP 440 -- Version Identification and Dependency Specification | Python.org
https://www.python.org/dev/peps/pep-0517/

https://discuss.python.org/t/pycon-us-packaging-mini-summit-2019/833/44 | PyCon US Packaging Mini-Summit 2019 - Packaging - Discussions on Python.org

Wheels
https://packaging.python.org/guides/distributing-packages-using-setuptools/#wheels | Packaging and distributing projects — Python Packaging User Guide
https://packaging.python.org/tutorials/packaging-projects/#wheels | Packaging Python Projects — Python Packaging User Guide
https://pip.pypa.io/en/stable/reference/pip_wheel

Sample project
https://github.com/crwilcox/my-pypi-package | crwilcox/my-pypi-package: A sample package to publish to pypi that uses circleci for CI and nox for test automation
https://github.com/crwilcox/my-pypi-package/blob/master/.circleci/config.yml | my-pypi-package/config.yml at master · crwilcox/my-pypi-package
https://speakerdeck.com/crwilcox/pycon-2019-shipping-your-first-python-package-and-automating-future-publishing?slide=14 | PyCon 2019 - Shipping your first Python package and automating future publishing - Speaker Deck
https://www.youtube.com/watch?v=P3dY3uDmnkU | Chris Wilcox - Shipping your first Python package and automating future publishing - PyCon 2019 - YouTube

https://www.bernat.tech/pep-517-and-python-packaging/ | The state of Python Packaging - package types
https://github.com/gaborbernat/pugs | gaborbernat/pugs: random pug quote provider
https://github.com/ipfs/package-managers/issues/56 | Interesting academic papers related to package management · Issue #56 · ipfs/package-managers

Improvements
https://pythoninsider.blogspot.com/2019/05/use-two-factor-auth-to-improve-your.html | Python Insider: Use two-factor auth to improve your PyPI account's security
https://packaging.python.org/guides/making-a-pypi-friendly-readme/ | Making a PyPI-friendly README — Python Packaging User Guide



New- Packaging
https://pydist.com/blog/distributions-vs-releases | PyDist – Blog
https://github.com/jazzband/pip-tools | jazzband/pip-tools: A set of tools to keep your pinned Python dependencies fresh.
-->

<!--
https://wiki.python.org/moin/CheeseShop | CheeseShop - Python Wiki

https://wiki.python.org/moin/Distutils | Distutils - Python Wiki

https://docs.python.org/3/distutils/introduction.html | 1. An Introduction to Distutils — Python 3.6.4rc1 documentation
https://docs.python.org/3/distutils/setupscript.html | 2. Writing the Setup Script — Python 3.6.4rc1 documentation
https://docs.python.org/3.1/distutils/uploading.html | 7. Uploading Packages to the Package Index — Python v3.1.5 documentation
https://docs.python.org/3.6/distutils/packageindex.html#package-index | 6. The Python Package Index (PyPI) — Python 3.6.4rc1 documentation
https://docs.python.org/3/distutils/sourcedist.html | 4. Creating a Source Distribution — Python 3.6.4rc1 documentation

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

Tools
https://docs.python-guide.org/dev/virtualenvs/ | Pipenv & Virtual Environments — The Hitchhiker's Guide to Python
https://pypi.org/project/poetry/ | poetry · PyPI
https://poetry.eustace.io/ | Poetry - Python dependency management and packaging made easy.
https://pipxproject.github.io/pipx/ | pipx
https://github.com/dephell/dephell | dephell/dephell: Python project management. Manage packages: convert between formats, lock, install, resolve, isolate, test, build graph, show outdated, audit. Manage venvs, build package, bump version.

https://packaging.python.org/discussions/install-requires-vs-requirements/ | install_requires vs requirements files — Python Packaging User Guide
https://pip.pypa.io/en/stable/user_guide/#requirements-files

https://www.youtube.com/watch?v=GBQAKldqgZs | Kenneth Reitz - Pipenv: The Future of Python Dependency Management - PyCon 2018 - YouTube
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

<!--
https://www.youtube.com/watch?v=AQsZsgJ30AE
https://www.youtube.com/watch?v=EdD6Ifjlle4 | DjangoCon US 2018 - Packaging Django Apps for Distribution on PyPI by Laura Hampton - YouTube
https://www.youtube.com/watch?time_continue=1&v=QgZ7qv4Cd0Y | How To Publish A Package On PyPI - YouTube
-->

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
https://packaging.python.org/guides/migrating-to-pypi-org/ | Migrating to PyPI.org — Python Packaging User Guide
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

## Django- General

DSF Internship
* [DSF Internship](https://www.djangoproject.com/weblog/2019/apr/24/internship-opportunity-dsf-app/)

Carlton Gibson's Talks
* [Carlton Gibson: Your Framework Needs You (DjangoCon US 2018](https://2018.djangocon.us/talk/your-web-framework-needs-you)
* [Carlton Gibson: Feeding the Pony: Contributing back to Django & How to make that work for you DjangoCon Europe 2019](https://2019.djangocon.eu/talks/feeding-the-pony-contributing-back-to-django-how-t/)

<!--
https://2018.djangocontent.eu/hd/talk/MUAVUD/ | Growing old gracefully: on being a career programmer. :: DjangoCon Europe 2018 :: pretalx

https://www.youtube.com/watch?time_continue=4&v=xlbxa3rw5cw
"@rixxtr says the first step to contributing to Django: acquire a ticket. Except... there are currently 1300 tickets and you click "view tickets" not "search" #PyConAU"
https://twitter.com/weatheredpup/status/1157171428904488961
-->

Dissolving Django Core
* [James Bennett: Core No More](https://www.b-list.org/weblog/2018/nov/20/core)
* [Django DEP: Add draft DEP dissolving Django core. by ubernostrum](https://github.com/django/deps/pull/47)
* [Rough draft Django DEP: Dissolving Django Core](https://github.com/ubernostrum/deps/blob/draft-dissolve-core/draft/XXXX-dissolve-core.rst)
* [Draft proposal: dissolving "Django core" - Google Groups](https://groups.google.com/forum/#!topic/dsf-members/yqnWGII63mI)
* [On the Django core team - Google Groups](https://groups.google.com/forum/#!topic/dsf-members/GWOzvsOAGUs)

<!--
https://github.com/django/djangoproject.com/pull/912 | add docker for local development by mjhea0 · Pull Request #912 · django/djangoproject.com

https://github.com/encode/django-rest-framework/pull/6615 | Dropped Python 2 compatibility. by carltongibson · Pull Request #6615 · encode/django-rest-framework
-->

Django Triage & Review Team
* [Django: Creating a new "Triage & Review Team"](https://groups.google.com/forum/#!topic/django-developers/mUBWlG0-Jbw/discussion)

## Python Governance

Python Authorities
* [Python Packaging Authority (PyPA)](https://pypa.io) and [Python Packaging Authority GitHub](https://github.com/pypa) 
* [Python Authority Authority (PyAA) GitHub](https://github.com/pyaa)
* [Python Code Quality Authority (PyCQA) GitHub](https://github.com/PyCQA) and [Python Code Quality Authority (PyCQA) GitLab](https://gitlab.com/groups/pycqa)
* [Python Cryptographic Authority (PyCA) GitHub](https://github.com/pyca)

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
https://twitter.com/llanga/status/1156568264396419073 | Łukasz Langa on Twitter: "@zooba Well, the Steering Council can *and should* set a roadmap for Python's next decade. I'm talking about it in my keynote. But what not even the SC can do is tell a group of people to *abandon* a particular use case. For example, imagine they told MicroPython to drop their project." / Twitter
https://twitter.com/brettsky/status/1156684427486879745 | Brett Cannon on Twitter: "@zooba I would love to do it as well, but without staff to help make those plans happen the best we can offer is the vision document we're working on to try to coax ppl in a certain direction along with a longer time horizon to compensate for volunteer (un)availability" / Twitter
https://github.com/rust-lang/rfcs/blob/master/text/2657-roadmap-2019.md | rfcs/2657-roadmap-2019.md at master · rust-lang/rfcs

https://mail.python.org/mm3/archives/list/distutils-sig@python.org/thread/QT7SKORCF6OKWO3OVP5KO6XNGU2AR6TU/ | Mailman 3 Handing over default BDFL-Delegate responsibilities for packaging interoperability PEPs to Paul Moore - Distutils-SIG - python.org

https://www.python.org/nominations/elections/2019-python-software-foundation-board/nominees/jannis-leidel/ | Nomination for | Python.org

Elections
https://twitter.com/di_codes/status/1137014831805095937
https://www.python.org/nominations/elections/ | Elections | Python.org
https://www.python.org/nominations/elections/2019-python-software-foundation-board/nominees/ | Nomination for | Python.org
https://www.youtube.com/watch?v=sORneSQNOmc&feature=youtu.be | (1) python.org self nomination demonstration - YouTube
https://wiki.python.org/moin/PythonSoftwareFoundation | PythonSoftwareFoundation - Python Wiki

Steering Committee
https://github.com/python/steering-council | python/steering-council: Communications from the Steering Council
https://github.com/python/steering-council/blob/master/updates/2019-02-26_steering-council-update.md | steering-council/2019-02-26_steering-council-update.md at master · python/steering-council

https://www.europython-society.org/post/182445627020/announcing-the-guido-van-rossum-core-developer | EuroPython Society — Announcing the Guido van Rossum Core Developer...

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

## Python and Django PEPs and DEPs

PEPs
* [PEP Index](https://www.python.org/dev/peps)
* [Legacy PEP Index](https://legacy.python.org/dev/peps)

PEP Template
* [PEP 12 -- Sample reStructuredText PEP Template](https://www.python.org/dev/peps/pep-0012)

DEPs (Django Enhancement Proposals)
* [DEPs (Django Enhancement Proposals) GitHub](https://github.com/django/deps)

<!--
https://github.com/FlipperPA/django-dep-default-project | FlipperPA/django-dep-default-project: A Django Enhancement Proposal (DEP) to make the default project more friendly to newcomers.
-->

## Python Summits and Sprints

Python Language Summits
* [The 2019 Python Language Summit](http://pyfound.blogspot.com/2019/05/the-2019-python-language-summit.html)
* [The 2018 Python Language Summit](https://lwn.net/Articles/754152)

Python Core Sprint 2018
* [Python Blog "CPython Core Developer Sprint 2018"](http://pyfound.blogspot.com/2018/09/cpython-core-developer-sprint-2018.html)
* [Mariatta: Part 1](https://mariatta.ca/core-sprint-2018-part-1.html) and [Mariatta: Part 2](https://mariatta.ca/core-sprint-2018-part-2.html)
* [Victor Stinner](https://twitter.com/VictorStinner/status/1041219533439217665)

Python Core Sprint 2016
* [Lukasz Langa: Diversity on the Python Sprint in September](http://lukasz.langa.pl/12/diversity-python-sprint-september)

<!--
https://pyfound.blogspot.com/2019/06/python-language-summit-lightning-talks-part-2.html | Python Software Foundation News: Python Language Summit Lightning Talks, Part 2

http://pycon.blogspot.com/2016/05/how-to-get-ready-for-pycon-development.html
-->

Python Sprints
* [Python Sprints](https://python-sprints.github.io)

<!--
https://wiki.python.org/moin/EuroPython2018/CPython | EuroPython2018/CPython - Python Wiki
-->

### Python Tools and Official Status

PSF Infrastructure Configuration
* [PSF Infrastructure Configuration GitHub](https://github.com/python/psf-salt)

PSF Repos
* [Python Software Foundation GitHub Organization](https://www.python.org/psf/github/)
* [PSF GitHub](https://github.com/psf)
* [PyFound GitHub](https://github.com/pyfound)

Kenneth Reitz Repos
* ["I’m looking for some new owners for some of my repositories."](https://twitter.com/kennethreitz/status/1151551174925049858)
* [Ernest's Response](https://github.com/not-kennethreitz/team/issues/21#issuecomment-512560246)

Repos Under "Python" GitHub Organization
* [Python Steering Committee: "Repositories under the "python" organization on GitHub"](https://github.com/python/steering-council/issues/9)
* [Dustin Ingram: "Relevant discussion"](https://twitter.com/di_codes/status/1125778236930174977)

Black Moving Under "Python" GitHub Organization
* [Łukasz Langa Tweet](https://twitter.com/llanga/status/1123980466292445190)

DEP 0008: Formatting Code with Black
* [Accepted: DEP 0008: Formatting Code with Black](https://github.com/django/deps/blob/master/accepted/0008-black.rst)
* [Andrew Godwin Tweet](https://twitter.com/andrewgodwin/status/1127027840296177666)
* [Łukasz Langa Tweet: "I'm not crying, you're crying"](https://twitter.com/llanga/status/1127075906286002176)

<!--
https://github.com/python/psf-infra-meta/issues | Issues · python/psf-infra-meta

Black
https://twitter.com/llanga/status/1001919374716948480 | Łukasz Langa on Twitter: "If you are really attached to your string quotes and that attachment was the one thing blocking you from adopting Black, the uncompromising #python code formatter, look here: https://t.co/q3QhYBeiru (Note that Black's recommendation on the matter doesn't change.)"
https://github.com/ambv/black/commit/8ebbd268880f15834b70910a6dc61e1ee7596b7c | Add --skip-string-normalization · ambv/black@8ebbd26
https://twitter.com/llanga/status/1153417052302053378
https://twitter.com/llanga/status/1153417050024550401
-->

pipenv
* [pipenv as The PyPA recommended tool for installing Python packages](https://packaging.python.org/guides/tool-recommendations/) and [Python Packaging User Guide: Managing Application Dependencies](https://packaging.python.org/tutorials/managing-dependencies/#managing-dependencies)

DJ Static, DJ Database URL
* [Kenneth Reitz: DJ Static GitHub](https://github.com/kennethreitz/dj-static)
* [Kenneth Reitz: DJ Database URL GitHub](https://github.com/kennethreitz/dj-database-url), [DJ Database URL PyPi](https://pypi.python.org/pypi/dj-database-url), and [DJ Database URL Python Warehouse](https://warehouse.python.org/project/dj-database-url)

Records, Requests (HTTP for Humans), Requests HTML
* [Kenneth Reitz: Records GitHub](https://github.com/kennethreitz/records)
* [Kenneth Reitz: Requests PyPi](https://pypi.python.org/pypi/requests), [Requests](https://python-requests.org/), [Requests Docs](http://docs.python-requests.org), and [Requests GitHub](https://github.com/requests/requests)
* [Kenneth Reitz: Requests HTML](http://html.python-requests.org) and [Requests HTML GitHub](https://github.com/kennethreitz/requests-html)

<!--
https://github.com/kennethreitz/responder | kennethreitz/responder: A familiar HTTP Service Framework for Python.

https://github.com/kennethreitz/requests3#requests-iii-http-for-humans-and-machines-alike | kennethreitz/requests3: Requests 3.0, for Humans and Machines, alike. 🤖
https://github.com/requests/requests-threads | requests/requests-threads: 🎭 Twisted Deferred Thread backend for Requests.

https://github.com/kennethreitz/pip-purge
https://github.com/kennethreitz/twitter-scraper | kennethreitz/twitter-scraper: Scrape the Twitter Frontend API without authentication.
https://github.com/kennethreitz/background | kennethreitz/background: Runs things in the background.
https://github.com/kennethreitz/homebrew-pythons
-->

## python.org and djangoproject.com Contributing

python.org Contributing
* [python.org GitHub](https://github.com/python/pythondotorg)
* [python.org Issues](https://github.com/python/pythondotorg/issues)
* [python.org Staging](https://staging.python.org)
* [python.org Read the Docs](https://pythondotorg.readthedocs.io)
* [python.org Read the Docs Install](https://pythondotorg.readthedocs.io/install.html) and [python.org Read the Docs Contributing](https://pythondotorg.readthedocs.io/contributing.html)
* [Couldn't set up local environment](https://github.com/python/pythondotorg/issues/987)
* [python.org Contributors](https://github.com/python/pythondotorg/graphs/contributors)

djangoproject.com Contributing
* [djangoproject.com GitHub](https://github.com/django/djangoproject.com)

## Codes of Conduct and CLA

PSF Code of Conduct Working Group
* [PSF Code of Conduct Working Group](https://mail.python.org/pipermail/psf-community/2018-April/000488.html)

Django Code of Conduct and CLA
* [Django Code of Conduct](https://www.djangoproject.com/conduct) and [Django Code of Conduct GitHub](https://github.com/django/code-of-conduct)
* [Django Contributor License Agreements](https://www.djangoproject.com/foundation/cla)
