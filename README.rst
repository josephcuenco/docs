=====================
MongoDB Documentation
=====================

Welcome to the MongoDB documentation repository! This repository contains the source files for the official MongoDB documentation, available at MongoDB Docs. It is maintained by the MongoDB Documentation Team, and contributions from the community are welcome.

This documentation covers topics such as installation, configuration, querying, and advanced MongoDB features. Your contributions help keep the documentation accurate and useful.


Building the Documentation
--------------------------
Prerequisites:

- Python 2.x (required by giza) 

- pip (Python package manager) 

- giza: Python-based command-line tool used to build and manage complex documentation projects



To build the MongoDB documentation locally, follow these steps:

Install giza:

``` 
python2 -m pip install giza
``` 

Clone this repository:

```
git clone https://github.com/mongodb/docs.git
cd docs/
```

Build the documentation:

```
make html
```

The HTML files will be located in build/<branch>/html/ (e.g., build/master/html/).

Contribute
----------

The MongoDB Documentation Project is governed by the terms of the
`MongoDB Contributor Agreement
<https://www.mongodb.com/legal/contributor-agreement>`_.

To contribute to the documentation, 

- If you have not done so already, please sign the `MongoDB Contributor Agreement <https://www.mongodb.com/legal/contributor-agreement>`_.

- Fork this repository on GitHub and issue a pull request. 

Report Issues
-------------

If you encounter an issue or have a request for new documentation, submit an issue in the `Documentation Jira Project <https://jira.mongodb.org/browse/DOCS>`_. When submitting an issue, please include:

- A detailed description of the problem or request.
- A link to the affected documentation (if applicable).
- Any suggestions or corrections.

License
-------

All documentation is available under the terms of a `Creative Commons
License <https://creativecommons.org/licenses/by-nc-sa/3.0/>`_.

If you have any questions, please contact `docs@mongodb.com
<mailto:docs@mongodb.com>`_.

-- The MongoDB Documentation Team
