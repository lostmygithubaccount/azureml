Job
===

A Job...

Parameters
----------

**Required**

- ``name``, type = string
- ``command``, type = string

**Optional**

- ``environment``, type = string or azureml.Environment, default = ``""``
- ``datasets``, type = string or azureml.Data or list[string] or list[azureml.Data], default = ``""``
- ``target``, type = string or azureml.Compute, default = ``"local"``
- ``distribution``, type = enum, options: ``"horovod"``, ``"pytorch"``, ``"tensorflow"``, ``"spark"``, ``"dask"``, ``"ray"``
- ``**distributed_params``, type = params

  - see the distributed documentation for the corresponding type for distribution params

- ``**sweep_params``, type = params

  - ``sampling``, type = enum, options: ``"random"``, ``"bayesian"``, ``"grid"``, default = ``"random"``