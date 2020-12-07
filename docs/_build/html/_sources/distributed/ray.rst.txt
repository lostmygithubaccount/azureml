Ray
===

Ray_ provides a simple, universal API for building distributed applications.

Parameters
----------

- ``nodes``, type = int, default = ``1``

Requirements
------------

To run Ray, you need:

- Python
- pip: 

  - ray

Recommended docker images include:

- "azureml/ray"

Initialization
--------------

Simple initialize ray_:

.. code-block:: python

    import ray

    ray.init()

GPUs
----

Ray supports GPUs...

.. _ray: https://docs.ray.io
