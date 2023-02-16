---
title: Line
second_title: Aspose.3D voor .NET API-referentie
description: Een polylijn is een pad gedefinieerd door een set punten metControlPoints./geometry/controlpoints/  en verbonden doorSegments./line/segments/  wat betekent dat het ook een set van verbonden lijnsegmenten kan zijn. De lijn is meestal een lineair object wat betekent dat het niet kan worden gebruikt om een curve weer te geven om een curve weer te geven gebruiktNurbsCurve./nurbscurve/ .
type: docs
weight: 420
url: /nl/net/aspose.threed.entities/line/
---
## Line class

Een polylijn is een pad gedefinieerd door een set punten met[`ControlPoints`](../geometry/controlpoints/) , en verbonden door[`Segments`](./segments/) , wat betekent dat het ook een set van verbonden lijnsegmenten kan zijn. De lijn is meestal een lineair object, wat betekent dat het niet kan worden gebruikt om een curve weer te geven, om een curve weer te geven, gebruikt[`NurbsCurve`](../nurbscurve/) .

```csharp
public class Line : Curve
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [Line](line/#constructor)() | Initialiseert een nieuw exemplaar van het`Line` klasse. |
| [Line](line/#constructor_1)(string) | Initialiseert een nieuw exemplaar van het`Line` klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Color](../../aspose.threed.entities/curve/color/) { get; set; } | Haalt of stelt de kleur van de lijn in, standaardwaarde is wit(1, 1, 1) |
| [ControlPoints](../../aspose.threed.entities/line/controlpoints/) { get; } | Krijgt alle controlepunten |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Haalt op of stelt in of deze entiteit moet worden uitgesloten tijdens het exporteren. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Krijgt of stelt de naam in. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Haalt of stelt het eerste bovenliggende knooppunt in. Als het eerste bovenliggende knooppunt wordt ingesteld, wordt deze entiteit losgekoppeld van andere bovenliggende knooppunten. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Haalt alle bovenliggende knooppunten op, een entiteit kan worden gekoppeld aan meerdere bovenliggende knooppunten voor geometrie-instancing |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Haalt de verzameling van alle eigenschappen op. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Krijgt de scène waartoe dit object behoort |
| [Segments](../../aspose.threed.entities/line/segments/) { get; } | Krijgt de segmenten van de lijn |
| [Visible](../../aspose.threed.entities/line/visible/) { get; set; } | Krijgt of stelt in als de geometrie zichtbaar is |

## methoden

| Naam | Beschrijving |
| --- | --- |
| static [FromPoints](../../aspose.threed.entities/line/frompoints/)(params Vector3[]) | Construeer een`Line` instantie van een reeks punten. |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Vindt de eigenschap. Het kan een dynamische eigenschap zijn (gemaakt door CreateDynamicProperty/SetProperty) of native eigenschap (geïdentificeerd door zijn naam) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Haalt het begrenzingskader op van de huidige entiteit in het coördinatensysteem van de objectruimte. |
| override [GetEntityRendererKey](../../aspose.threed.entities/curve/getentityrendererkey/)() | Haalt de sleutel op van de entiteitsrenderer die is geregistreerd in de renderer |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Haal de waarde op van gespecificeerde eigenschap |
| [MakeDefaultIndices](../../aspose.threed.entities/line/makedefaultindices/)() | Genereer de reeks 0,1,2,3....[`ControlPoints`](../geometry/controlpoints/) .Lengte-1 tot[`Segments`](./segments/) zodat de ControlPoints kunnen worden gebruikt als een enkele lijn |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Verwijdert een dynamische eigenschap. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Verwijder de gespecificeerde eigenschap geïdentificeerd door name |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Stelt de waarde in van gespecificeerde eigenschap |

### Zie ook

* class [Curve](../curve/)
* naamruimte [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* montage [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->