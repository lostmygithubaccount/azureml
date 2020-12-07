Concepts
========

In `azureml`, all concepts are represented as an asset.

**Required**

- ``name``, type = string

**Optional**

- ``id``, type = guid, defaults to auto-gen on creation 
- ``version``, type = string, default = ``"latest"``
- ``description``, type = string, default = ``""``
- ``tags``, type = map, default = ``{}``

.. toctree::
   :hidden:

   concepts/workspace.rst
   concepts/data.rst
   concepts/compute.rst
   concepts/environment.rst
   concepts/model.rst
   concepts/job.rst
   concepts/endpoint.rst
