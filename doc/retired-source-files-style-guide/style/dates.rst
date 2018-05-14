.. _dates:

=====
Dates
=====

Dates are displayed differently in different countries, so you must use
a date format that's explicit and consistent and that global users
can't misinterpret.

Unless space is limited, always show dates in the following format:
*month day*, *year*. Always spell out the month.

.. list-table::
   :widths: 50 50
   :header-rows: 1

   * - Use
     - Avoid
   * - November 12, 2017
     - 12 Nov 2017

       2017-Nov-12

       11/12/2017

       11/12/17

       12/11/17

       10-11-17

.. note::

   Don't use ordinal numbers for dates. For example, don't use
   *January 1st*; use *January 1* instead.

When the month, day, and year are embedded in a sentence, use a comma
before and after the year. When only the month and year are embedded in
a sentence, omit the commas unless the syntax would ordinarily require a
comma following the year.

.. list-table::
   :widths: 100
   :header-rows: 1

   * - Use
   * - Any sites that are using MySQL 4 after November 1, 2017, will be
       automatically migrated to MySQL 5.
   * - The Alert Logic Security Research Team used 12 months of security event
       data captured from July 2016 through June 2017.
   * - As of September 2017, a subset of customer accounts weren't being
       billed for actual usage in comparison to their preselected SQL Server
       storage allocations.

Use an all-numeric date only in the following situations:

- Space is limited, as in a table or figure.
- You need to show a literal representation of the date as it's displayed
  in the software.

Because all-numeric dates are interpreted differently in different
countries, explain the format of a numeric date, and use a consistent
format throughout the documentation. If possible, use the ISO 8601
format, which is *yyyy*-*mm*-*dd* (for example, 2017-11-10 for November
10, 2017).

.. list-table::
   :widths: 100
   :header-rows: 1

   * - Use
   * - The value that's shown for 8/19/10 represents the average number of
       extents from data collections beginning August 19, 2017.

For information about and examples for showing a date range, see
:ref:`ranges-of-numbers`.
