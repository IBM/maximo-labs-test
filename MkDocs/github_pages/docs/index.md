# Welcome to the IBM Maximo Github Pages Lab
This lab will document the steps needed in order to use Github Pages to host the Maximo Labs,
like:

* Changes to the github repo
* Change image location in all md files and modify the build_all_mkdocs script
* Edit mkdocs.yml files for all labs
* ...

A minimized replica of the originial monitor-hands-on-labs has been used 
in order to get the basics right.

The experimentation has been done in a new Github repo in the IBM organization, 
called maximo-labs-test.


After building the labs, so the /site directory has been build, then run this command to publish the site to Github Pages:

    ghp-import -po site

---

**Updated: 2023-12-05**

---