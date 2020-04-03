# Python and Django- Contributing

<!--
Poetry
https://twitter.com/SDisPater/status/1245782235392942080

https://www.djangoproject.com/weblog/2020/apr/01/bugfix-releases/

https://jefftriplett.com/django-release-cycle/

https://twitter.com/cfactoid/status/1245803183848513537
https://twitter.com/cfactoid/status/1245493559253446658
https://twitter.com/di_codes/status/1245049626971037696
https://twitter.com/cfactoid/status/1244795881406242823
https://twitter.com/moshezadka/status/1245906711749124097

pip for Python on Windows
https://twitter.com/simonw/status/1243297680886870017

Ruby and Rust
https://twitter.com/thejonanshow/status/1196462092649406465 | Jonan Scheffler on Twitter: ""Today, we can't keep ignoring multicore. We're going to provide multiple concurrency models: one for CPU bottlenecks and one for I/O bottlenecks."" / Twitter

Language Summit
https://twitter.com/pganssle/status/1224378970340233216

https://status.python.org

https://docs.python.org/dev/whatsnew/3.9.html
https://www.python.org/downloads/release/python-390a5/

Ubuntu
https://www.linuxtoday.com/developer/python-2-removed-from-ubuntu-20.04-lts-200219221006.html?utm_source=dlvr.it&utm_medium=twitter | Linux Today - Python 2 Removed from Ubuntu 20.04 LTS!

Fedora
https://twitter.com/VictorStinner/status/1206876992026664960 | Victor Stinner 🐍 on Twitter: "Great rationale about the maintenance burden of a whole operating system, Adam Williamson on Fedora dropping features like x86 architecture, Python 2 and optical media https://t.co/cRds7It67m "Fedora is not a museum piece, it's a living, relatively forward-looking distribution."" / Twitter
https://lists.fedoraproject.org/archives/list/devel@lists.fedoraproject.org/message/YUTCNQKX4X756N7DYXRGTBRZOAKEP653/ | Re: Fedora 32 System-Wide Change proposal: Drop Optical Media Release Criterion - devel - Fedora Mailing-Lists

Python Rec
https://twitter.com/jakevdp/status/1232552739864924160 | Jake VanderPlas on Twitter: "For Python package maintainers considering which Python versions to support going forward, check out the recommendations from the Numpy community in NEP 29: https://t.co/AjEjsrkd5j https://t.co/I9aI2KAyxV" / Twitter
https://numpy.org/neps/nep-0029-deprecation_policy.html | NEP 29 — Recommend Python and Numpy version support as a community policy standard — NumPy Enhancement Proposals

PEP 614
https://twitter.com/pganssle/status/1235656233539026944

https://discuss.python.org/t/pep-594-removing-dead-batteries-from-the-standard-library/1704
https://www.python.org/dev/peps/pep-0594/

hugs.python.org
-->

## Authorities

<!--
https://blog.ganssle.io/articles/2019/08/test-as-installed.html

https://snarky.ca/what-the-heck-is-pyproject-toml/

https://snarky.ca/the-challenges-in-designing-a-library-for-pep-425/

https://snarky.ca/a-quick-and-dirty-guide-on-how-to-install-packages-for-python/
https://hynek.me/articles/testing-packaging/
https://hynek.me/articles/conditional-python-dependencies/ | Conditional Python Dependencies · Homepage of Hynek Schlawack

https://hynek.me/articles/python-app-deps-2018/ | Python Application Dependency Management in 2018 · Homepage of Hynek Schlawack

Important!
https://twitter.com/anthonypjshaw/status/1200387635555921920 | Anthony Shaw 🐍 on Twitter: "Spent 2 hours trying to debug failing tests only to realise it was testing an old version of the package. Always run “python -m pytest” not “pytest” 😫. Now that flit supports src I might move it over to avoid making the same silly mistake" / Twitter

https://snarky.ca/why-you-should-use-python-m-pip/
python -m pip install X
https://twitter.com/mariatta/status/1217494274469548032
https://twitter.com/mariatta/status/1189243515739561985

http://python-notes.curiousefficiency.org/en/latest/python_concepts/import_traps.html | Traps for the Unwary in Python’s Import System — Nick Coghlan's Python Notes 1.0 documentation
http://python-notes.curiousefficiency.org/en/latest/python3/multicore_python.html | Efficiently Exploiting Multiple Cores with Python — Nick Coghlan's Python Notes 1.0 documentation

https://twitter.com/hynek/status/1228299479528374272 | Hynek Schlawack on Twitter: "About Python Package Metadata: https://t.co/LbTn8LMKmH" / Twitter
https://twitter.com/hynek/status/1231524138357067776 | Hynek Schlawack on Twitter: "Here’s the new canonical home for my post on the current state of Python packaging metadata: https://t.co/zwdtWs2v0H I’ll rewrite the prod one later to have a better flow instead of an update that is longer than the original article. The old URLs will link to the new ones." / Twitter

https://hynek.me/articles/python-in-production/ | Python in Production · Homepage of Hynek Schlawack
https://hynek.micro.blog/2020/02/22/python-in-production.html | Python in Production · Hynek’s Brief Thoughts

https://nedbatchelder.com/blog/202003/functional_strategies_in_python.html
-->

## News and Releases

* [Django News (Jeff and William S. Vincent)](https://django-news.com/) and [Django Store](https://django.threadless.com/)
* [Django Chat Podcast (Carlton Gibson and William S. Vincent)](https://djangochat.com/)

<!--
https://twitter.com/webology/status/1205503566745493505

Podcast
https://twitter.com/di_codes/status/1202697746446245888 | Dustin Ingram on Twitter: "Wow, I have definitely been underestimating the podcast audience. I just discovered that this one interview I did for the @GCPPodcast is one of the most downloaded episodes in the past year. What Python topics would you want to hear about in 2020? https://t.co/3iYXBFcvDG" / Twitter

https://news.python.sc/ | Pythonic News

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
https://www.python.org/doc/versions/

Best Practices
Python on Windows is Okay, Actually
https://us.pycon.org/2019/schedule/presentation/212/
https://www.youtube.com/watch?v=uoI57uMdDD4
https://docs.python.org/3/using/unix.html

https://github.com/python/cpython/tree/master/Misc/NEWS.d

Python versions
https://twitter.com/llanga/status/1232477893210435584 | Łukasz Langa on Twitter: "Python 3.8.2 and 3.9.0a4 are now available. They are quite literally the best Python versions we've ever seen. Go get 'em while they are hot. The one you want in production: https://t.co/Ji0gDx9ZVe And the bleeding edge: https://t.co/rDS29XfbJ9 #python #kangaroo #encyclopaedia" / Twitter
https://twitter.com/llanga/status/1229843838715473920 | Łukasz Langa on Twitter: "#Python 3.8.2rc2 released! It includes a revert for a change to urlparse() that was mistakenly backported to 3.8.1 and caused a fair amount of trouble for third party libraries. If you have a minute, download it and pip install a bunch of your favorites: https://t.co/fwQbmsqCgx https://t.co/pIZingcLw5" / Twitter

Python 3.8.2rc1
https://twitter.com/llanga/status/1227231833844264960
https://twitter.com/eevee/status/1227613322834411522
https://realpython.com/python38-new-features/
https://speakerdeck.com/matrixise/whats-new-in-python-3-dot-8 | What's new in Python 3.8? - Speaker Deck
https://docs.python.org/3.8/whatsnew/3.8.html
https://docs.python.org/3.8/whatsnew/changelog.html#changelog
https://twitter.com/carltongibson/status/1179011386036367362

Release notes
https://docs.python.org/3/whatsnew/
https://docs.python.org/3/whatsnew/3.6.html | What’s New In Python 3.6 — Python 3.8.1 documentation
https://docs.python.org/3/whatsnew/index.html | What’s New in Python — Python 3.8.1 documentation

https://twitter.com/baybryj/status/1184202292729405440 | Ned Deily on Twitter: "Wow! It's the #Python Harvest of Releases Week (and no one expects that)! Yesterday the latest feature release: 3.8.0. Today: 3.7.5 bugfix release. Coming soon: 2.7.17, the penultimate release (you are migrating, right?) and the first 3.9.0 alpha!" / Twitter

https://github.com/pypa/python-manylinux-demo
https://github.com/pypa/manylinux
https://github.com/pypa/manylinux/issues/179 | Tracking issue for manylinux2010 rollout · Issue #179 · pypa/manylinux

https://docs.microsoft.com/en-us/windows/python/ | Python on Windows documentation | Microsoft Docs

https://blog.python.org/2019/12/python-381-376-3610-and-390a2-are-now.html | Python Insider: Python 3.8.1, 3.7.6, 3.6.10, and 3.9.0a2 are now available!
https://discuss.python.org/t/python-3-8-1-3-7-6-3-6-10-and-3-9-0a2-are-now-available/2889 | Python 3.8.1, 3.7.6, 3.6.10, and 3.9.0a2 are now available! - Committers - Discussions on Python.org
https://twitter.com/llanga/status/1207584391494545408 | Łukasz Langa on Twitter: "Why release one version of #Python if you can release four? This merry season, we bring you Python 3.8.1, 3.7.6, 3.6.10, and 3.9.0a2. We hope you'll enjoy them at least as much as we did packaging them! https://t.co/TRqv5mZxk5 #ItsALiving #DontTrifleWithMyAffections" / Twitter
https://twitter.com/raymondh/status/1136076427218964480 | Raymond Hettinger on Twitter: "#Python 3.8 news: The beta release out. Please download it and try out the new features: shared memory multiprocessing, walrus operator, positional-only notation ... Let us know if anything can be made better. But no complaints that it is too fast ;-) https://t.co/9mlvs0luFv"
https://realpython.com/python37-new-features/ | Cool New Features in Python 3.7 – Real Python
-->

## Python 2 or 3, Python 2 EoL

Python 2 End of Life (EOL)
* [Python 2 End of Life (EOL) Python Developer email](https://mail.python.org/pipermail/python-dev/2018-March/152348.html)

Changeset Python 2 Sunsetting Initiative
* [Sunsetting Python 2](https://www.python.org/doc/sunset-python-2/)
* [Sumana Tweet](https://twitter.com/brainwane/status/1176517084890750981)
* [Kickoff for Communications Work on the Python 2 Sunsetting](https://www.harihareswara.net/sumana/2019/08/05/0)

Python 2 EOL Websites
* [Guido van Rossum: "Cool sites about the Python 3 transition"](https://twitter.com/gvanrossum/status/1012462042094002176)
* [Python Clock](https://pythonclock.org)
* [Python 3 Statement](http://python3statement.org)

Django and Python 3
* [Django Packages Python 3](https://www.djangopackages.com/python3)

<!--
Python 2 versus 3
https://twitter.com/chriswilcox47/status/1237444424461766658

Python 3 Post Mortem
https://twitter.com/gvanrossum/status/1216863597562740737

https://www.djangoproject.com/weblog/2019/dec/02/django-3-released/
https://twitter.com/andrewgodwin/status/1201518717588234240

https://twitter.com/webology/status/1196469384253972482 | 🍂 Jeff Triplett 🍂 on Twitter: "🚀 Django 3.0 is expected to launch in December 2019, and RC 1 was released today for anyone who wants to try it out or update your test suites to start testing against it. I recommend updating your projects to note what's changed. https://t.co/nx7QvsUy4R" / Twitter
https://twitter.com/webology/status/1161660263269052422 | ✨ Jeff Triplett ✨ on Twitter: "👇 Keep in mind, that having support for Django 2.0, 2.1, etc does not mean that you have to lose support for Django 1.11. So getting your project ready for Django 2.x does not mean you have to switch from 1.11 until you are ready. You can have both. 
https://t.co/IfmaQr0Oog" / Twitter
https://twitter.com/webology/status/1161644230277828613 | ✨ Jeff Triplett ✨ on Twitter: "🎉 Yesterday, I had the pleasure of upgrading @simplworld's Games API to Django 2.2 and Python 3.7 from Django 1.11 for @WhartonLearning. Since the project is open source, I can share my pull request and you can see what it took. https://t.co/H0yesMbjjC" / Twitter
https://twitter.com/kennethreitz/status/1204348890721456128

PEP 373 -- Python 2.7 Release Schedule
https://www.python.org/dev/peps/pep-0373/
https://wiki.python.org/moin/Python2orPython3
https://twitter.com/webology/status/1212552867225198592 | 🎊 Jeff Triplett 🎉 on Twitter: "🐍 Active development of Python 2.7 has ended, but there will be one final 2.7 release this April. ⛑ It's time to use Python 3 though if you haven't switched yet. https://t.co/wRu728dVrI" / Twitter
https://twitter.com/webology/status/1208057706625548288 | ❄☃ Jeff Triplett 🎄🔔 on Twitter: "It's confusing, but the FINAL Python 2.7 release will be in April 2020. EOL, in this context, means that the 2.7 code will no longer accept changes unless it blocks the final April 2020 release from being released otherwise. https://t.co/dTLA2JmFIs" / Twitter

https://django.readthedocs.io/en/1.7.x/topics/python3.html
https://docs.python.org/3.8/library/2to3.html
https://www.youtube.com/watch?v=klaGx9Q_SOA
https://snarky.ca/my-experience-creating-caniusepython3/
https://pypi.org/project/caniusepython3/

https://twitter.com/ncoghlan_dev/status/1137520803283529728 | Nick Coghlan on Twitter: "This is an excellent post from @hawkieowl on the trade-offs of dropping support for older language versions. Controversial opinion though: if you have a service that has had stable requirements for years, trading runtime inefficiency for ease of code changes is a bad trade-off.… https://t.co/e3xKksW7bq"

Dropping Support
https://docs.pytest.org/en/latest/py27-py34-deprecation.html | Python 2.7 and 3.4 support plan — pytest documentation
https://aws.amazon.com/about-aws/whats-new/2019/11/aws-lambda-now-supports-python-3-8/
https://aws.amazon.com/support
https://forums.aws.amazon.com/forum.jspa?forumID=186
https://palletsprojects.com/blog/ending-python2-support/ | Ending Python 2 Support | The Pallets Projects
https://www.anaconda.com/end-of-life-eol-for-python-2-7-is-coming-are-you-ready/ | End of Life (EOL) for Python 2.7 is coming. Are you ready? - Anaconda
https://twitter.com/pganssle/status/978256523909623809 | Paul Ganssle on Twitter: "For any #python folks who may use python-dateutil in your projects, I'm working out the schedule for dropping Python 2.7 support now. The issue for discussion is here: https://t.co/sWRIhe85qp RT appreciated for visibility (don't want anyone blindsided)"
https://github.com/dateutil/dateutil/issues/653 | Python 2 deprecation schedule · Issue #653 · dateutil/dateutil
https://twitter.com/BokehPlots/status/1138961281480704000 | Bokeh Plot Library on Twitter: "It's a few months out, but the preparations for a Bokeh 2.0 release are already apace. Besides dropping Pyhon 2 support, there will be some other small changes made at the same time. We will lay out everything to expect in this major number bump in a blog post soon.… https://t.co/8KThwKBqtS"
-->

## Related Projects, PSF and DSF People and Members

Python Software Foundation (PSF) People
* [PSF Members](https://www.python.org/psf/members)
* [PSF Fellows](https://www.python.org/psf/fellows)
* [PSF Committees/Workgroups](https://www.python.org/psf/committees)

Django Software Foundation (DSF) People (Not Specifically Developer)
* [DSF Committees](https://www.djangoproject.com/foundation/committees)
* [DSF Individual Members](https://www.djangoproject.com/foundation/individual-members)
* [DSF Corporate Members](https://www.djangoproject.com/foundation/corporate-members)

Django People- Current
* [Django Organization](https://docs.djangoproject.com/en/dev/internals/organization)
* [DSF Developer Members](https://www.djangoproject.com/foundation/developer-members)
* [Django Team List (Old?)](https://www.djangoproject.com/foundation/teams)

Django People- Historical
* [Django Core Developers (Old Version)](https://docs.djangoproject.com/en/1.7/internals/committers/#core-developers)
* [Django Organization Repo People](https://github.com/orgs/django/people)

<!--
https://people.djangoproject.com
-->

## CPython Experts, Mailing Lists, Core Developer Info, Permissions

CPython Experts Index
* [CPython Experts Index](https://devguide.python.org/experts/)

Mailing List and Permissions History
* [Python Core Workflow Mailing List](https://mail.python.org/mailman/listinfo/core-workflow)
* [Permissions History](https://devguide.python.org/developers/#permissions-history)
* [Developer Log](https://github.com/python/devguide/blob/bbd38631554165a64e187bd29815125098159a13/developers.rst)
* [Core Developer Motivations and Affiliations](https://docs.python.org/devguide/motivations.html)
* [Core Developer Office Hours](https://devguide.python.org/help/#office-hour)

## Python Contributing Info and Docs

CPython Bugs Dashboard
* [Bugs](http://bugs.python.org)

CPython
* [CPython GitHub](https://github.com/python/cpython)

CPython Pull Requests
* [CPython Pull Requests](https://github.com/python/cpython/pulls)
* [CPython Commits to Master Branch](https://github.com/python/cpython/commits/master)

Official CPython Contributing Guides
* [CPython Dev Guide](https://devguide.python.org)

Release
* [PEP 537 -- Python 3.7 Release Schedule](https://www.python.org/dev/peps/pep-0537)
* [PEP 429 -- Python 3.4 Release Schedule](https://www.python.org/dev/peps/pep-0429)
* [PEP 373 -- Python 2.7 Release Schedule](https://www.python.org/dev/peps/pep-0373)

Release Managers
* ["Welcome the 3.8 and 3.9 Release Manager - Łukasz Langa!"](https://mail.python.org/pipermail/python-dev/2018-January/151949.html)

Python Status
* ["Status of Python CIs (buildbots, Travis CI, AppVeyor): July 2018"](https://mail.python.org/pipermail/python-dev/2018-July/154703.html)
* [Python Status](https://status.python.org)
* [Python Status History](https://status.python.org/history)
* [CPython Travis CI](https://travis-ci.org/python/cpython/)

CPython Dev Stuff
* [Alternate URL: CPython Dev Guide Read the Docs](http://cpython-devguide.readthedocs.io), and [CPython Dev Guide GitHub](https://github.com/python/devguide)
* [How to Become a Core Developer- Python Developer's Guide](https://devguide.python.org/coredev)
* [PEP 0007 Style Guide for C Code](https://www.python.org/dev/peps/pep-0007)

Victor Stinner CPython Contributing Guides
* [Victor Stinner: Python Development Documentation](https://pythondev.readthedocs.io/)
* [Victor Stinner: "Welcome to Tutorial to contribute to the CPython project’s documentation!"](https://cpython-core-tutorial.readthedocs.io)

Sprint PR Tool
* [Core PR Tool](https://github.com/CuriousLearner/pulls)


<!--
https://python-release-cycle.glitch.me/ | Python Release Cycle

Extended-BNF (EBNF) specification with regular-expression syntax - Google Search

https://devguide.python.org/#contributing
https://devguide.python.org/committing/

https://paper.dropbox.com/doc/Contributing-to-CPython-JlgnduI6kw9MJIaGPpN9G

https://cpython-core-tutorial.readthedocs.io/en/latest/ | Welcome to Tutorial to contribute to the CPython project’s documentation! — Tutorial to contribute to the CPython project 0.0 documentation

https://medium.com/@Captain_Joannah/so-you-want-to-contribute-to-cpython-gather-here-5a2694148ca4 | So, You want to Contribute to Cpython : Gather here !!
https://medium.com/mergify/case-study-cpython-development-workflow-472ae5843188 | Case Study: CPython Development Workflow – mergify – Medium

https://mail.python.org/archives/list/python-dev@python.org/thread/KE7OS4PZASZMFTW2FP2MWZU5R4Q2QZKU/
https://discuss.python.org/t/pep-607-shared-background-for-the-release-cadence-peps/2528?u=steve.dower | PEP 607: Shared background for the release cadence PEPs - PEPs - Discussions on Python.org
PEP 602 -- Annual Release Cycle for Python
https://www.python.org/dev/peps/pep-0602/
https://www.python.org/dev/peps/pep-0602/#the-testing-matrix
PEP 607 -- Reducing CPython's Feature Delivery Latency
https://www.python.org/dev/peps/pep-0607/
PEP 605- Rejected
https://discuss.python.org/t/rejected-pep-605-a-rolling-feature-release-stream-for-cpython/2418

https://mail.python.org/archives/list/python-dev@python.org/thread/YHDDRBEE2LPMBZNKJO5U6ERFIZC7FTIG/ | Mailman 3 Announcing the new Python triage team on GitHub - Python-Dev - python.org

https://devguide.python.org/#quick-reference
https://devguide.python.org/#branchstatus
https://devguide.python.org/#status-of-python-branches | Python Developer’s Guide — Python Developer's Guide
https://devguide.python.org/devcycle.html | 18. Development Cycle — Python Developer's Guide
https://devguide.python.org/devcycle/#indevbranch | 17. Development Cycle — Python Developer's Guide
https://devguide.python.org/devcycle/#maintbranch | 17. Development Cycle — Python Developer's Guide
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
Galaxy
https://twitter.com/webology/status/1226977717364707328

http://pyfound.blogspot.com/2019/05/mariatta-wijaya-lets-use-github-issues.html | Python Software Foundation News: Mariatta Wijaya: Let's Use GitHub Issues Already!
https://medium.com/@Captain_Joannah/cpython-bug-tracker-the-broken-promise-of-the-easy-issue-tag-my-thoughts-c957c1039760 | Cpython Bug Tracker: The broken promise of the Easy issue tag — My thoughts

PyCon DE
https://speakerdeck.com/mariatta/pyconde-2019-keynote | PyConDE 2019 Keynote - Speaker Deck
https://twitter.com/dengun/status/1181977093703421953 | Dengun Group on Twitter: "#PyConDE #PyDataBerlin PEP 581 and PEP 588: Migrating Python’s Issue Tracker by Core Developer Mariatta Wijaya (@mariatta). Interesting and in-depth talk on how the CPython's Issue Tracker process works and it's pain points. https://t.co/CZKanPOev4" / Twitter
https://twitter.com/mariatta/status/1181961785252962305 | Mariatta 🤦 on Twitter: "Thanks @ixek for coming and summarizing my talk 👏😊💜 #PEP581 #PyConDE 🧵⤵️ https://t.co/YroC8PjMxT" / Twitter
https://twitter.com/mariatta/status/1188177179630157824
https://de.pycon.org/program/pyconde-dfcu3k-pep-581-and-pep-588-migrating-cpython-s-issue-tracker-mariatta-wijaya | 404 Not Found
https://twitter.com/mariatta/status/1166538642308747264 | Tweet / Twitter


https://www.python.org/dev/buildbot/

https://github.com/python/bedevere
https://github.com/python/the-knights-who-say-ni | python/the-knights-who-say-ni: CLA enforcement bot for Python organization projects

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

## Python Performance, Speed, and Security

Security
* [OpenSSL](https://www.openssl.org/)
* [Python Security](https://python-security.readthedocs.io/)

Speed
* [Python Speed Center](https://speed.python.org/)

<!--
https://github.com/vstinner/pysandbox/

speed.python.org
https://hackernoon.com/which-is-the-fastest-version-of-python-2ae7c61a6b2b

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
-->

## CPython Helpers

Regression Test Suite For Python Core Developers
* [Regression Test Suite](https://docs.python.org/3/library/test.html)
* [test.support — Utilities for the Python test suite](https://docs.python.org/3/library/test.html#module-test.support)

Disassember
* [Disassembler Wikipedia](https://en.wikipedia.org/wiki/Disassembler)

<!--
Failed Optimization
https://twitter.com/VictorStinner/status/1163465586866905088 | Victor Stinner 🐍 on Twitter: "I wrote a long email about my different Python optimization projects (registervm, FAT Python, pyperf, ...), why they failed https://t.co/xLqlltsB0n and my advices to optimize Python in 2019: &gt; New PyHandle C API &gt; Tracing garbage collector for CPython &gt; CPython subinterpreters" / Twitter
https://mail.python.org/pipermail/python-dev/2018-May/153296.html | [Python-Dev] Python startup time

https://twitter.com/VictorStinner/status/1150703344119427072 | Victor Stinner 🐍 on Twitter: "Video my keynote "Python Performance: Past, Present, Future": https://t.co/cFAyw3XoaW (9h video, link to the start of the my talk, at 31:15)… https://t.co/iwxRcjwqun"
https://twitter.com/VictorStinner/status/1149625666809155589 | Victor Stinner 🐍 on Twitter: "My keynote slides: Python Performance: Past, Present and Future https://t.co/0m8923itpt Many previous optimization projects failed; Cython, multiprocessing and Numba are working well to make your code faster; PyHandle, tracing GC and subinterpreters are very promising #EuroPython… https://t.co/21jAlxb7v8"

https://github.com/python/pyperformance/blob/master/README.rst | performance/README.rst at master · python/performance
https://github.com/python/pyperformance | python/pyperformance: Python Performance Benchmark Suite

https://docs.python.org/3/library/os.html | os — Miscellaneous operating system interfaces — Python 3.7.4rc2 documentation
https://docs.python.org/3/reference/datamodel.html | 3. Data model — Python 3.7.4rc2 documentation
https://docs.python.org/3/reference/executionmodel.html | 4. Execution model — Python 3.7.4rc2 documentation

https://docs.python.org/3/library/dis.html | dis — Disassembler for Python bytecode — Python 3.7.4rc2 documentation
https://docs.python.org/3/library/dis.html#dis.Instruction | dis — Disassembler for Python bytecode — Python 3.7.4rc2 documentation

https://docs.python.org/3/library/inspect.html	
		
2. Using the Python Interpreter	

https://speakerdeck.com/tiran/europython-2019-introduction-to-low-level-profiling-and-tracing | EuroPython 2019: Introduction to low-level profiling and tracing - Speaker Deck
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

<!--
https://twitter.com/ncoghlan_dev/status/1164868943493791744 | Nick Coghlan on Twitter: "Current GitHub language stats for the main CPython repo: * Python 63.9% * C 28.9% * Objective-C 4.4% * C++ 1.2% * HTML 0.4% * M4 0.4% * Other 0.8% The autoconf scripts are large enough to make it onto the list :)" / Twitter

http://devdocs.io/python~3.6/ | DevDocs — Python 3.6 documentation

https://github.com/pyladies/pyladies-maintainers | pyladies/pyladies-maintainers: PyLadies resources for open source project maintainers, core developers (including CPython), and aspiring project maintainers and core developers.
https://github.com/pyladies/pyladies-maintainers/tree/master/cpython | pyladies-maintainers/cpython at master · pyladies/pyladies-maintainers

https://pythondev.readthedocs.io/internals.html

Moshe
https://cobordism.com/
https://github.com/moshez/big-bad-loop
https://www.youtube.com/watch?v=2WdjlznbD0o&feature=youtu.be&t=9228\
https://2019.northbaypython.org/schedule/presentation/10/

A Bit About Bytes
https://www.youtube.com/watch?v=cSSpnq362Bk
https://docs.python.org/3/library/dis.html
https://github.com/python/cpython/blob/master/Python/ceval.c
-->

Visualizing How Python Works  		
* [Python Tutor](http://pythontutor.com)

CPython Source Code Guide
* [CPython Source Code Guide](https://realpython.com/cpython-source-code-guide)

PyLadies CPython Source Code Resource Issue
* [PyLadies CPython Source Code Resource Issue](https://github.com/pyladies/pyladies-maintainers/issues/6 )

Yet another guided tour of CPython
* [Yet another guided tour of CPython](https://paper.dropbox.com/doc/Yet-another-guided-tour-of-CPython--Aa3JxpUCv8jV2bO0P8tDYiBzAg-XY7KgFGn88zMNivGJ4Jzv)

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

Python Virtual Machine
* [Inside the Python Virtual Machine](https://leanpub.com/insidethepythonvirtualmachine/read)

Python Internals
* [Stack Overflow Python Internals Questions Sorted by Votes](https://stackoverflow.com/questions/tagged/python-internals?sort=votes)

<!--
https://2020.pycascades.com/talks/cpython-internals-whos-afraid-of-the-big-bad-loop/ | CPython Internals: Who's Afraid of the Big Bad Loop? — PyCascades 2020 – Portland, Oregon
https://www.youtube.com/watch?v=2WdjlznbD0o&feature=youtu.be&t=9228%5C | PyCascades 2020: Day 2 - YouTube

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
https://en.wikipedia.org/wiki/Compilers:_Principles,_Techniques,_and_Tools

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

## Parsers

PEG Parser
* [Guido van Rossum: PEG Parsing Series](https://medium.com/@gvanrossum_83706/peg-parsing-series-de5d41b2ed60)

Types of Parsers
* [LL Parser Wikipedia](https://en.wikipedia.org/wiki/LL_parser)
* [Top-Down Parsing Wikipedia](https://en.wikipedia.org/wiki/Top-down_parsing)
* [Parsing Expression Grammar Wikipedia](https://en.wikipedia.org/wiki/Parsing_expression_grammar)

<!--
https://twitter.com/gvanrossum/status/1237020095341182981

https://medium.com/@gvanrossum_83706/peg-at-the-core-developer-sprint-8b23677b91e6

https://github.com/gvanrossum/pegen
https://github.com/gvanrossum/ctok | gvanrossum/ctok: Expose CPython's tokenizer as a Python class
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
Core Dev Sprint
http://pyfound.blogspot.com/2019/10/cpython-core-developer-sprint-2019.html
https://twitter.com/ThePSF/status/1189620494028460038
https://www.youtube.com/watch?time_continue=2&v=NKmy_Cnt3pM
https://twitter.com/llanga/status/1189611164860407808
https://twitter.com/gvanrossum/status/1190099807722852352

https://pyfound.blogspot.com/2019/06/python-language-summit-lightning-talks-part-2.html | Python Software Foundation News: Python Language Summit Lightning Talks, Part 2

http://pycon.blogspot.com/2016/05/how-to-get-ready-for-pycon-development.html
-->

Python Sprints
* [Python Sprints](https://python-sprints.github.io)

<!--
https://wiki.python.org/moin/EuroPython2018/CPython | EuroPython2018/CPython - Python Wiki
-->

## CPython and Django Docs

CPython Docs
* [About These Documents](https://docs.python.org/3/about.html)

Django Docs
* [Writing Documentation](https://docs.djangoproject.com/en/dev/internals/contributing/writing-documentation/)
* [Writing Documentation: How Documentation is Organized](https://docs.djangoproject.com/en/dev/internals/contributing/writing-documentation/#how-the-documentation-is-organized)

<!--
Python Docs Theme
https://twitter.com/mariatta/status/1217180209176166400
https://github.com/python/python-docs-theme/commits/master

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

<!--
Rackspace
https://mobile.twitter.com/kantrn/status/1225863584569102338

Carlton Talk
DjangoCon 2019 - Using Django as a Micro-Framework: Hacking on the HTTP handlers.. by Carlton Gibson
https://www.youtube.com/watch?v=w9cYEovduWI&t=634s
https://github.com/wsvincent/django-microframework
https://twitter.com/glasnt/status/1176980071665455104

https://forum.djangoproject.com/latest | Latest topics - Django Forum
https://twitter.com/andrewgodwin/status/1184156750284382209 | Andrew Godwin on Twitter: "Now the Django Forum has funding, we have links to it in the docs too! Only thing left is to get it onto https://t.co/8mbGtcVsAG, if anyone feels like getting a PR going :)" / Twitter

Django Mentored Sprint
https://twitter.com/carltongibson/status/1119632462357905408 | Carlton Gibson on Twitter: "Ah, this is what I need. This is such a good idea. Just sprinted at @DjangoConEurope without it. Was dearly missed. Totally going to try and copy it for @djangocon... super 🤹🏼‍♀️🕺… 
https://t.co/XhmAKJbJks"
https://twitter.com/carltongibson/status/1102298036196294656 | Carlton Gibson on Twitter: "Yeah, me too. "Smooth the on-ramp" is my motto for the year. We'll get there. ✊… "
-->

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
https://django-release-cycle.glitch.me/
https://twitter.com/webology/status/1235628234148110336

Django 1.11 EoL
https://twitter.com/webology/status/1235288399654907904
https://twitter.com/carltongibson/status/1235222028703199234

Django 1.4
https://twitter.com/hynek/status/1189556183515963392

https://github.com/django/django/tree/master/docs/internals
http://www.sphinx-doc.org/en/master/usage/restructuredtext/index.html#rst-index
https://code.djangoproject.com/ticket/30010
https://code.djangoproject.com/query
https://docs.djangoproject.com/en/dev/internals/contributing/writing-code/submitting-patches/
https://docs.djangoproject.com/en/dev/internals/contributing/committing-code/#committing-guidelines
https://docs.djangoproject.com/en/dev/internals/contributing/triaging-tickets/#needs-documentation
https://docs.djangoproject.com/en/2.2/internals/contributing/new-contributors/#first-steps
https://code.djangoproject.com/wiki/Version3.1Roadmap
https://docs.djangoproject.com/en/2.2/topics/testing/overview/
https://docs.djangoproject.com/en/dev/internals/contributing/writing-code/submitting-patches/#patch-review-checklist

https://forum.djangoproject.com/t/should-django-do-google-code-in/355 | Should Django do Google Code-in? - Django Internals / Mentorship - Django Forum
https://twitter.com/carltongibson/status/1184155612353122306 | Carlton Gibson on Twitter: "@laymonage @djangoproject @AdamChainz @MariuszFelisiak @_rami_ Looks good. Issue is mentoring capacity… I shall enquire. Thanks." / Twitter

https://github.com/django/django-docker-box | django/django-docker-box: Run the Django test suite across all supported databases and python versions
https://tomforb.es/django-docker-box-is-now-an-official-django-project/ | Django Docker Box is now an official Django project! | Tom Forbes

Django sprint
https://github.com/carltongibson/dcus2019sprints
https://twitter.com/KatiMichel/status/1177419622389125120
https://twitter.com/carltongibson/status/1177987774785306624

"Really liking the "How to Contribute to Django" workshop led by @carltongibson
this morning at the first day of #DjangoCon sprints. Large group of people sharing knowledge and troubleshooting together. Simplified a process that could be daunting for a lot of people."
https://twitter.com/KatiMichel/status/1177281890086092805

https://twitter.com/andrewgodwin/status/1240357729174052866
https://github.com/django/django/commit/fc0fa72ff4cdbf5861a366e31cb8bbacd44da22d
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

## Django- General

Django Project Governance Model
* [New Django Project Governance Model](https://www.djangoproject.com/weblog/2020/mar/12/governance/)
* [Django Project Governance Model (Jacob Kaplan-Moss)](https://jacobian.org/2020/mar/12/django-governance/)

<!--
https://twitter.com/andrewgodwin/status/1238135085817184258
https://twitter.com/JamieXML/status/1238301461026660352
-->

Django Triage & Review Team
* [Django: Creating a new "Triage & Review Team"](https://groups.google.com/forum/#!topic/django-developers/mUBWlG0-Jbw/discussion)

Carlton Gibson's Talks
* [Carlton Gibson: Your Framework Needs You (DjangoCon US 2018](https://2018.djangocon.us/talk/your-web-framework-needs-you)
* [Carlton Gibson: Feeding the Pony: Contributing back to Django & How to make that work for you DjangoCon Europe 2019](https://2019.djangocon.eu/talks/feeding-the-pony-contributing-back-to-django-how-t/)

<!--
https://2018.djangocontent.eu/hd/talk/MUAVUD/ | Growing old gracefully: on being a career programmer. :: DjangoCon Europe 2018 :: pretalx

https://www.youtube.com/watch?time_continue=4&v=xlbxa3rw5cw
"@rixxtr says the first step to contributing to Django: acquire a ticket. Except... there are currently 1300 tickets and you click "view tickets" not "search" #PyConAU"
https://twitter.com/weatheredpup/status/1157171428904488961
-->

Process of Dissolving Django Core
* [James Bennett: Core No More](https://www.b-list.org/weblog/2018/nov/20/core)
* [Django DEP: Add draft DEP dissolving Django core. by ubernostrum](https://github.com/django/deps/pull/47)
* [Rough draft Django DEP: Dissolving Django Core](https://github.com/django/deps/blob/master/draft/0010-new-governance.rst)
* [Draft proposal: dissolving "Django core" - Google Groups](https://groups.google.com/forum/#!topic/dsf-members/yqnWGII63mI)
* [On the Django core team - Google Groups](https://groups.google.com/forum/#!topic/dsf-members/GWOzvsOAGUs)

<!--
https://github.com/django/djangoproject.com/pull/912 | add docker for local development by mjhea0 · Pull Request #912 · django/djangoproject.com
-->

Django Foundation

<!--
https://twitter.com/webology/status/1230232028978798592 | ✨ Jeff Triplett ✨ on Twitter: "🎧 Interesting insights into the @djangoproject's Foundation side. https://t.co/Ngsb2sMxkz" / Twitter
https://wsvincent.com/how-django-works-behind-the-scenes/ | How Django Works Behind the Scenes - William Vincent
https://www.djangoproject.com/fundraising/#fellowship-program
-->

DSF Internship
* [DSF Internship](https://www.djangoproject.com/weblog/2019/apr/24/internship-opportunity-dsf-app/)

## Python Governance

<!--
PSF

Ewa
https://www.youtube.com/watch?v=J-B_kthDhCU | Ewa Jodlowska: Our stories - Keynote - YouTube
https://twitter.com/TerraMeijar/status/1189487136115957761

PSF Board Elections
https://twitter.com/marlene_zw/status/1127330663428845569 | Marlene Mhangami on Twitter: "This is a super helpful thread for anyone interested in the PSF board elections. I’m up for re-election this year! Happy to answer any questions or help anyone with the process of nomination etc. 😊… https://t.co/rC8Fv61OFm"

https://www.python.org/nominations/elections/2019-python-software-foundation-board/nominees/jannis-leidel/ | Nomination for | Python.org

Elections
https://twitter.com/di_codes/status/1137014831805095937
https://www.python.org/nominations/elections/ | Elections | Python.org
https://www.python.org/nominations/elections/2019-python-software-foundation-board/nominees/ | Nomination for | Python.org
https://www.youtube.com/watch?v=sORneSQNOmc&feature=youtu.be | (1) python.org self nomination demonstration - YouTube
https://wiki.python.org/moin/PythonSoftwareFoundation | PythonSoftwareFoundation - Python Wiki
-->

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
http://www.holovaty.com/writing/bdfls-retiring/
https://mail.python.org/mm3/archives/list/distutils-sig@python.org/thread/QT7SKORCF6OKWO3OVP5KO6XNGU2AR6TU/ | Mailman 3 Handing over default BDFL-Delegate responsibilities for packaging interoperability PEPs to Paul Moore - Distutils-SIG - python.org

Steering Council
https://discuss.python.org/t/steering-council-nomination-pablo-galindo-salgado-2020-term/2667 | Steering Council Nomination: Pablo Galindo Salgado (2020 Term) - Users / Steering Council Nominations - Discussions on Python.org
https://github.com/python/peps/pull/1242/files | PEP 8101: Update nominees by ewdurbin · Pull Request #1242 · python/peps
https://twitter.com/WillingCarol/status/1206649187212955649 | Carol Willing on Twitter: "Thanks to @gvanrossum and @ncoghlan_dev for serving on the inaugural Steering Council (and for your mentorship over the years) A big thanks to all who stood for the election and your ongoing impact on Python. Congrats @Yhg1s @VictorStinner @pumpichank and @brettsky 🐍💐 https://t.co/qOh0BhfdAc" / Twitter
https://twitter.com/jacobian/status/1206700267187650560 | jacobian on Twitter: "Burying the lede here a little bit: GvR's no longer on the steering committee. So for the first time in Python's history Guido has no (formal) power on the project. From one ex-BDFL to another: congrats on getting out before the "for life" clause had to kick in! https://t.co/McMX9VM0ri" / Twitter

Steering Council
https://snarky.ca/what-its-like-to-be-on-the-python-steering-council/
https://discuss.python.org/t/steering-council-nomination-brett-cannon-2020-term/2566
https://twitter.com/brettsky/status/1188268846840369152

https://twitter.com/llanga/status/1156568264396419073 | Łukasz Langa on Twitter: "@zooba Well, the Steering Council can *and should* set a roadmap for Python's next decade. I'm talking about it in my keynote. But what not even the SC can do is tell a group of people to *abandon* a particular use case. For example, imagine they told MicroPython to drop their project." / Twitter
https://twitter.com/brettsky/status/1156684427486879745 | Brett Cannon on Twitter: "@zooba I would love to do it as well, but without staff to help make those plans happen the best we can offer is the vision document we're working on to try to coax ppl in a certain direction along with a longer time horizon to compensate for volunteer (un)availability" / Twitter
https://github.com/rust-lang/rfcs/blob/master/text/2657-roadmap-2019.md | rfcs/2657-roadmap-2019.md at master · rust-lang/rfcs

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
https://twitter.com/llanga/status/1188968251918819329
https://twitter.com/llanga/status/1001919374716948480 | Łukasz Langa on Twitter: "If you are really attached to your string quotes and that attachment was the one thing blocking you from adopting Black, the uncompromising #python code formatter, look here: https://t.co/q3QhYBeiru (Note that Black's recommendation on the matter doesn't change.)"
https://github.com/ambv/black/commit/8ebbd268880f15834b70910a6dc61e1ee7596b7c | Add --skip-string-normalization · ambv/black@8ebbd26
https://twitter.com/llanga/status/1153417052302053378
https://twitter.com/llanga/status/1153417050024550401
-->

## python.org and djangoproject.com Contributing

python.org Contributing
* [python.org](https://www.python.org)
* [python.org GitHub](https://github.com/python/pythondotorg)
* [python.org Issues](https://github.com/python/pythondotorg/issues)
* [python.org Staging](https://staging.python.org)
* [python.org Read the Docs](https://pythondotorg.readthedocs.io)
* [python.org Read the Docs Install](https://pythondotorg.readthedocs.io/install.html) and [python.org Read the Docs Contributing](https://pythondotorg.readthedocs.io/contributing.html)
* [Couldn't set up local environment](https://github.com/python/pythondotorg/issues/987)
* [python.org Contributors](https://github.com/python/pythondotorg/graphs/contributors)

djangoproject.com Contributing
* [djangoproject.com](https://www.djangoproject.com)
* [djangoproject.com GitHub](https://github.com/django/djangoproject.com)

<!--
* [Django Project Trac](https://github.com/django/code.djangoproject.com)
-->
