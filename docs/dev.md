Development
===========

This page contains information for developers about how to contribute to this project.

Submodules
----------

This project contains the following submodules:

* `lib`: Contains the XML schema definitions and Java classes for validating them.
* `rpm`: Contains the configuration for building the RPM package.

Unit tests
----------

To run the unit tests, use the following command in the root of this project:

```bash
mvn test
```

If you haven't built the project before, you might need to install the submodules to the local repository first:

```bash
mvn install -DskipTests
mvn test
```

The tests validate the XSD files and check them against example XML files.

