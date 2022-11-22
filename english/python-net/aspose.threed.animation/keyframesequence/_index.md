﻿---
title: KeyframeSequence class
second_title: Aspose.3D for Python via .NET API References
description: 
type: docs
weight: 70
url: /python-net/aspose.threed.animation/keyframesequence/
is_root: false
---

## KeyframeSequence class

The sequence of key-frames, it describes the transformation of a sampled value over time.



The KeyframeSequence type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [KeyframeSequence(name)](/3d/python-net/aspose.threed.animation/keyframesequence/__init__/#str) | Initializes a new instance of the [KeyframeSequence](/3d/python-net/aspose.threed.animation/keyframesequence) class. |
| [KeyframeSequence()](/3d/python-net/aspose.threed.animation/keyframesequence/__init__/#) | Initializes a new instance of the [KeyframeSequence](/3d/python-net/aspose.threed.animation/keyframesequence) class. |


### Properties
| Property | Description |
| :- | :- |
| [name](/3d/python-net/aspose.threed.animation/keyframesequence/name) | Gets or sets the name. |
| [properties](/3d/python-net/aspose.threed.animation/keyframesequence/properties) | Gets the collection of all properties. |
| [bind_point](/3d/python-net/aspose.threed.animation/keyframesequence/bind_point) | Gets the property bind point which owns this curve |
| [key_frames](/3d/python-net/aspose.threed.animation/keyframesequence/key_frames) | Gets the key frames of this curve. |
| [post_behavior](/3d/python-net/aspose.threed.animation/keyframesequence/post_behavior) | Gets the post behavior indicates what the sampled value should be after the last key frame. |
| [pre_behavior](/3d/python-net/aspose.threed.animation/keyframesequence/pre_behavior) | Gets the pre behavior indicates what the sampled value should be before the first key. |


### Methods
| Method | Description |
| :- | :- |
| [remove_property(property)](/3d/python-net/aspose.threed.animation/keyframesequence/remove_property/#Property) | Removes a dynamic property. |
| [remove_property(property)](/3d/python-net/aspose.threed.animation/keyframesequence/remove_property/#str) | Remove the specified property identified by name |
| [add(time, value)](/3d/python-net/aspose.threed.animation/keyframesequence/add/#float-float) | Create a new key frame with specified value |
| [add(time, value, interpolation)](/3d/python-net/aspose.threed.animation/keyframesequence/add/#float-float-Interpolation) | Create a new key frame with specified value |
| [get_property(property)](/3d/python-net/aspose.threed.animation/keyframesequence/get_property/#str) | Get the value of specified property |
| [set_property(property, value)](/3d/python-net/aspose.threed.animation/keyframesequence/set_property/#str-any) | Sets the value of specified property |
| [find_property(property_name)](/3d/python-net/aspose.threed.animation/keyframesequence/find_property/#str) | Finds the property.
| [reset()](/3d/python-net/aspose.threed.animation/keyframesequence/reset/#) | Removes all key frames and reset the post/pre behaviors. |


### See Also

* module [aspose.threed.animation](../)
* class [A3DObject](/3d/python-net/aspose.threed.animation/a3dobject)