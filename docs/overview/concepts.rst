Concepts
========

In `azureml`, all concepts are represented as an asset.

Parameters
----------

**Required**

- ``name``, type = string

**Optional**

- ``id``, type = guid, defaults to auto-gen on creation 
- ``version``, type = string, default = ``"latest"``
- ``description``, type = string, default = ``""``
- ``tags``, type = map, default = ``{}``

Management
----------

An asset in `azureml` is an Azure Resource Manager (ARM) Resource defined under the MachineLearningService scope. Assets can be managed from:

- Azure Portal
- Azure Machine Learning Studio
- ARM template (JSON)
- YAML
- CLI
- Python

Assets
------

.. toctree::
   :hidden:
   :caption: Assets

   concepts/workspace.rst
   concepts/data.rst
   concepts/compute.rst
   concepts/environment.rst
   concepts/model.rst
   concepts/job.rst
   concepts/endpoint.rst
