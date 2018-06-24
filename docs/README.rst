********************
Smriti Documentation
********************

This documentation consists of the flow of the entire codebase of the Smriti.


Installing Modules
===================
Navigate to the root directory of the project where app.js is located
using ``cd`` and run below command to install all the required modules::

   >> cd smriti/

   >> npm install


Running the Web-app
===========================
We have set two environment for the entire codebase following as:

-   ``Development`` (Used in development phase)

-   ``Production`` (Used in Live mode)

These two environment are implemented in ``config`` directory. 

Running Front-end Server
~~~~~~~~~~~~~~~~~~~~~~~~~

To run the front-end part of the web app in development mode use command 
in the root directory where app.js is located:

.. code:: bash

   NODE_ENV=development nodemon app.js

Running Back-end Server
~~~~~~~~~~~~~~~~~~~~~~~~

To run the back-end part of the web app in the same mode, run the Flask_API
notebook file in the localhost using:

.. code:: bash

   nohup jupyter notebook

This will run the jupyter notebook in your localhost, then navigate to the
flask_api directory and run the flask_api_smriti notebook file to start the 
backend server, which will run on port #3300 and will look something like
this, in the web browser:

.. code:: bash

   http://localhost:8888/notebooks/smriti_raghuvar/flask_api/Flask_API_Smriti_Review.ipynb


Used Tools & Frameworks
===========================

We have used following tools and framworks to implement end-to-end product.

Languages
~~~~~~~~~~~~~~~

For Front-end:
~~~~~~~~~~~~~~~

-   `HTML & CSS`
-   `JQuery`
-   `JavsScript`
-   `Pug (Template engine for NodeJs)`

For Back-end:
~~~~~~~~~~~~~~~~

-   `NodeJs`
-   `ExpressJs`
-   `JavsScript`
-   `MongoDB for Database`
-   `Flask for running backend server`

Tools
------------

-   `Python`
-   `npm`
-   `node`
-   `nodemon`
-   `Jupyter Notebook`

Overview of Entire Codebase 
==============================

Entire codebase of the Smriti is divided into 3 principal components:

-   ``Authentication``
-   ``Review``
-   ``Drafting``

--------------------------

-   All the authentication modules(log-in, signup) are implemented in the authRoute file.
-   All the APIs related to review modules are implemented in the reviewRoute file.
-   All the APIs related to drafting modules are implemented in the draftRoute file.

--------------------------

For detailed description of the routes file visit Routes section
`Routes <routes.html>`__.

--------------------------

