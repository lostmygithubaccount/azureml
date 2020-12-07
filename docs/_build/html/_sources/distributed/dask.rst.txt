Dask
====

Dask_ natively scales Python and provides advanced parallelism for analytics.

Overview
--------

Dask is open source and exists within the broader PyData community, which consists of commonly used data science tools like Numpy, Pandas, and Scikit-Learn.

Parameters
----------

- ``nodes``, type = int, default = ``1``
- ``adaptive``, type = bool, default = ``false``
- ``min_nodes``, type = int, default = ``0``
- ``max_nodes``, type = int, default = ``-1``
- ``**scheduler_params``, type = params
- ``**worker_params``, type = params

Requirements
------------

To run Dask, you need:

- Python
- pip:

  - dask
  - distributed
  - bokeh
  - ...
  

Recommended docker images include:

- "azureml/dask"
- "dask/daskdev"
- "rapidsai/rapidsai"

Initialization
--------------

Simply initialize a distributed_ client:

.. code-block:: python 

    from distributed import Client

    client = Client()

GPUs
----

Dask is agnostic of the compute type. Start a CUDA worker on GPU-enabled machines to utilize GPUs. 

Rapids_ is developed to extend support APIs to GPUs.


.. _dask: https://github.com/dask/dask

.. _distributed: https://github.com/dask/distributed

.. _rapids: https://github.com/rapidsai

