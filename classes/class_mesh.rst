:github_url: hide

.. Generated automatically by doc/tools/make_rst.py in Godot's source tree.
.. DO NOT EDIT THIS FILE, but the Mesh.xml source instead.
.. The source is found in doc/classes or modules/<name>/doc_classes.

.. _class_Mesh:

Mesh
====

**Inherits:** :ref:`Resource<class_Resource>` **<** :ref:`RefCounted<class_RefCounted>` **<** :ref:`Object<class_Object>`

**Inherited By:** :ref:`ArrayMesh<class_ArrayMesh>`, :ref:`ImmediateMesh<class_ImmediateMesh>`, :ref:`PrimitiveMesh<class_PrimitiveMesh>`

A :ref:`Resource<class_Resource>` that contains vertex array-based geometry.

Description
-----------

Mesh is a type of :ref:`Resource<class_Resource>` that contains vertex array-based geometry, divided in *surfaces*. Each surface contains a completely separate array and a material used to draw it. Design wise, a mesh with multiple surfaces is preferred to a single surface, because objects created in 3D editing software commonly contain multiple materials.

Tutorials
---------

- `3D Material Testers Demo <https://godotengine.org/asset-library/asset/123>`__

- `3D Kinematic Character Demo <https://godotengine.org/asset-library/asset/126>`__

- `3D Platformer Demo <https://godotengine.org/asset-library/asset/125>`__

- `Third Person Shooter Demo <https://godotengine.org/asset-library/asset/678>`__

Properties
----------

+---------------------------------+-------------------------------------------------------------------+--------------------+
| :ref:`Vector2i<class_Vector2i>` | :ref:`lightmap_size_hint<class_Mesh_property_lightmap_size_hint>` | ``Vector2i(0, 0)`` |
+---------------------------------+-------------------------------------------------------------------+--------------------+

Methods
-------

+-----------------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`AABB<class_AABB>`                             | :ref:`_get_aabb<class_Mesh_method__get_aabb>` **(** **)** |virtual| |const|                                                                                       |
+-----------------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`                               | :ref:`_get_blend_shape_count<class_Mesh_method__get_blend_shape_count>` **(** **)** |virtual| |const|                                                             |
+-----------------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`StringName<class_StringName>`                 | :ref:`_get_blend_shape_name<class_Mesh_method__get_blend_shape_name>` **(** :ref:`int<class_int>` index **)** |virtual| |const|                                   |
+-----------------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`                               | :ref:`_get_surface_count<class_Mesh_method__get_surface_count>` **(** **)** |virtual| |const|                                                                     |
+-----------------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| void                                                | :ref:`_set_blend_shape_name<class_Mesh_method__set_blend_shape_name>` **(** :ref:`int<class_int>` index, :ref:`StringName<class_StringName>` name **)** |virtual| |
+-----------------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`                               | :ref:`_surface_get_array_index_len<class_Mesh_method__surface_get_array_index_len>` **(** :ref:`int<class_int>` index **)** |virtual| |const|                     |
+-----------------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`                               | :ref:`_surface_get_array_len<class_Mesh_method__surface_get_array_len>` **(** :ref:`int<class_int>` index **)** |virtual| |const|                                 |
+-----------------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Array<class_Array>`                           | :ref:`_surface_get_arrays<class_Mesh_method__surface_get_arrays>` **(** :ref:`int<class_int>` index **)** |virtual| |const|                                       |
+-----------------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Array<class_Array>`                           | :ref:`_surface_get_blend_shape_arrays<class_Mesh_method__surface_get_blend_shape_arrays>` **(** :ref:`int<class_int>` index **)** |virtual| |const|               |
+-----------------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`                               | :ref:`_surface_get_format<class_Mesh_method__surface_get_format>` **(** :ref:`int<class_int>` index **)** |virtual| |const|                                       |
+-----------------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Dictionary<class_Dictionary>`                 | :ref:`_surface_get_lods<class_Mesh_method__surface_get_lods>` **(** :ref:`int<class_int>` index **)** |virtual| |const|                                           |
+-----------------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Material<class_Material>`                     | :ref:`_surface_get_material<class_Mesh_method__surface_get_material>` **(** :ref:`int<class_int>` index **)** |virtual| |const|                                   |
+-----------------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`                               | :ref:`_surface_get_primitive_type<class_Mesh_method__surface_get_primitive_type>` **(** :ref:`int<class_int>` index **)** |virtual| |const|                       |
+-----------------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| void                                                | :ref:`_surface_set_material<class_Mesh_method__surface_set_material>` **(** :ref:`int<class_int>` index, :ref:`Material<class_Material>` material **)** |virtual| |
+-----------------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Shape3D<class_Shape3D>`                       | :ref:`create_convex_shape<class_Mesh_method_create_convex_shape>` **(** :ref:`bool<class_bool>` clean=true, :ref:`bool<class_bool>` simplify=false **)** |const|  |
+-----------------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Mesh<class_Mesh>`                             | :ref:`create_outline<class_Mesh_method_create_outline>` **(** :ref:`float<class_float>` margin **)** |const|                                                      |
+-----------------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Shape3D<class_Shape3D>`                       | :ref:`create_trimesh_shape<class_Mesh_method_create_trimesh_shape>` **(** **)** |const|                                                                           |
+-----------------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`TriangleMesh<class_TriangleMesh>`             | :ref:`generate_triangle_mesh<class_Mesh_method_generate_triangle_mesh>` **(** **)** |const|                                                                       |
+-----------------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`AABB<class_AABB>`                             | :ref:`get_aabb<class_Mesh_method_get_aabb>` **(** **)** |const|                                                                                                   |
+-----------------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`PackedVector3Array<class_PackedVector3Array>` | :ref:`get_faces<class_Mesh_method_get_faces>` **(** **)** |const|                                                                                                 |
+-----------------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`                               | :ref:`get_surface_count<class_Mesh_method_get_surface_count>` **(** **)** |const|                                                                                 |
+-----------------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Array<class_Array>`                           | :ref:`surface_get_arrays<class_Mesh_method_surface_get_arrays>` **(** :ref:`int<class_int>` surf_idx **)** |const|                                                |
+-----------------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Array<class_Array>`                           | :ref:`surface_get_blend_shape_arrays<class_Mesh_method_surface_get_blend_shape_arrays>` **(** :ref:`int<class_int>` surf_idx **)** |const|                        |
+-----------------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Material<class_Material>`                     | :ref:`surface_get_material<class_Mesh_method_surface_get_material>` **(** :ref:`int<class_int>` surf_idx **)** |const|                                            |
+-----------------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| void                                                | :ref:`surface_set_material<class_Mesh_method_surface_set_material>` **(** :ref:`int<class_int>` surf_idx, :ref:`Material<class_Material>` material **)**          |
+-----------------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------+

Enumerations
------------

.. _enum_Mesh_PrimitiveType:

.. _class_Mesh_constant_PRIMITIVE_POINTS:

.. _class_Mesh_constant_PRIMITIVE_LINES:

.. _class_Mesh_constant_PRIMITIVE_LINE_STRIP:

.. _class_Mesh_constant_PRIMITIVE_TRIANGLES:

.. _class_Mesh_constant_PRIMITIVE_TRIANGLE_STRIP:

enum **PrimitiveType**:

- **PRIMITIVE_POINTS** = **0** --- Render array as points (one vertex equals one point).

- **PRIMITIVE_LINES** = **1** --- Render array as lines (every two vertices a line is created).

- **PRIMITIVE_LINE_STRIP** = **2** --- Render array as line strip.

- **PRIMITIVE_TRIANGLES** = **3** --- Render array as triangles (every three vertices a triangle is created).

- **PRIMITIVE_TRIANGLE_STRIP** = **4** --- Render array as triangle strips.

----

.. _enum_Mesh_ArrayType:

.. _class_Mesh_constant_ARRAY_VERTEX:

.. _class_Mesh_constant_ARRAY_NORMAL:

.. _class_Mesh_constant_ARRAY_TANGENT:

.. _class_Mesh_constant_ARRAY_COLOR:

.. _class_Mesh_constant_ARRAY_TEX_UV:

.. _class_Mesh_constant_ARRAY_TEX_UV2:

.. _class_Mesh_constant_ARRAY_CUSTOM0:

.. _class_Mesh_constant_ARRAY_CUSTOM1:

.. _class_Mesh_constant_ARRAY_CUSTOM2:

.. _class_Mesh_constant_ARRAY_CUSTOM3:

.. _class_Mesh_constant_ARRAY_BONES:

.. _class_Mesh_constant_ARRAY_WEIGHTS:

.. _class_Mesh_constant_ARRAY_INDEX:

.. _class_Mesh_constant_ARRAY_MAX:

enum **ArrayType**:

- **ARRAY_VERTEX** = **0** --- :ref:`PackedVector3Array<class_PackedVector3Array>`, :ref:`PackedVector2Array<class_PackedVector2Array>`, or :ref:`Array<class_Array>` of vertex positions.

- **ARRAY_NORMAL** = **1** --- :ref:`PackedVector3Array<class_PackedVector3Array>` of vertex normals.

- **ARRAY_TANGENT** = **2** --- :ref:`PackedFloat32Array<class_PackedFloat32Array>` of vertex tangents. Each element in groups of 4 floats, first 3 floats determine the tangent, and the last the binormal direction as -1 or 1.

- **ARRAY_COLOR** = **3** --- :ref:`PackedColorArray<class_PackedColorArray>` of vertex colors.

- **ARRAY_TEX_UV** = **4** --- :ref:`PackedVector2Array<class_PackedVector2Array>` for UV coordinates.

- **ARRAY_TEX_UV2** = **5** --- :ref:`PackedVector2Array<class_PackedVector2Array>` for second UV coordinates.

- **ARRAY_CUSTOM0** = **6**

- **ARRAY_CUSTOM1** = **7**

- **ARRAY_CUSTOM2** = **8**

- **ARRAY_CUSTOM3** = **9**

- **ARRAY_BONES** = **10** --- :ref:`PackedFloat32Array<class_PackedFloat32Array>` or :ref:`PackedInt32Array<class_PackedInt32Array>` of bone indices. Each element is a group of 4 numbers.

- **ARRAY_WEIGHTS** = **11** --- :ref:`PackedFloat32Array<class_PackedFloat32Array>` of bone weights. Each element in groups of 4 floats.

- **ARRAY_INDEX** = **12** --- :ref:`PackedInt32Array<class_PackedInt32Array>` of integers used as indices referencing vertices, colors, normals, tangents, and textures. All of those arrays must have the same number of elements as the vertex array. No index can be beyond the vertex array size. When this index array is present, it puts the function into "index mode," where the index selects the \*i\*'th vertex, normal, tangent, color, UV, etc. This means if you want to have different normals or colors along an edge, you have to duplicate the vertices.

For triangles, the index array is interpreted as triples, referring to the vertices of each triangle. For lines, the index array is in pairs indicating the start and end of each line.

- **ARRAY_MAX** = **13** --- Represents the size of the :ref:`ArrayType<enum_Mesh_ArrayType>` enum.

----

.. _enum_Mesh_ArrayCustomFormat:

.. _class_Mesh_constant_ARRAY_CUSTOM_RGBA8_UNORM:

.. _class_Mesh_constant_ARRAY_CUSTOM_RGBA8_SNORM:

.. _class_Mesh_constant_ARRAY_CUSTOM_RG_HALF:

.. _class_Mesh_constant_ARRAY_CUSTOM_RGBA_HALF:

.. _class_Mesh_constant_ARRAY_CUSTOM_R_FLOAT:

.. _class_Mesh_constant_ARRAY_CUSTOM_RG_FLOAT:

.. _class_Mesh_constant_ARRAY_CUSTOM_RGB_FLOAT:

.. _class_Mesh_constant_ARRAY_CUSTOM_RGBA_FLOAT:

.. _class_Mesh_constant_ARRAY_CUSTOM_MAX:

enum **ArrayCustomFormat**:

- **ARRAY_CUSTOM_RGBA8_UNORM** = **0**

- **ARRAY_CUSTOM_RGBA8_SNORM** = **1**

- **ARRAY_CUSTOM_RG_HALF** = **2**

- **ARRAY_CUSTOM_RGBA_HALF** = **3**

- **ARRAY_CUSTOM_R_FLOAT** = **4**

- **ARRAY_CUSTOM_RG_FLOAT** = **5**

- **ARRAY_CUSTOM_RGB_FLOAT** = **6**

- **ARRAY_CUSTOM_RGBA_FLOAT** = **7**

- **ARRAY_CUSTOM_MAX** = **8** --- Represents the size of the :ref:`ArrayCustomFormat<enum_Mesh_ArrayCustomFormat>` enum.

----

.. _enum_Mesh_ArrayFormat:

.. _class_Mesh_constant_ARRAY_FORMAT_VERTEX:

.. _class_Mesh_constant_ARRAY_FORMAT_NORMAL:

.. _class_Mesh_constant_ARRAY_FORMAT_TANGENT:

.. _class_Mesh_constant_ARRAY_FORMAT_COLOR:

.. _class_Mesh_constant_ARRAY_FORMAT_TEX_UV:

.. _class_Mesh_constant_ARRAY_FORMAT_TEX_UV2:

.. _class_Mesh_constant_ARRAY_FORMAT_CUSTOM0:

.. _class_Mesh_constant_ARRAY_FORMAT_CUSTOM1:

.. _class_Mesh_constant_ARRAY_FORMAT_CUSTOM2:

.. _class_Mesh_constant_ARRAY_FORMAT_CUSTOM3:

.. _class_Mesh_constant_ARRAY_FORMAT_BONES:

.. _class_Mesh_constant_ARRAY_FORMAT_WEIGHTS:

.. _class_Mesh_constant_ARRAY_FORMAT_INDEX:

.. _class_Mesh_constant_ARRAY_FORMAT_BLEND_SHAPE_MASK:

.. _class_Mesh_constant_ARRAY_FORMAT_CUSTOM_BASE:

.. _class_Mesh_constant_ARRAY_FORMAT_CUSTOM_BITS:

.. _class_Mesh_constant_ARRAY_FORMAT_CUSTOM0_SHIFT:

.. _class_Mesh_constant_ARRAY_FORMAT_CUSTOM1_SHIFT:

.. _class_Mesh_constant_ARRAY_FORMAT_CUSTOM2_SHIFT:

.. _class_Mesh_constant_ARRAY_FORMAT_CUSTOM3_SHIFT:

.. _class_Mesh_constant_ARRAY_FORMAT_CUSTOM_MASK:

.. _class_Mesh_constant_ARRAY_COMPRESS_FLAGS_BASE:

.. _class_Mesh_constant_ARRAY_FLAG_USE_2D_VERTICES:

.. _class_Mesh_constant_ARRAY_FLAG_USE_DYNAMIC_UPDATE:

.. _class_Mesh_constant_ARRAY_FLAG_USE_8_BONE_WEIGHTS:

enum **ArrayFormat**:

- **ARRAY_FORMAT_VERTEX** = **1** --- Mesh array contains vertices. All meshes require a vertex array so this should always be present.

- **ARRAY_FORMAT_NORMAL** = **2** --- Mesh array contains normals.

- **ARRAY_FORMAT_TANGENT** = **4** --- Mesh array contains tangents.

- **ARRAY_FORMAT_COLOR** = **8** --- Mesh array contains colors.

- **ARRAY_FORMAT_TEX_UV** = **16** --- Mesh array contains UVs.

- **ARRAY_FORMAT_TEX_UV2** = **32** --- Mesh array contains second UV.

- **ARRAY_FORMAT_CUSTOM0** = **64**

- **ARRAY_FORMAT_CUSTOM1** = **128**

- **ARRAY_FORMAT_CUSTOM2** = **256**

- **ARRAY_FORMAT_CUSTOM3** = **512**

- **ARRAY_FORMAT_BONES** = **1024** --- Mesh array contains bones.

- **ARRAY_FORMAT_WEIGHTS** = **2048** --- Mesh array contains bone weights.

- **ARRAY_FORMAT_INDEX** = **4096** --- Mesh array uses indices.

- **ARRAY_FORMAT_BLEND_SHAPE_MASK** = **7**

- **ARRAY_FORMAT_CUSTOM_BASE** = **13**

- **ARRAY_FORMAT_CUSTOM_BITS** = **3**

- **ARRAY_FORMAT_CUSTOM0_SHIFT** = **13**

- **ARRAY_FORMAT_CUSTOM1_SHIFT** = **16**

- **ARRAY_FORMAT_CUSTOM2_SHIFT** = **19**

- **ARRAY_FORMAT_CUSTOM3_SHIFT** = **22**

- **ARRAY_FORMAT_CUSTOM_MASK** = **7**

- **ARRAY_COMPRESS_FLAGS_BASE** = **25**

- **ARRAY_FLAG_USE_2D_VERTICES** = **33554432** --- Flag used to mark that the array contains 2D vertices.

- **ARRAY_FLAG_USE_DYNAMIC_UPDATE** = **67108864**

- **ARRAY_FLAG_USE_8_BONE_WEIGHTS** = **134217728**

----

.. _enum_Mesh_BlendShapeMode:

.. _class_Mesh_constant_BLEND_SHAPE_MODE_NORMALIZED:

.. _class_Mesh_constant_BLEND_SHAPE_MODE_RELATIVE:

enum **BlendShapeMode**:

- **BLEND_SHAPE_MODE_NORMALIZED** = **0** --- Blend shapes are normalized.

- **BLEND_SHAPE_MODE_RELATIVE** = **1** --- Blend shapes are relative to base weight.

Property Descriptions
---------------------

.. _class_Mesh_property_lightmap_size_hint:

- :ref:`Vector2i<class_Vector2i>` **lightmap_size_hint**

+-----------+-------------------------------+
| *Default* | ``Vector2i(0, 0)``            |
+-----------+-------------------------------+
| *Setter*  | set_lightmap_size_hint(value) |
+-----------+-------------------------------+
| *Getter*  | get_lightmap_size_hint()      |
+-----------+-------------------------------+

Sets a hint to be used for lightmap resolution.

Method Descriptions
-------------------

.. _class_Mesh_method__get_aabb:

- :ref:`AABB<class_AABB>` **_get_aabb** **(** **)** |virtual| |const|

----

.. _class_Mesh_method__get_blend_shape_count:

- :ref:`int<class_int>` **_get_blend_shape_count** **(** **)** |virtual| |const|

----

.. _class_Mesh_method__get_blend_shape_name:

- :ref:`StringName<class_StringName>` **_get_blend_shape_name** **(** :ref:`int<class_int>` index **)** |virtual| |const|

----

.. _class_Mesh_method__get_surface_count:

- :ref:`int<class_int>` **_get_surface_count** **(** **)** |virtual| |const|

----

.. _class_Mesh_method__set_blend_shape_name:

- void **_set_blend_shape_name** **(** :ref:`int<class_int>` index, :ref:`StringName<class_StringName>` name **)** |virtual|

----

.. _class_Mesh_method__surface_get_array_index_len:

- :ref:`int<class_int>` **_surface_get_array_index_len** **(** :ref:`int<class_int>` index **)** |virtual| |const|

----

.. _class_Mesh_method__surface_get_array_len:

- :ref:`int<class_int>` **_surface_get_array_len** **(** :ref:`int<class_int>` index **)** |virtual| |const|

----

.. _class_Mesh_method__surface_get_arrays:

- :ref:`Array<class_Array>` **_surface_get_arrays** **(** :ref:`int<class_int>` index **)** |virtual| |const|

----

.. _class_Mesh_method__surface_get_blend_shape_arrays:

- :ref:`Array<class_Array>` **_surface_get_blend_shape_arrays** **(** :ref:`int<class_int>` index **)** |virtual| |const|

----

.. _class_Mesh_method__surface_get_format:

- :ref:`int<class_int>` **_surface_get_format** **(** :ref:`int<class_int>` index **)** |virtual| |const|

----

.. _class_Mesh_method__surface_get_lods:

- :ref:`Dictionary<class_Dictionary>` **_surface_get_lods** **(** :ref:`int<class_int>` index **)** |virtual| |const|

----

.. _class_Mesh_method__surface_get_material:

- :ref:`Material<class_Material>` **_surface_get_material** **(** :ref:`int<class_int>` index **)** |virtual| |const|

----

.. _class_Mesh_method__surface_get_primitive_type:

- :ref:`int<class_int>` **_surface_get_primitive_type** **(** :ref:`int<class_int>` index **)** |virtual| |const|

----

.. _class_Mesh_method__surface_set_material:

- void **_surface_set_material** **(** :ref:`int<class_int>` index, :ref:`Material<class_Material>` material **)** |virtual|

----

.. _class_Mesh_method_create_convex_shape:

- :ref:`Shape3D<class_Shape3D>` **create_convex_shape** **(** :ref:`bool<class_bool>` clean=true, :ref:`bool<class_bool>` simplify=false **)** |const|

Calculate a :ref:`ConvexPolygonShape3D<class_ConvexPolygonShape3D>` from the mesh.

If ``clean`` is ``true`` (default), duplicate and interior vertices are removed automatically. You can set it to ``false`` to make the process faster if not needed.

If ``simplify`` is ``true``, the geometry can be further simplified to reduce the amount of vertices. Disabled by default.

----

.. _class_Mesh_method_create_outline:

- :ref:`Mesh<class_Mesh>` **create_outline** **(** :ref:`float<class_float>` margin **)** |const|

Calculate an outline mesh at a defined offset (margin) from the original mesh.

\ **Note:** This method typically returns the vertices in reverse order (e.g. clockwise to counterclockwise).

----

.. _class_Mesh_method_create_trimesh_shape:

- :ref:`Shape3D<class_Shape3D>` **create_trimesh_shape** **(** **)** |const|

Calculate a :ref:`ConcavePolygonShape3D<class_ConcavePolygonShape3D>` from the mesh.

----

.. _class_Mesh_method_generate_triangle_mesh:

- :ref:`TriangleMesh<class_TriangleMesh>` **generate_triangle_mesh** **(** **)** |const|

Generate a :ref:`TriangleMesh<class_TriangleMesh>` from the mesh.

----

.. _class_Mesh_method_get_aabb:

- :ref:`AABB<class_AABB>` **get_aabb** **(** **)** |const|

Returns the smallest :ref:`AABB<class_AABB>` enclosing this mesh in local space. Not affected by ``custom_aabb``. See also :ref:`VisualInstance3D.get_transformed_aabb<class_VisualInstance3D_method_get_transformed_aabb>`.

\ **Note:** This is only implemented for :ref:`ArrayMesh<class_ArrayMesh>` and :ref:`PrimitiveMesh<class_PrimitiveMesh>`.

----

.. _class_Mesh_method_get_faces:

- :ref:`PackedVector3Array<class_PackedVector3Array>` **get_faces** **(** **)** |const|

Returns all the vertices that make up the faces of the mesh. Each three vertices represent one triangle.

----

.. _class_Mesh_method_get_surface_count:

- :ref:`int<class_int>` **get_surface_count** **(** **)** |const|

Returns the amount of surfaces that the ``Mesh`` holds.

----

.. _class_Mesh_method_surface_get_arrays:

- :ref:`Array<class_Array>` **surface_get_arrays** **(** :ref:`int<class_int>` surf_idx **)** |const|

Returns the arrays for the vertices, normals, uvs, etc. that make up the requested surface (see :ref:`ArrayMesh.add_surface_from_arrays<class_ArrayMesh_method_add_surface_from_arrays>`).

----

.. _class_Mesh_method_surface_get_blend_shape_arrays:

- :ref:`Array<class_Array>` **surface_get_blend_shape_arrays** **(** :ref:`int<class_int>` surf_idx **)** |const|

Returns the blend shape arrays for the requested surface.

----

.. _class_Mesh_method_surface_get_material:

- :ref:`Material<class_Material>` **surface_get_material** **(** :ref:`int<class_int>` surf_idx **)** |const|

Returns a :ref:`Material<class_Material>` in a given surface. Surface is rendered using this material.

----

.. _class_Mesh_method_surface_set_material:

- void **surface_set_material** **(** :ref:`int<class_int>` surf_idx, :ref:`Material<class_Material>` material **)**

Sets a :ref:`Material<class_Material>` for a given surface. Surface will be rendered using this material.

.. |virtual| replace:: :abbr:`virtual (This method should typically be overridden by the user to have any effect.)`
.. |const| replace:: :abbr:`const (This method has no side effects. It doesn't modify any of the instance's member variables.)`
.. |vararg| replace:: :abbr:`vararg (This method accepts any number of arguments after the ones described here.)`
.. |constructor| replace:: :abbr:`constructor (This method is used to construct a type.)`
.. |static| replace:: :abbr:`static (This method doesn't need an instance to be called, so it can be called directly using the class name.)`
.. |operator| replace:: :abbr:`operator (This method describes a valid operator to use with this type as left-hand operand.)`
