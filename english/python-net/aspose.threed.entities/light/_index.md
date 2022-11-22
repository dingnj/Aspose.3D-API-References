﻿---
title: Light class
second_title: Aspose.3D for Python via .NET API References
description: 
type: docs
weight: 150
url: /python-net/aspose.threed.entities/light/
is_root: false
---

## Light class

The light illuminates the scene.
            



            The formula to calculate the total attenuation of light is:
            `A = ConstantAttenuation + (Dist * LinearAttenuation) + ((Dist^2) * QuadraticAttenuation)`



The Light type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [Light()](/3d/python-net/aspose.threed.entities/light/__init__/#) | Initializes a new instance of the [Light](/3d/python-net/aspose.threed.entities/light) class. |
| [Light(name)](/3d/python-net/aspose.threed.entities/light/__init__/#str) | Initializes a new instance of the [Light](/3d/python-net/aspose.threed.entities/light) class. |
| [Light(name, type)](/3d/python-net/aspose.threed.entities/light/__init__/#str-LightType) |  |


### Properties
| Property | Description |
| :- | :- |
| [name](/3d/python-net/aspose.threed.entities/light/name) | Gets or sets the name. |
| [properties](/3d/python-net/aspose.threed.entities/light/properties) | Gets the collection of all properties. |
| [scene](/3d/python-net/aspose.threed.entities/light/scene) | Gets the scene that this object belongs to |
| [parent_nodes](/3d/python-net/aspose.threed.entities/light/parent_nodes) | Gets all parent nodes, an entity can be attached to multiple parent nodes for geometry instancing |
| [excluded](/3d/python-net/aspose.threed.entities/light/excluded) | Gets or sets whether to exclude this entity during exporting. |
| [parent_node](/3d/python-net/aspose.threed.entities/light/parent_node) | Gets or sets the first parent node, if set the first parent node, this entity will be detached from other parent nodes. |
| [rotation_mode](/3d/python-net/aspose.threed.entities/light/rotation_mode) | Gets or sets the frustum's orientation mode
| [near_plane](/3d/python-net/aspose.threed.entities/light/near_plane) | Gets or sets the frustum's near plane distance. |
| [far_plane](/3d/python-net/aspose.threed.entities/light/far_plane) | Gets or sets the frustum's far plane distance. |
| [aspect](/3d/python-net/aspose.threed.entities/light/aspect) | Gets or sets the aspect ratio of the frustum |
| [ortho_height](/3d/python-net/aspose.threed.entities/light/ortho_height) | Gets or sets the height when frustum in orthographic projection. |
| [up](/3d/python-net/aspose.threed.entities/light/up) | Gets or sets the up direction of the camera |
| [look_at](/3d/python-net/aspose.threed.entities/light/look_at) | Gets or sets the the interested position that the camera is looking at. |
| [direction](/3d/python-net/aspose.threed.entities/light/direction) | Gets or sets the direction that the camera is looking at.
| [target](/3d/python-net/aspose.threed.entities/light/target) | Gets or sets the target that the camera is looking at.
| [color](/3d/python-net/aspose.threed.entities/light/color) | Gets or sets the light's color |
| [light_type](/3d/python-net/aspose.threed.entities/light/light_type) | Gets or sets the light's type |
| [cast_light](/3d/python-net/aspose.threed.entities/light/cast_light) | Gets or sets if the current light instance can illuminate other objects. |
| [intensity](/3d/python-net/aspose.threed.entities/light/intensity) | Gets or sets the light's intensity, default value is 100 |
| [hot_spot](/3d/python-net/aspose.threed.entities/light/hot_spot) | Gets or sets the hot spot cone angle(in degrees). |
| [falloff](/3d/python-net/aspose.threed.entities/light/falloff) | Gets or sets the falloff cone angle (in degrees). |
| [constant_attenuation](/3d/python-net/aspose.threed.entities/light/constant_attenuation) | Gets or sets the constant attenuation to calculate the total attenuation of the light |
| [linear_attenuation](/3d/python-net/aspose.threed.entities/light/linear_attenuation) | Gets or sets the linear attenuation to calculate the total attenuation of the light |
| [quadratic_attenuation](/3d/python-net/aspose.threed.entities/light/quadratic_attenuation) | Gets or sets the quadratic attenuation to calculate the total attenuation of the light |
| [cast_shadows](/3d/python-net/aspose.threed.entities/light/cast_shadows) | Gets or sets if the light can cast shadows on other objects. |
| [shadow_color](/3d/python-net/aspose.threed.entities/light/shadow_color) | Gets or sets the shadow's color. |


### Methods
| Method | Description |
| :- | :- |
| [remove_property(property)](/3d/python-net/aspose.threed.entities/light/remove_property/#Property) | Removes a dynamic property. |
| [remove_property(property)](/3d/python-net/aspose.threed.entities/light/remove_property/#str) | Remove the specified property identified by name |
| [get_property(property)](/3d/python-net/aspose.threed.entities/light/get_property/#str) | Get the value of specified property |
| [set_property(property, value)](/3d/python-net/aspose.threed.entities/light/set_property/#str-any) | Sets the value of specified property |
| [find_property(property_name)](/3d/python-net/aspose.threed.entities/light/find_property/#str) | Finds the property.
| [get_bounding_box()](/3d/python-net/aspose.threed.entities/light/get_bounding_box/#) | Gets the bounding box of current entity in its object space coordinate system. |
| [get_entity_renderer_key()](/3d/python-net/aspose.threed.entities/light/get_entity_renderer_key/#) | Gets the key of the entity renderer registered in the renderer |


### See Also

* module [aspose.threed.entities](../)
* class [Frustum](/3d/python-net/aspose.threed.entities/frustum)