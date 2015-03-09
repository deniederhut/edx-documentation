####################################
edX Analytics
####################################

******************
March 10, 2015
******************

The tracking logs in daily data packages now include additional events for
actions completed using the edX mobile app. 

* The edX mobile app for iOS now emits ``play_video``, ``pause_video``,
  ``stop_video``, ``load_video``, and ``seek_video`` events.

* The edX mobile app for Android now emits ``seek_video`` events in addition to
  other video interaction events. 

For more information, see the `Video Interaction Events`_ section of the `edX
Research Guide`_.

******************
March 5, 2015
******************

* Data packages now include the following events. For more information, see
  the `Tracking Logs`_ chapter in the `edX Research Guide`_.

  * Events that record when learners view the contents of a Google Calendar or
    Google Drive component in the LMS.

  * Events that record new posts, responses, and comments in course
    discussions.

******************
February 23, 2015
******************

Events in the data package now include data from two HTTP header fields,
``referer`` and ``accept_language``.

******************
February 12, 2015
******************

* The ``context`` field for server events now provides a ``usage_key`` to
  identify XBlock content. The ``usage_key`` member field was added to the
  ``module`` dictionary, which also provides the component ``display_name``, on
  28 Jan 2015.

  For more information, see the `Tracking Logs`_ chapter in the `edX Research
  Guide`_.

******************
January 28, 2015
******************

Data packages now include a .csv file of the email preference that each learner
supplies when they enroll in your institution's courses on edx.org. The file
includes data collected across all of an institution's edx.org courses. For
more information, see `Email Opt In Report`_ in the `edX Research Guide`_.

.. _Analytics January 8, 2015:

***************
January 8, 2015
***************

* In early November 2014, an error was introduced that prevented events from
  being generated for open assessment problems. This error has been corrected.

* Also see mobile updates for :ref:`Mobile January 8, 2015`.

.. include:: ../links.rst