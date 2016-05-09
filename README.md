trivup - Trivially Up a cluster of applications
===============================================

![librdkafka tests](https://github.com/edenhill/trivup/raw/master/.librdkafka_tests.png)
*(Serving suggestion)*

trivup is a flexible, pluggable, light-weight, partly naiivistic, framework
for trivially bringing up a cluster of applications.

The initial use-case is to bring up a simple Kafka cluster for easily testing
[librdkafka](https://github.com/edenhill/librdkafka) on different
broker versions.

**NOTE**: It currently only operates on localhost.


See [tests/usecase.py](tests/usecase.py) for a small showcase.
