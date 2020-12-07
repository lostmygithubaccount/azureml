Workspace
=========

A Workspace...

Parameters
----------

**Required**

- ``name``, type = string
- ``resource_group``, type = string

**Optional**

- ``location``, type = enum,  options: see available regions, default = ``"eastus"``
- ``create_resources``, type = bool, default = ``true``

  - creates Azure resource group, virtual network, storage account, and key vault
  - set to ``false`` to ensure an existing resource group and resources are used

- ``virtual_network``, type = string, default = ``""``

  - name of virtual network
  - must be in same resource group
  - if specified, will create all resources in this vnet by default

- ``storage_account``, type = string, default = ``""``

  - name of storage account
  - must be in same resource group

- ``key_vault``, type = string, default = ``""``

  - name of the key vault
  - must be in same resource group
