# Quickstart module for oembed integration

Provides the required configuration for using oembed for:
- Instagram posts

## Lando configuration
This project template includes a sample lando configuration file that can be
used to automatically build a local Arizona Quickstart site with your module
installed for development and testing.
```
lando start
lando install
```

The sample lando configuration also includes tooling that expose Quickstart's
code quality tools for checking that your module code adheres to Quickstart's
coding standards.
```
lando phpcs

lando phpcbf

lando phpstan
```
