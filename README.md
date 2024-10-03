# The clojure.core test suite
This is a set of tests for Clojure's core standard library. Its purpose is not
only to draw clear boundaries around Clojure JVM's behavior, but also to serve
as a compliance suite for other Clojure dialects.

Currently, this project is owned by jank, the native Clojure dialect. As we
build it up and prove jank's readiness, we also create value for the rest of the
Clojure community.

## How to contribute
Anyone with Clojure knowledge can help out!

Check out the latest progress and the steps for helping out here: https://github.com/jank-lang/clojure.core-test/issues/1

## Running the tests
For a one-off run, you can use the following:

```bash
$ lein test
```

However, during development, you can use `test-refresh` to automatically re-run
the test suite whenever you save new changes.

```bash
$ lein test-refresh
```
