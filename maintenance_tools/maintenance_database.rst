.. meta::
   :description: digiKam Maintenance Tool Database Cleaning
   :keywords: digiKam, documentation, user manual, photo management, open source, free, learn, easy, maintenance, database, cleanup, Shrink

.. metadata-placeholder

   :authors: - digiKam Team

   :license: see Credits and License page for details (https://docs.digikam.org/en/credits_license.html)

.. _maintenance_database:

Database Cleaning
=================

.. contents::

.. figure:: images/maintenance_database_cleaning.webp
    :alt:
    :align: center

    The digiKam Maintenance Database Options

This process will analysis your database files to consolidate the contents. The Core database is always cleaned. You can select additional databases for cleaning by selecting one of the extra options listed below:

    - **Cleanup the Thumbnails database**.

    - **Cleanup the Faces database**.

    - **Cleanup the Similarity database**.

    - **Shrink all databases** to ensure de-fragmentation and just keeps the database small.

.. note::

   The last option leads to the vacuuming (shrinking) of the databases. Vacuuming is supported both for SQLite and MySQL.

While the scan for new items process is under progress, as the process may take much time and digiKam cannot be used, a non modal dialog appear to make sure that no database corruption occurs.

.. figure:: images/maintenance_database_process.webp
    :alt:
    :align: center

    The digiKam Database process Working in the Background.
