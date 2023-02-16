---
title: EllipseShape
second_title: Aspose.3D voor .NET API-referentie
description: IFCcompatibele ellipsvorm gedefinieerd door parameters. De middenpositie van het profiel bevindt zich in het midden van het begrenzingsvak.
type: docs
weight: 1540
url: /nl/net/aspose.threed.profiles/ellipseshape/
---
## EllipseShape class

IFC-compatibele ellipsvorm gedefinieerd door parameters. De middenpositie van het profiel bevindt zich in het midden van het begrenzingsvak.

```csharp
public class EllipseShape : ParameterizedProfile
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [EllipseShape](ellipseshape/)() | De standaard constructeur. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Haalt op of stelt in of deze entiteit moet worden uitgesloten tijdens het exporteren. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Krijgt of stelt de naam in. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Haalt of stelt het eerste bovenliggende knooppunt in. Als het eerste bovenliggende knooppunt wordt ingesteld, wordt deze entiteit losgekoppeld van andere bovenliggende knooppunten. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Haalt alle bovenliggende knooppunten op, een entiteit kan worden gekoppeld aan meerdere bovenliggende knooppunten voor geometrie-instancing |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Haalt de verzameling van alle eigenschappen op. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Krijgt de scène waartoe dit object behoort |
| [SemiAxis1](../../aspose.threed.profiles/ellipseshape/semiaxis1/) { get; set; } | Haalt of stelt de eerste straal in van de ellips die gemeten is in de richting van de x-as. |
| [SemiAxis2](../../aspose.threed.profiles/ellipseshape/semiaxis2/) { get; set; } | Haalt of stelt de tweede straal in van de ellips die gemeten is in de richting van de y-as. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Vindt de eigenschap. Het kan een dynamische eigenschap zijn (gemaakt door CreateDynamicProperty/SetProperty) of native eigenschap (geïdentificeerd door zijn naam) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Haalt het begrenzingskader op van de huidige entiteit in het coördinatensysteem van de objectruimte. |
| override [GetEntityRendererKey](../../aspose.threed.profiles/profile/getentityrendererkey/)() | Haalt de sleutel op van de entiteitsrenderer die is geregistreerd in de renderer |
| override [GetExtent](../../aspose.threed.profiles/ellipseshape/getextent/)() | Haalt het bereik op in x- en y-dimensie. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Haal de waarde op van gespecificeerde eigenschap |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Verwijdert een dynamische eigenschap. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Verwijder de gespecificeerde eigenschap geïdentificeerd door name |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Stelt de waarde in van gespecificeerde eigenschap |

### Zie ook

* class [ParameterizedProfile](../parameterizedprofile/)
* naamruimte [Aspose.ThreeD.Profiles](../../aspose.threed.profiles/)
* montage [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->