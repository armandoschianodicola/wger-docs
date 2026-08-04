.. _cloudron:

Cloudron
========

There is a community-maintained package for `Cloudron <https://www.cloudron.io/>`_:

  https://github.com/OrcVole/wger-cloudron

The package is available through Cloudron's community app store and integrates
with Cloudron's user management via OpenID Connect and stores uploaded media in
the app's data directory so that it is included in Cloudron's backups.

Note that it currently does **not** include PowerSync, so you won't be able to
connect to the server with the mobile app.

This script is **not maintained by the wger project**. We can't guarantee that
it stays up to date with current wger releases, and we can't provide support
for issues caused by the script itself. For problems with the script, open an
issue against
`OrcVole/wger-cloudron <https://github.com/OrcVole/wger-cloudron/issues>`_.

For a setup that we test and support, see :doc:`docker`.
