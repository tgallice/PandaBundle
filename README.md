XabbuhPandeBundle
=================

[![Build Status](https://travis-ci.org/xabbuh/PandaBundle.svg?branch=master)](https://travis-ci.org/xabbuh/PandaBundle)
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/xabbuh/PandaBundle/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/xabbuh/PandaBundle/?branch=master)

The XabbuhPandaBundle eases integration of the Panda encoding service into
Symfony 2. It sits on top a [PHP client implementation]
(https://github.com/xabbuh/panda-client) for Panda's REST API.

Features included are:

- Commands to maintain your cloud, your videos and their encodings
- Publishing of Panda notification events through Symfony's Event Dispatcher
  component
- Extends the default Symfony field form type that make it usable as Panda video
  uploader widget

Installation
------------

See the [documentation](Resources/doc/index.md) for instructions on how to
install the XabbuhPandaBundle.

License
-------

XabbuhPandaBundle is licensed under the MIT license. See the [LICENSE]
(Resources/meta/LICENSE) for the full license text.
