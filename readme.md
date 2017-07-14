# Heroku Buildpack Sprettur

This buildpack injects `sprettur` (the Heroku CI test runner) into a Heroku dyno, aliases it to `ci`, and performs other operations to prepare a dyno for testing with Heroku CI.

It is primarily designed for internal use by the Heroku CI system. Other use cases may be possible, but are not supported.
