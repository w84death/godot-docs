.. Generated automatically by doc/tools/makerst.py in Godot's source tree.
.. DO NOT EDIT THIS FILE, but the CollisionObject.xml source instead.
.. The source is found in doc/classes or modules/<name>/doc_classes.

.. _class_CollisionObject:

CollisionObject
===============

**Inherits:** :ref:`Spatial<class_spatial>` **<** :ref:`Node<class_node>` **<** :ref:`Object<class_object>`

**Inherited By:** :ref:`PhysicsBody<class_physicsbody>`, :ref:`Area<class_area>`

**Category:** Core

Brief Description
-----------------

Base node for collision objects.

Member Functions
----------------

+------------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| void                               | :ref:`_input_event<class_CollisionObject__input_event>`  **(** :ref:`Object<class_object>` camera, :ref:`InputEvent<class_inputevent>` event, :ref:`Vector3<class_vector3>` click_position, :ref:`Vector3<class_vector3>` click_normal, :ref:`int<class_int>` shape_idx  **)** virtual |
+------------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`              | :ref:`create_shape_owner<class_CollisionObject_create_shape_owner>`  **(** :ref:`Object<class_object>` owner  **)**                                                                                                                                                                    |
+------------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`bool<class_bool>`            | :ref:`get_capture_input_on_drag<class_CollisionObject_get_capture_input_on_drag>`  **(** **)** const                                                                                                                                                                                   |
+------------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`RID<class_rid>`              | :ref:`get_rid<class_CollisionObject_get_rid>`  **(** **)** const                                                                                                                                                                                                                       |
+------------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Array<class_array>`          | :ref:`get_shape_owners<class_CollisionObject_get_shape_owners>`  **(** **)**                                                                                                                                                                                                           |
+------------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`bool<class_bool>`            | :ref:`is_ray_pickable<class_CollisionObject_is_ray_pickable>`  **(** **)** const                                                                                                                                                                                                       |
+------------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`bool<class_bool>`            | :ref:`is_shape_owner_disabled<class_CollisionObject_is_shape_owner_disabled>`  **(** :ref:`int<class_int>` owner_id  **)** const                                                                                                                                                       |
+------------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| void                               | :ref:`remove_shape_owner<class_CollisionObject_remove_shape_owner>`  **(** :ref:`int<class_int>` owner_id  **)**                                                                                                                                                                       |
+------------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| void                               | :ref:`set_capture_input_on_drag<class_CollisionObject_set_capture_input_on_drag>`  **(** :ref:`bool<class_bool>` enable  **)**                                                                                                                                                         |
+------------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| void                               | :ref:`set_ray_pickable<class_CollisionObject_set_ray_pickable>`  **(** :ref:`bool<class_bool>` ray_pickable  **)**                                                                                                                                                                     |
+------------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`              | :ref:`shape_find_owner<class_CollisionObject_shape_find_owner>`  **(** :ref:`int<class_int>` shape_index  **)** const                                                                                                                                                                  |
+------------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| void                               | :ref:`shape_owner_add_shape<class_CollisionObject_shape_owner_add_shape>`  **(** :ref:`int<class_int>` owner_id, :ref:`Shape<class_shape>` shape  **)**                                                                                                                                |
+------------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| void                               | :ref:`shape_owner_clear_shapes<class_CollisionObject_shape_owner_clear_shapes>`  **(** :ref:`int<class_int>` owner_id  **)**                                                                                                                                                           |
+------------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Object<class_object>`        | :ref:`shape_owner_get_owner<class_CollisionObject_shape_owner_get_owner>`  **(** :ref:`int<class_int>` owner_id  **)** const                                                                                                                                                           |
+------------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Shape<class_shape>`          | :ref:`shape_owner_get_shape<class_CollisionObject_shape_owner_get_shape>`  **(** :ref:`int<class_int>` owner_id, :ref:`int<class_int>` shape_id  **)** const                                                                                                                           |
+------------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`              | :ref:`shape_owner_get_shape_count<class_CollisionObject_shape_owner_get_shape_count>`  **(** :ref:`int<class_int>` owner_id  **)** const                                                                                                                                               |
+------------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`              | :ref:`shape_owner_get_shape_index<class_CollisionObject_shape_owner_get_shape_index>`  **(** :ref:`int<class_int>` owner_id, :ref:`int<class_int>` shape_id  **)** const                                                                                                               |
+------------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Transform<class_transform>`  | :ref:`shape_owner_get_transform<class_CollisionObject_shape_owner_get_transform>`  **(** :ref:`int<class_int>` owner_id  **)** const                                                                                                                                                   |
+------------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| void                               | :ref:`shape_owner_remove_shape<class_CollisionObject_shape_owner_remove_shape>`  **(** :ref:`int<class_int>` owner_id, :ref:`int<class_int>` shape_id  **)**                                                                                                                           |
+------------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| void                               | :ref:`shape_owner_set_disabled<class_CollisionObject_shape_owner_set_disabled>`  **(** :ref:`int<class_int>` owner_id, :ref:`bool<class_bool>` disabled  **)**                                                                                                                         |
+------------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| void                               | :ref:`shape_owner_set_transform<class_CollisionObject_shape_owner_set_transform>`  **(** :ref:`int<class_int>` owner_id, :ref:`Transform<class_transform>` transform  **)**                                                                                                            |
+------------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

Signals
-------

-  **input_event**  **(** :ref:`Object<class_object>` camera, :ref:`Object<class_object>` event, :ref:`Vector3<class_vector3>` click_position, :ref:`Vector3<class_vector3>` click_normal, :ref:`int<class_int>` shape_idx  **)**
-  **mouse_entered**  **(** **)**
Emitted when the mouse pointer enters any of this object's shapes.

-  **mouse_exited**  **(** **)**
Emitted when the mouse pointer exits all this object's shapes.


Member Variables
----------------

- :ref:`bool<class_bool>` **input_capture_on_drag**
- :ref:`bool<class_bool>` **input_ray_pickable**

Description
-----------

CollisionObject is the base class for physics objects. It can hold any number of collision :ref:`Shape<class_shape>`\ s. Each shape must be assigned to a *shape owner*. The CollisionObject can have any number of shape owners. Shape owners are not nodes and do not appear in the editor, but are accessible through code using the ``shape_owner\_\*`` methods.

Member Function Description
---------------------------

.. _class_CollisionObject__input_event:

- void  **_input_event**  **(** :ref:`Object<class_object>` camera, :ref:`InputEvent<class_inputevent>` event, :ref:`Vector3<class_vector3>` click_position, :ref:`Vector3<class_vector3>` click_normal, :ref:`int<class_int>` shape_idx  **)** virtual

.. _class_CollisionObject_create_shape_owner:

- :ref:`int<class_int>`  **create_shape_owner**  **(** :ref:`Object<class_object>` owner  **)**

Creates a new shape owner for the given object. Returns ``owner_id`` of the new owner for future reference.

.. _class_CollisionObject_get_capture_input_on_drag:

- :ref:`bool<class_bool>`  **get_capture_input_on_drag**  **(** **)** const

.. _class_CollisionObject_get_rid:

- :ref:`RID<class_rid>`  **get_rid**  **(** **)** const

Returns the object's :ref:`RID<class_rid>`.

.. _class_CollisionObject_get_shape_owners:

- :ref:`Array<class_array>`  **get_shape_owners**  **(** **)**

Returns an :ref:`Array<class_array>` of ``owner_id`` identifiers. You can use these ids in other methods that take ``owner_id`` as an argument.

.. _class_CollisionObject_is_ray_pickable:

- :ref:`bool<class_bool>`  **is_ray_pickable**  **(** **)** const

.. _class_CollisionObject_is_shape_owner_disabled:

- :ref:`bool<class_bool>`  **is_shape_owner_disabled**  **(** :ref:`int<class_int>` owner_id  **)** const

If ``true`` the shape owner and its shapes are disabled.

.. _class_CollisionObject_remove_shape_owner:

- void  **remove_shape_owner**  **(** :ref:`int<class_int>` owner_id  **)**

Removes the given shape owner.

.. _class_CollisionObject_set_capture_input_on_drag:

- void  **set_capture_input_on_drag**  **(** :ref:`bool<class_bool>` enable  **)**

.. _class_CollisionObject_set_ray_pickable:

- void  **set_ray_pickable**  **(** :ref:`bool<class_bool>` ray_pickable  **)**

.. _class_CollisionObject_shape_find_owner:

- :ref:`int<class_int>`  **shape_find_owner**  **(** :ref:`int<class_int>` shape_index  **)** const

Returns the ``owner_id`` of the given shape.

.. _class_CollisionObject_shape_owner_add_shape:

- void  **shape_owner_add_shape**  **(** :ref:`int<class_int>` owner_id, :ref:`Shape<class_shape>` shape  **)**

Adds a :ref:`Shape<class_shape>` to the shape owner.

.. _class_CollisionObject_shape_owner_clear_shapes:

- void  **shape_owner_clear_shapes**  **(** :ref:`int<class_int>` owner_id  **)**

Removes all shapes from the shape owner.

.. _class_CollisionObject_shape_owner_get_owner:

- :ref:`Object<class_object>`  **shape_owner_get_owner**  **(** :ref:`int<class_int>` owner_id  **)** const

Returns the parent object of the given shape owner.

.. _class_CollisionObject_shape_owner_get_shape:

- :ref:`Shape<class_shape>`  **shape_owner_get_shape**  **(** :ref:`int<class_int>` owner_id, :ref:`int<class_int>` shape_id  **)** const

Returns the :ref:`Shape<class_shape>` with the given id from the given shape owner.

.. _class_CollisionObject_shape_owner_get_shape_count:

- :ref:`int<class_int>`  **shape_owner_get_shape_count**  **(** :ref:`int<class_int>` owner_id  **)** const

Returns the number of shapes the given shape owner contains.

.. _class_CollisionObject_shape_owner_get_shape_index:

- :ref:`int<class_int>`  **shape_owner_get_shape_index**  **(** :ref:`int<class_int>` owner_id, :ref:`int<class_int>` shape_id  **)** const

.. _class_CollisionObject_shape_owner_get_transform:

- :ref:`Transform<class_transform>`  **shape_owner_get_transform**  **(** :ref:`int<class_int>` owner_id  **)** const

Returns the shape owner's :ref:`Transform<class_transform>`.

.. _class_CollisionObject_shape_owner_remove_shape:

- void  **shape_owner_remove_shape**  **(** :ref:`int<class_int>` owner_id, :ref:`int<class_int>` shape_id  **)**

Removes a shape from the given shape owner.

.. _class_CollisionObject_shape_owner_set_disabled:

- void  **shape_owner_set_disabled**  **(** :ref:`int<class_int>` owner_id, :ref:`bool<class_bool>` disabled  **)**

If ``true`` disables the given shape owner.

.. _class_CollisionObject_shape_owner_set_transform:

- void  **shape_owner_set_transform**  **(** :ref:`int<class_int>` owner_id, :ref:`Transform<class_transform>` transform  **)**

Sets the :ref:`Transform<class_transform>` of the given shape owner.


