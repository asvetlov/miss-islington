miss-islington
==============

🐍🍒⛏🤖

Bot for backporting `CPython <https://github.com/python/cpython/>`_ Pull Requests.

miss-islington requires Python 3.6. Python 3.7 is not yet supported.


Backporting a PR on CPython
===========================

Prior to merging a PR, a Python core developer should apply the
``needs backport to X.Y`` label to the pull request.
Once the pull request has been merged, `@miss-islington <https://github.com/miss-islington>`_
will prepare the backport PR.

If `@miss-islington <https://github.com/miss-islington>`_ encountered any issue while backporting,
it will leave a comment about it. The PR then needs to be backported manually.


Merging the Backport PR
=======================

If a Python core developer approved the backport PR made by miss-islington, it will be
automatically merged once all the CI checks passed.

**Aside**: where does the name come from?
=========================================

According to Wikipedia, Miss Islington is the name of the witch in the
`Monty Python and the Holy Grail <https://www.youtube.com/watch?v=k3jt5ibfRzw&feature=youtu.be>`_
sketch.
