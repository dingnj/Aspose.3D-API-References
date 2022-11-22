﻿---
title: PbrMaterial class
second_title: Aspose.3D for Python via .NET API References
description: 
type: docs
weight: 30
url: /python-net/aspose.threed.shading/pbrmaterial/
is_root: false
---

## PbrMaterial class

Material for physically based rendering based on albedo color/metallic/roughness



The PbrMaterial type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [PbrMaterial()](/3d/python-net/aspose.threed.shading/pbrmaterial/__init__/#) | Construct a default PBR material instance |
| [PbrMaterial(albedo)](/3d/python-net/aspose.threed.shading/pbrmaterial/__init__/#System.Drawing.Color) | Construct a default PBR material with specified albedo color value. |


### Properties
| Property | Description |
| :- | :- |
| [name](/3d/python-net/aspose.threed.shading/pbrmaterial/name) | Gets or sets the name. |
| [properties](/3d/python-net/aspose.threed.shading/pbrmaterial/properties) | Gets the collection of all properties. |
| [MAP_SPECULAR](/3d/python-net/aspose.threed.shading/pbrmaterial/MAP_SPECULAR) |  |
| [MAP_DIFFUSE](/3d/python-net/aspose.threed.shading/pbrmaterial/MAP_DIFFUSE) |  |
| [MAP_EMISSIVE](/3d/python-net/aspose.threed.shading/pbrmaterial/MAP_EMISSIVE) |  |
| [MAP_AMBIENT](/3d/python-net/aspose.threed.shading/pbrmaterial/MAP_AMBIENT) |  |
| [MAP_NORMAL](/3d/python-net/aspose.threed.shading/pbrmaterial/MAP_NORMAL) |  |
| [transparency](/3d/python-net/aspose.threed.shading/pbrmaterial/transparency) | Gets or sets the transparency factor.
| [normal_texture](/3d/python-net/aspose.threed.shading/pbrmaterial/normal_texture) | Gets or sets the texture of normal mapping |
| [specular_texture](/3d/python-net/aspose.threed.shading/pbrmaterial/specular_texture) | Gets or sets the texture for specular color |
| [albedo_texture](/3d/python-net/aspose.threed.shading/pbrmaterial/albedo_texture) | Gets or sets the texture for albedo |
| [albedo](/3d/python-net/aspose.threed.shading/pbrmaterial/albedo) | Gets or sets the base color of the material |
| [occlusion_texture](/3d/python-net/aspose.threed.shading/pbrmaterial/occlusion_texture) | Gets or sets the texture for ambient occlusion |
| [occlusion_factor](/3d/python-net/aspose.threed.shading/pbrmaterial/occlusion_factor) | Gets or sets the factor of ambient occlusion |
| [metallic_factor](/3d/python-net/aspose.threed.shading/pbrmaterial/metallic_factor) | Gets or sets the metalness of the material, value of 1 means the material is a metal and value of 0 means the material is a dielectric. |
| [roughness_factor](/3d/python-net/aspose.threed.shading/pbrmaterial/roughness_factor) | Gets or sets the roughness of the material, value of 1 means the material is completely rough and value of 0 means the material is completely smooth |
| [metallic_roughness](/3d/python-net/aspose.threed.shading/pbrmaterial/metallic_roughness) | Gets or sets the texture for metallic(in R channel) and roughness(in G channel) |
| [emissive_texture](/3d/python-net/aspose.threed.shading/pbrmaterial/emissive_texture) | Gets or sets the texture for emissive |
| [emissive_color](/3d/python-net/aspose.threed.shading/pbrmaterial/emissive_color) | Gets or sets the emissive color |


### Methods
| Method | Description |
| :- | :- |
| [remove_property(property)](/3d/python-net/aspose.threed.shading/pbrmaterial/remove_property/#Property) | Removes a dynamic property. |
| [remove_property(property)](/3d/python-net/aspose.threed.shading/pbrmaterial/remove_property/#str) | Remove the specified property identified by name |
| [get_property(property)](/3d/python-net/aspose.threed.shading/pbrmaterial/get_property/#str) | Get the value of specified property |
| [set_property(property, value)](/3d/python-net/aspose.threed.shading/pbrmaterial/set_property/#str-any) | Sets the value of specified property |
| [find_property(property_name)](/3d/python-net/aspose.threed.shading/pbrmaterial/find_property/#str) | Finds the property.
| [get_texture(slot_name)](/3d/python-net/aspose.threed.shading/pbrmaterial/get_texture/#str) | Gets the texture from the specified slot, it can be material's property name or shader's parameter name |
| [set_texture(slot_name, texture)](/3d/python-net/aspose.threed.shading/pbrmaterial/set_texture/#str-TextureBase) | Sets the texture to specified slot |
| [from_material(material)](/3d/python-net/aspose.threed.shading/pbrmaterial/from_material/#Material) | Allow convert other material to PbrMaterial |


### See Also

* module [aspose.threed.shading](../)
* class [Material](/3d/python-net/aspose.threed.shading/material)