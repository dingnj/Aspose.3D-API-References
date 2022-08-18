---
title: Box
second_title: Aspose.3D för .NET API-referens
description: Box.
type: docs
weight: 240
url: /sv/net/aspose.threed.entities/box/
---
## Box class

Box.

```csharp
public class Box : Primitive
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [Box](box#constructor)() | Initierar en ny instans av[`Box`](../box) class. |
| [Box](box#constructor_1)(double, double, double) | Initierar en ny instans av[`Box`](../box) class. |
| [Box](box#constructor_2)(string, double, double, double, int, int, int) | Initierar en ny instans av[`Box`](../box) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [CastShadows](../../aspose.threed.entities/primitive/castshadows) { get; set; } | Hämtar eller ställer in om denna geometri kan kasta skugga |
| [Excluded](../../aspose.threed/entity/excluded) { get; set; } | Hämtar eller ställer in om den här entiteten ska exkluderas under export. |
| [Height](../../aspose.threed.entities/box/height) { get; set; } | Hämtar eller ställer in höjden på rutan justerad i y-axeln. |
| [HeightSegments](../../aspose.threed.entities/box/heightsegments) { get; set; } | hämtar eller ställer in höjdsegmenten. |
| [Length](../../aspose.threed.entities/box/length) { get; set; } | Hämtar eller ställer in längden på rutan justerad i z-axeln. |
| [LengthSegments](../../aspose.threed.entities/box/lengthsegments) { get; set; } | Hämtar eller ställer in längdsegmenten. |
| virtual [Name](../../aspose.threed/a3dobject/name) { get; set; } | Hämtar eller ställer in namnet. |
| [ParentNode](../../aspose.threed/entity/parentnode) { get; set; } | Hämtar eller ställer in den första överordnade noden, om den första överordnade noden ställs in, kommer denna enhet att frikopplas från andra överordnade noder. |
| [ParentNodes](../../aspose.threed/entity/parentnodes) { get; } | Hämtar alla överordnade noder, en enhet kan kopplas till flera överordnade noder för geometriinstansering |
| [Properties](../../aspose.threed/a3dobject/properties) { get; } | Hämtar samlingen av alla egenskaper. |
| [ReceiveShadows](../../aspose.threed.entities/primitive/receiveshadows) { get; set; } | Hämtar eller ställer in om denna geometri kan ta emot skugga. |
| [Scene](../../aspose.threed/sceneobject/scene) { get; } | Hämtar scenen som detta objekt tillhör |
| [Width](../../aspose.threed.entities/box/width) { get; set; } | Hämtar eller ställer in bredden på rutan justerad i x-axeln. |
| [WidthSegments](../../aspose.threed.entities/box/widthsegments) { get; set; } | Hämtar eller ställer in breddsegmenten |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty)(string) | Hittar egenskapen. Det kan vara en dynamisk egenskap (Skapad av CreateDynamicProperty/SetProperty) eller inbyggd egenskap (identifierad med dess namn) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox)() | Hämtar begränsningsrutan för nuvarande entitet i dess objektrymds koordinatsystem. |
| virtual [GetEntityRendererKey](../../aspose.threed/entity/getentityrendererkey)() | Hämtar nyckeln till entitetsrenderaren registrerad i renderaren |
| [GetProperty](../../aspose.threed/a3dobject/getproperty)(string) | Få värdet av specificerad egenskap |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(Property) | Tar bort en dynamisk egenskap. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(string) | Ta bort den angivna egenskapen identifierad av name |
| [SetProperty](../../aspose.threed/a3dobject/setproperty)(string, object) | Anger värdet för specificerad egenskap |
| override [ToMesh](../../aspose.threed.entities/box/tomesh)() | Konvertera aktuellt objekt till mesh |

### Se även

* class [Primitive](../primitive)
* namnutrymme [Aspose.ThreeD.Entities](../../aspose.threed.entities)
* hopsättning [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->