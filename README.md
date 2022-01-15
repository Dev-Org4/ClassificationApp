# ClassificationApp

> ## Prerequisites:

-   Python:
    -   Python: 3.9.9
-   SPARQLWrapper:
    ```bash
    pip install sparqlwrapper
    ```
-   Flask:
    ```bash
    pip install Flask
    ```
-   Scikit-learn:
    ```bash
    pip install scikit-learn
    ```
-   Pandas:

    ```bash
    pip install pandas
    ```

    > ## Create Environment:

-   Linux/Mac OS:(on linux works without the creation of the virtual environment)
    ```bash
    $ mkdir myproject
    $ cd myproject
    $ python3 -m venv venv
    ```
-   Windows:
    ```bash
    $ mkdir myproject
    $ cd myproject
    $ py -3 -m venv venv
    ```

> ## Activate Environment (requires the environment creation):

-   Linux/Mac OS:
    ```bash
    $ . venv/bin/activate
    ```
-   Windows:
    ```bash
    $ venv\Scripts\activate
    ```

> ## Initialize Server:

-   Linux/Mac OS:
    ```bash
    $ export FLASK_RUN_PORT=5000
    $ export FLASK_APP=__filename__
    $ export FLASK_ENV=development
    $ flask run
    ```
-   Windows(CMD):
    ```bash
    $ set FLASK_RUN_PORT=5000
    $ set FLASK_APP=__filename__
    $ set FLASK_ENV=development
    $ flask run
    ```
