---
title: ParameterizedProfile
second_title: Aspose.3D för .NET API-referens
description: Basklassen för alla parametriserade profiler.
type: docs
weight: 1600
url: /sv/net/aspose.threed.profiles/parameterizedprofile/
---
## ParameterizedProfile class

Basklassen för alla parametriserade profiler.

```csharp
public abstract class ParameterizedProfile : Profile
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Excluded](../../aspose.threed/entity/excluded) { get; set; } | Hämtar eller ställer in om den här entiteten ska exkluderas under export. |
| virtual [Name](../../aspose.threed/a3dobject/name) { get; set; } | Hämtar eller ställer in namnet. |
| [ParentNode](../../aspose.threed/entity/parentnode) { get; set; } | Hämtar eller ställer in den första överordnade noden, om den första överordnade noden ställs in, kommer denna enhet att frikopplas från andra överordnade noder. |
| [ParentNodes](../../aspose.threed/entity/parentnodes) { get; } | Hämtar alla överordnade noder, en enhet kan kopplas till flera överordnade noder för geometriinstansering |
| [Properties](../../aspose.threed/a3dobject/properties) { get; } | Hämtar samlingen av alla egenskaper. |
| [Scene](../../aspose.threed/sceneobject/scene) { get; } | Hämtar scenen som detta objekt tillhör |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty)(string) | Hittar egenskapen. Det kan vara en dynamisk egenskap (Skapad av CreateDynamicProperty/SetProperty) eller inbyggd egenskap (identifierad med dess namn) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox)() | Hämtar begränsningsrutan för nuvarande entitet i dess objektrymds koordinatsystem. |
| override [GetEntityRendererKey](../../aspose.threed.profiles/profile/getentityrendererkey)() | Hämtar nyckeln till entitetsrenderaren registrerad i renderaren |
| abstract [GetExtent](../../aspose.threed.profiles/parameterizedprofile/getextent)() | Får utsträckningen i x- och y-dimension. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty)(string) | Få värdet av specificerad egenskap |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(Property) | Tar bort en dynamisk egenskap. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(string) | Ta bort den angivna egenskapen identifierad av name |
| [SetProperty](../../aspose.threed/a3dobject/setproperty)(string, object) | Anger värdet för specificerad egenskap |

### Se även

* class [Profile](../profile)
* namnutrymme [Aspose.ThreeD.Profiles](../../aspose.threed.profiles)
* hopsättning [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->