﻿---
title: Transform class
second_title: Aspose.3D for Python via .NET API References
description: 
type: docs
weight: 210
url: /python-net/aspose.threed/transform/
is_root: false
---

## Transform class

A transform contains information that allow access to object's translate/scale/rotation or transform matrix at minimum cost
            This is used by local transform.



The Transform type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [name](/3d/python-net/aspose.threed/transform/name) | Gets or sets the name. |
| [properties](/3d/python-net/aspose.threed/transform/properties) | Gets the collection of all properties. |
| [geometric_translation](/3d/python-net/aspose.threed/transform/geometric_translation) | Gets or sets the geometric translation. 
| [geometric_scaling](/3d/python-net/aspose.threed/transform/geometric_scaling) | Gets or sets the geometric scaling. 
| [geometric_rotation](/3d/python-net/aspose.threed/transform/geometric_rotation) | Gets or sets the geometric Euler rotation(measured in degree). 
| [translation](/3d/python-net/aspose.threed/transform/translation) | Gets or sets the translation |
| [scale](/3d/python-net/aspose.threed/transform/scale) | Gets or sets the scale |
| [pre_rotation](/3d/python-net/aspose.threed/transform/pre_rotation) | Gets or sets the pre-rotation represented in degree |
| [post_rotation](/3d/python-net/aspose.threed/transform/post_rotation) | Gets or sets the post-rotation represented in degree |
| [euler_angles](/3d/python-net/aspose.threed/transform/euler_angles) | Gets or sets the rotation represented in Euler angles, measured in degree |
| [rotation](/3d/python-net/aspose.threed/transform/rotation) | Gets or sets the rotation represented in quaternion. |
| [transform_matrix](/3d/python-net/aspose.threed/transform/transform_matrix) | Gets or sets the transform matrix. |


### Methods
| Method | Description |
| :- | :- |
| [remove_property(property)](/3d/python-net/aspose.threed/transform/remove_property/#Property) | Removes a dynamic property. |
| [remove_property(property)](/3d/python-net/aspose.threed/transform/remove_property/#str) | Remove the specified property identified by name |
| [get_property(property)](/3d/python-net/aspose.threed/transform/get_property/#str) | Get the value of specified property |
| [set_property(property, value)](/3d/python-net/aspose.threed/transform/set_property/#str-any) | Sets the value of specified property |
| [find_property(property_name)](/3d/python-net/aspose.threed/transform/find_property/#str) | Finds the property.
| [set_geometric_translation(x, y, z)](/3d/python-net/aspose.threed/transform/set_geometric_translation/#float-float-float) | Sets the geometric translation. 
| [set_geometric_scaling(sx, sy, sz)](/3d/python-net/aspose.threed/transform/set_geometric_scaling/#float-float-float) | Sets the geometric scaling. 
| [set_geometric_rotation(rx, ry, rz)](/3d/python-net/aspose.threed/transform/set_geometric_rotation/#float-float-float) | Sets the geometric Euler rotation(measured in degree). 
| [set_translation(tx, ty, tz)](/3d/python-net/aspose.threed/transform/set_translation/#float-float-float) | Sets the translation of current transform. |
| [set_scale(sx, sy, sz)](/3d/python-net/aspose.threed/transform/set_scale/#float-float-float) | Sets the scale of current transform. |
| [set_euler_angles(rx, ry, rz)](/3d/python-net/aspose.threed/transform/set_euler_angles/#float-float-float) | Sets the Euler angles in degrees of current transform. |
| [set_rotation(rw, rx, ry, rz)](/3d/python-net/aspose.threed/transform/set_rotation/#float-float-float-float) | Sets the rotation(as quaternion components) of current transform. |
| [set_pre_rotation(rx, ry, rz)](/3d/python-net/aspose.threed/transform/set_pre_rotation/#float-float-float) | Sets the pre-rotation represented in degree |
| [set_post_rotation(rx, ry, rz)](/3d/python-net/aspose.threed/transform/set_post_rotation/#float-float-float) | Sets the post-rotation represented in degree |


### See Also

* module [aspose.threed](../)
* class [A3DObject](/3d/python-net/aspose.threed/a3dobject)