Inspired by https://github.com/fschulze/devpi-buildout

Setup
=====

.. code-block:: bash

  $ bin/supervisord
  $ bin/devpi use http://localhost:3141/
  $ bin/devpi login root --password=
  $ bin/devpi user -c foo password=bar
  $ bin/devpi login foo --password=bar
  $ bin/devpi index -c prod
  $ bin/devpi index -c test bases=foo/prod
