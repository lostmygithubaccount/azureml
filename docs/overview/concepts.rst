Concepts
========

In `azureml`, all concepts derive from a base asset which has:

- a name
- a unique id (GUID)
- a version
- a description
- tags

Formally, an asset in `azureml` is in Azure Resource Manager (ARM) Resource defined under the MachineLearningService. Assets can be created from:

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
