Getting Started With ODK
=========================

This document walks you through a very basic setup process,
to get you familiar with using Open Data Kit.

You will:

.. contents::
 :local:

.. _getting-started-install-collect:

Install Collect
---------------------

The easiest way to install the Collect App is `to get it from the Google Play store <https://play.google.com/store/apps/details?id=org.odk.collect.android&hl=en>`_.

.. seealso:: :doc:`collect-install`

.. _getting-started-install-aggregate:

Install Aggregate (optional)
------------------------------

The easiest way to set up Aggregate is to
:doc:`install it on Google App engine <aggregate-app-engine>`. 

You'll set up a new Google Cloud project, and then run the install utility locally. This will connect to your Google Cloud account and install Aggregate there.

Alternatively, if you just want to try things out,
you can use the `Aggregate demo server`_.

.. _Aggregate demo server: https://opendatakit.appspot.com

.. seealso:: :doc:`aggregate-install`

.. _getting-started-create-form:

Create a form with Build and upload it to Aggregate
------------------------------------------------------

The quickest and easiest way to start using your own survey forms is to create one online with `ODK Build <https://build.opendatakit.org/>`_.

#. Go to `build.opendatakit.org <https://build.opendatakit.org/>`_, create a new account, and log in. Once logged in, a blank survey is created. 
#. Give your form a name (:guilabel:`rename` in the upper left-hand corner).
#. Add a few questions (click on question types in the :guilabel:`+Add New` bar along the bottom).
#. Once your new form is complete, go to :menuselection:`File --> Upload form to Aggregate...` to upload your form.


.. seealso::
  
  `Build desktop app <https://opendatakit.org/downloads/download-category/build/>`_
    To use Build locally.

  `XLSForm <http://xlsform.org/>`_
    A more robust form creation tool.
  
    
.. _getting-started-load-form:

Load a form into Collect from Aggregate
----------------------------------------------------------

#. Open Collect on your Android device.
#. Open server settings 
   (:menuselection:`⋮ --> General Settings --> Server`).
#. Edit the server settings to connect to your Aggregate server or the demo server.
#. Go back to the app home screen and select :guilabel:`Get Blank Form`, then select your form.


.. _getting-started-fill-form:

Fill out a form and upload it to Aggregate
-------------------------------------------

#. Select :guilabel:`Fill Blank Form` to complete a survey.
#. Select :guilabel:`Send Finalized Form` to upload your completed survey to Aggregate.


Now log back into Aggregate instance and see your completed survey results.
