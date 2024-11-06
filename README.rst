.. image:: https://img.shields.io/badge/sitcomtn--146-lsst.io-brightgreen.svg
   :target: https://sitcomtn-146.lsst.io
.. image:: https://github.com/lsst-sitcom/sitcomtn-146/workflows/CI/badge.svg
   :target: https://github.com/lsst-sitcom/sitcomtn-146/actions/

####################################################
WET-007 analysis of WET-001 simulation of LsstComCam
####################################################

SITCOMTN-146
============

Comparison of WEP fit between TIE and Danish

**Links:**

- Publication URL: https://sitcomtn-146.lsst.io
- Alternative editions: https://sitcomtn-146.lsst.io/v
- GitHub repository: https://github.com/lsst-sitcom/sitcomtn-146
- Build system: https://github.com/lsst-sitcom/sitcomtn-146/actions/


Build this technical note
=========================

You can clone this repository and build the technote locally if your system has Python 3.11 or later:

.. code-block:: bash

   git clone https://github.com/lsst-sitcom/sitcomtn-146
   cd sitcomtn-146
   make init
   make html

Repeat the ``make html`` command to rebuild the technote after making changes.
If you need to delete any intermediate files for a clean build, run ``make clean``.

The built technote is located at ``_build/html/index.html``.

Publishing changes to the web
=============================

This technote is published to https://sitcomtn-146.lsst.io whenever you push changes to the ``main`` branch on GitHub.
When you push changes to a another branch, a preview of the technote is published to https://sitcomtn-146.lsst.io/v.

Editing this technical note
===========================

The main content of this technote is in ``index.rst`` (a reStructuredText file).
Metadata and configuration is in the ``technote.toml`` file.
For guidance on creating content and information about specifying metadata and configuration, see the Documenteer documentation: https://documenteer.lsst.io/technotes.
