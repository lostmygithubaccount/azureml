Concepts
========

In `azureml`, all concepts derive from a base Asset which has:

- a name
- a unique id (GUID)
- a version
- tags

Formally, an Asset in `azureml` is in Azure Resource Manager (ARM) Resource defined under the MachineLearningService. Assets can be created from:

- JSON ARM template
- YAML
- CLI
- Python

.. toctree::
   :maxdepth: 2
   :hidden:

   concepts/workspace.rst
   concepts/data.rst
   concepts/compute.rst
   concepts/environment.rst
   concepts/model.rst
   concepts/job.rst
   concepts/endpoint.rst
