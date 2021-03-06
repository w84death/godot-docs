.. Generated automatically by doc/tools/makerst.py in Godot's source tree.
.. DO NOT EDIT THIS FILE, but the DirectionalLight.xml source instead.
.. The source is found in doc/classes or modules/<name>/doc_classes.

.. _class_DirectionalLight:

DirectionalLight
================

**Inherits:** :ref:`Light<class_light>` **<** :ref:`VisualInstance<class_visualinstance>` **<** :ref:`Spatial<class_spatial>` **<** :ref:`Node<class_node>` **<** :ref:`Object<class_object>`

**Category:** Core

Brief Description
-----------------

Directional Light, such as the Sun or the Moon.

Member Functions
----------------

+--------------------------+-----------------------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`    | :ref:`get_shadow_depth_range<class_DirectionalLight_get_shadow_depth_range>`  **(** **)** const                       |
+--------------------------+-----------------------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`    | :ref:`get_shadow_mode<class_DirectionalLight_get_shadow_mode>`  **(** **)** const                                     |
+--------------------------+-----------------------------------------------------------------------------------------------------------------------+
| :ref:`bool<class_bool>`  | :ref:`is_blend_splits_enabled<class_DirectionalLight_is_blend_splits_enabled>`  **(** **)** const                     |
+--------------------------+-----------------------------------------------------------------------------------------------------------------------+
| void                     | :ref:`set_blend_splits<class_DirectionalLight_set_blend_splits>`  **(** :ref:`bool<class_bool>` enabled  **)**        |
+--------------------------+-----------------------------------------------------------------------------------------------------------------------+
| void                     | :ref:`set_shadow_depth_range<class_DirectionalLight_set_shadow_depth_range>`  **(** :ref:`int<class_int>` mode  **)** |
+--------------------------+-----------------------------------------------------------------------------------------------------------------------+
| void                     | :ref:`set_shadow_mode<class_DirectionalLight_set_shadow_mode>`  **(** :ref:`int<class_int>` mode  **)**               |
+--------------------------+-----------------------------------------------------------------------------------------------------------------------+

Member Variables
----------------

- :ref:`float<class_float>` **directional_shadow_bias_split_scale**
- :ref:`bool<class_bool>` **directional_shadow_blend_splits**
- :ref:`int<class_int>` **directional_shadow_depth_range**
- :ref:`float<class_float>` **directional_shadow_max_distance**
- :ref:`int<class_int>` **directional_shadow_mode**
- :ref:`float<class_float>` **directional_shadow_normal_bias**
- :ref:`float<class_float>` **directional_shadow_split_1**
- :ref:`float<class_float>` **directional_shadow_split_2**
- :ref:`float<class_float>` **directional_shadow_split_3**

Numeric Constants
-----------------

- **SHADOW_ORTHOGONAL** = **0**
- **SHADOW_PARALLEL_2_SPLITS** = **1**
- **SHADOW_PARALLEL_4_SPLITS** = **2**
- **SHADOW_DEPTH_RANGE_STABLE** = **0**
- **SHADOW_DEPTH_RANGE_OPTIMIZED** = **1**

Description
-----------

A DirectionalLight is a type of :ref:`Light<class_light>` node that emits light constantly in one direction (the negative z axis of the node). It is used lights with strong intensity that are located far away from the scene to model sunlight or moonlight. The worldspace location of the DirectionalLight transform (origin) is ignored, only the basis is used do determine light direction.

Member Function Description
---------------------------

.. _class_DirectionalLight_get_shadow_depth_range:

- :ref:`int<class_int>`  **get_shadow_depth_range**  **(** **)** const

.. _class_DirectionalLight_get_shadow_mode:

- :ref:`int<class_int>`  **get_shadow_mode**  **(** **)** const

.. _class_DirectionalLight_is_blend_splits_enabled:

- :ref:`bool<class_bool>`  **is_blend_splits_enabled**  **(** **)** const

.. _class_DirectionalLight_set_blend_splits:

- void  **set_blend_splits**  **(** :ref:`bool<class_bool>` enabled  **)**

.. _class_DirectionalLight_set_shadow_depth_range:

- void  **set_shadow_depth_range**  **(** :ref:`int<class_int>` mode  **)**

.. _class_DirectionalLight_set_shadow_mode:

- void  **set_shadow_mode**  **(** :ref:`int<class_int>` mode  **)**


