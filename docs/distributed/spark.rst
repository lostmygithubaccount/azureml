Spark
=====

Apache Spark_ is a unified analytics engine for large-scale data processing.

Overview
--------

Apache Spark is open source. It provides high-level APIs for Java, Scala, Python, and R.

Parameters
----------

- ``nodes``, type = int, default = ``1``
- ``**executor_params``, type = params
- ``**worker_params``, type = params

Requirements
------------

To run Spark, you need...


Initialization
--------------

Simply initialize the SparkContext in the language of your choice, e.g. Python:

.. code-block:: python

    from pyspark import SparkContext

    sc = SparkContext()

GPUs
----

As of version 3.0.0, Spark supports GPUs...

.. _spark: https://spark.apache.org
