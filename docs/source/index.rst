.. lookit-api documentation master file, created by
   sphinx-quickstart on Wed Sep  6 09:57:34 2017.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to Lookit's documentation!
==========================================

Use the table of contents at the left to navigate. Here you will find information about how to use Lookit to conduct developmental research, as well as how to contribute to the codebase. If you are looking for non-technical information like how to recruit partipants or when the platform will be available for general use, see `the wiki <https://github.com/lookit/research-resources/wiki>`_.

What is Lookit?
----------------
Lookit is an online platform for developmental research. Families can sign up or log in, provide some basic information about their children, and then take part in studies from a variety of labs when it's convenient for them. There's no videoconferencing or scheduling: parents and children simply do activities in the web browser, and information about the session (e.g., survey responses, timing, condition assignment) along with webcam video of the session is sent to the Lookit server. Lookit can be used to collect looking measures from preverbal children as well as verbal responses, pointing, etc. from older children. Researchers can design, test, and manage their studies on the platform, including contacting participants; common tasks such as checking for informed verbal consent before accessing any data from a session are built into the Lookit research workflow. Families may take part in studies from multiple labs over time. Having one central platform allows families to access many interesting studies for all the children in their family in one place, and researchers benefit from economies of scale in software development and recruitment. 

Overview of Lookit code
------------------------

The `Lookit codebase <https://github.com/lookit/>`_ has been jointly developed by MIT and the `Center for Open Science <https://cos.io/>`_. All of it is open-source (MIT License). It contains two main repositories:

* `lookit-api <https://github.com/lookit/lookit-api>`_, a Django application that houses  functionality for both participants and researchers. Participants can log in, take part in studies with their children, and view their past responses; researchers can design, administer, and download data from their studies.

* `ember-lookit-frameplayer <https://github.com/lookit/ember-lookit-frameplayer>`_, an Ember app that runs the actual studies in the web browser

The documentation you are reading now lives in `lookit-docs <https://github.com/lookit/lookit-docs>`_.

Contents:

.. toctree::
   :maxdepth: 4
   :hidden:

   researchers
   
   tutorial
   
   frame-dev
   
   install-django-project
   install-ember-app
   
   implementation
   
   contributor-guidelines
   
   definitions
   
   cds-participants
