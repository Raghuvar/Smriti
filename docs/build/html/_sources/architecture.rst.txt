********************
Smriti Architecture
********************

The architecture of Smriti web app is totally based on the MVC architecture
which follows as:

Smriti's MVC architecture consists of with the 3 principal components:

   - **Models:** Models is the directory in which all the database concepts are implemented. We have used MongoDB as the database for the backend.

   - **Views:** Views is the directory in which all the UIs concepts are implemented.

   - **Controller:** Controller is the directory in which backend features are implemented.


Directory Structure of Smriti
===============================

-   **auth** : contain all the authentication implementation strategies.
-   **config** : contain the production and development set up configuration.
-   **controllers** : contain the backend features implementation strategies.
-   **flask_api** : contain the back end server implementation strategies.
-   **Models** : contain all the database connection strategies.
-   **public** : contain all the ``css``, ``js`` and other public files. 
-   **routes** : contain all the APIs routes related to ``GET`` and ``POST`` request.
-   **views** : contain all the implementation of front-end UIs of all the pages.
