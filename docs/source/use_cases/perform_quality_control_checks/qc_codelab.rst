Perform Quality Control on Variants
===================================

.. comment: begin: goto-read-the-docs

.. container:: visible-only-on-github

   +-----------------------------------------------------------------------------------+
   | **The properly rendered version of this document can be found at Read The Docs.** |
   |                                                                                   |
   | **If you are reading this on github, you should instead click** `here`__.         |
   +-----------------------------------------------------------------------------------+

.. _RenderedVersion: http://googlegenomics.readthedocs.org/en/latest/use_cases/perform_quality_control_checks/qc_codelab.html

__ RenderedVersion_

.. comment: end: goto-read-the-docs

There are a collection of quality control checks for variants documented in codelab `Quality Control using Google Genomics`_.

These methods were co-developed with researchers working on the Million Veterans Program data. For more detail, please see `the paper <http://biorxiv.org/content/early/2015/12/24/035295>`__ and `diagram of their full pipeline <https://github.com/StanfordBioinformatics/mvp_aaa_codelabs/blob/master/README.md>`__ with some additional quality control checks on `github <https://github.com/StanfordBioinformatics/mvp_aaa_codelabs>`__.

To make use of this codelab upon your own data:

(1) First, load your data into Google Genomics and export your variants to BigQuery.  See `Load Genomic Variants`_ for more detail as to how to do this.
(2) Each section of `the codelab <https://github.com/googlegenomics/codelabs/tree/master/R/PlatinumGenomes-QC>`_ discusses how to run that part on your own data.  For example, update the BigQuery table name in `Part 1: Data Overview <https://github.com/googlegenomics/codelabs/blob/master/R/PlatinumGenomes-QC/Data-Overview.md#variants>`_
