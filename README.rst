Overview
========

This repository provides an ansible role to install the useful ag defaults
described here_.

.. _here: http://shuttlethread.com/blog/useful-ack-defaults

Installation
------------

To provision :code:`localhost`, clone this repo and run the provided script::

    git clone --recursive https://github.com/ericcrosson/ansible-silversearcher-ag
    cd ansible-silversearcher-ag
    ./run.sh

Use
---

To invoke the silversearcher, use the provided :code:`ag` wrapper::

    cd search-dir
    ag search-terms

Acknowledgements
----------------

Thanks to Jamie Lentin for his initial post_ on shuttlethread.com.

Thanks to Geoff Greer for `the silver searcher`_.

.. _post: http://shuttlethread.com/blog/useful-ack-defaults
.. _the silver searcher: https://github.com/ggreer/the_silver_searcher
