Make sure you run tests with `-- --test-threads=1` due to some of the tests relying on zeromq being down and the others on it being up and I have not yet found a way to set this up for each individual test.

Tests are executed in alphabetical order of module name. 