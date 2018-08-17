baseplate
=========

|Build Status|

.. image:: https://reddit.testspace.com/spaces/122633/badge?token=d8fc2a779b88a27f39e1fc5044635a0e6907f100
    :alt: Space Health
    :target: https://reddit.testspace.com/spaces/122633?utm_campaign=badge&utm_medium=referral&utm_source=test

.. image:: https://reddit.testspace.com/spaces/122633/metrics/78043/badge?token=c8031e091264b293c8cc63b3e87a0fb22c1dbd0c
    :alt: Space Metric
    :target: https://reddit.testspace.com/spaces/122633/schema/Code%20Coverage?utm_campaign=badge&utm_medium=referral&utm_source=coverage%28%3F%3A%29

.. image:: https://reddit.testspace.com/spaces/122633/metrics/78044/badge?token=d75e5ccbc87ce4c3bdc5b1a057a61fcf8e229357
    :alt: Space Metric
    :target: https://reddit.testspace.com/spaces/122633/schema/Code%20Coverage?utm_campaign=badge&utm_medium=referral&utm_source=coverage

Baseplate is a library to build services on. Its goal is to provide all
the common things a service needs with as few surprises as possible,
including:

-  compatibility with Python 2.7 and Python 3.4+
-  transparent diagnostic information collection (metrics, tracing,
   logging)
-  configuration parsing
-  gevent-based Thrift and WSGI servers meant to run under
   `Einhorn <https://github.com/stripe/einhorn>`__
-  and various helper libraries like a Thrift client pool

Read the `full docs <https://baseplate.readthedocs.io/en/stable/>`__.

.. |Build Status| image:: https://travis-ci.org/reddit/baseplate.svg?branch=master
   :target: https://travis-ci.org/reddit/baseplate
