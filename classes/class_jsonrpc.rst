:github_url: hide

.. Generated automatically by doc/tools/makerst.py in Godot's source tree.
.. DO NOT EDIT THIS FILE, but the JSONRPC.xml source instead.
.. The source is found in doc/classes or modules/<name>/doc_classes.

.. _class_JSONRPC:

JSONRPC
=======

**Inherits:** :ref:`Object<class_Object>`

**Category:** Core

Brief Description
-----------------



Methods
-------

+-------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Dictionary<class_Dictionary>` | :ref:`make_notification<class_JSONRPC_method_make_notification>` **(** :ref:`String<class_String>` method, :ref:`Variant<class_Variant>` params **)**                                         |
+-------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Dictionary<class_Dictionary>` | :ref:`make_request<class_JSONRPC_method_make_request>` **(** :ref:`String<class_String>` method, :ref:`Variant<class_Variant>` params, :ref:`Variant<class_Variant>` id **)**                 |
+-------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Dictionary<class_Dictionary>` | :ref:`make_response<class_JSONRPC_method_make_response>` **(** :ref:`Variant<class_Variant>` result, :ref:`Variant<class_Variant>` id **)**                                                   |
+-------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Dictionary<class_Dictionary>` | :ref:`make_response_error<class_JSONRPC_method_make_response_error>` **(** :ref:`int<class_int>` code, :ref:`String<class_String>` message, :ref:`Variant<class_Variant>` id=null **)** const |
+-------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Variant<class_Variant>`       | :ref:`process_action<class_JSONRPC_method_process_action>` **(** :ref:`Variant<class_Variant>` action, :ref:`bool<class_bool>` recurse=false **)**                                            |
+-------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`String<class_String>`         | :ref:`process_string<class_JSONRPC_method_process_string>` **(** :ref:`String<class_String>` action **)**                                                                                     |
+-------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| void                                | :ref:`set_scope<class_JSONRPC_method_set_scope>` **(** :ref:`String<class_String>` scope, :ref:`Object<class_Object>` target **)**                                                            |
+-------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

Enumerations
------------

.. _enum_JSONRPC_ErrorCode:

.. _class_JSONRPC_constant_PARSE_ERROR:

.. _class_JSONRPC_constant_INVALID_REQUEST:

.. _class_JSONRPC_constant_METHOD_NOT_FOUND:

.. _class_JSONRPC_constant_INVALID_PARAMS:

.. _class_JSONRPC_constant_INTERNAL_ERROR:

enum **ErrorCode**:

- **PARSE_ERROR** = **-32700**

- **INVALID_REQUEST** = **-32600**

- **METHOD_NOT_FOUND** = **-32601**

- **INVALID_PARAMS** = **-32602**

- **INTERNAL_ERROR** = **-32603**

Method Descriptions
-------------------

.. _class_JSONRPC_method_make_notification:

- :ref:`Dictionary<class_Dictionary>` **make_notification** **(** :ref:`String<class_String>` method, :ref:`Variant<class_Variant>` params **)**

----

.. _class_JSONRPC_method_make_request:

- :ref:`Dictionary<class_Dictionary>` **make_request** **(** :ref:`String<class_String>` method, :ref:`Variant<class_Variant>` params, :ref:`Variant<class_Variant>` id **)**

----

.. _class_JSONRPC_method_make_response:

- :ref:`Dictionary<class_Dictionary>` **make_response** **(** :ref:`Variant<class_Variant>` result, :ref:`Variant<class_Variant>` id **)**

----

.. _class_JSONRPC_method_make_response_error:

- :ref:`Dictionary<class_Dictionary>` **make_response_error** **(** :ref:`int<class_int>` code, :ref:`String<class_String>` message, :ref:`Variant<class_Variant>` id=null **)** const

----

.. _class_JSONRPC_method_process_action:

- :ref:`Variant<class_Variant>` **process_action** **(** :ref:`Variant<class_Variant>` action, :ref:`bool<class_bool>` recurse=false **)**

----

.. _class_JSONRPC_method_process_string:

- :ref:`String<class_String>` **process_string** **(** :ref:`String<class_String>` action **)**

----

.. _class_JSONRPC_method_set_scope:

- void **set_scope** **(** :ref:`String<class_String>` scope, :ref:`Object<class_Object>` target **)**

