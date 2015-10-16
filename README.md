Example of ert-volkswagen
==============================

[![Build Status](https://travis-ci.org/gongo/ert-volkswagen-example.svg?branch=master)](https://travis-ci.org/gongo/ert-volkswagen-example)

Usage
--------------------

```
$ cask
$ cask exec ert-runner
(snip)
Ran 3 tests in 0.045 seconds
3 unexpected results:
   FAILED  ert-volkswagen-example-test/date-of-founded
   FAILED  ert-volkswagen-example-test/exhaust-gas-test
   FAILED  ert-volkswagen-example-test/message

```

```
$ CI=1 cask exec ert-runner
...

Ran 3 tests in 0.000 seconds
```

License
--------------------

MIT
