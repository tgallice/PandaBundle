CHANGELOG
=========

1.0.4
-----

* update dependencies to work with Symfony 2.5.4

1.0.3
-----

* add tests for the ``EventFactory`` class

1.0.2
-----

* ensure that a form id is set when enabling the upload form widget

* add tests for the ``VideoUploaderExtension`` class

* commands don't terminate unexpectedly when the client library throws an
  exception

1.0.1
-----

* service container extension test improvements (by using test case classes
  from the ``matthiasnoback/symfony-dependency-injection-test`` package)

* do not display misleading pagination information with empty result sets in
  the ``panda:video:list`` command
