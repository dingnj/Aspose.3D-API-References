---
title: ZShape
second_title: Aspose.3D für .NET-API-Referenz
description: IFC-kompatibles Z-Profil definiert durch Parameter.
type: docs
weight: 1660
url: /de/net/aspose.threed.profiles/zshape/
---
## ZShape class

IFC-kompatibles Z-Profil, definiert durch Parameter.

```csharp
public class ZShape : ParameterizedProfile
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [ZShape](zshape)() | Konstrukteur von[`ZShape`](../zshape) |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Depth](../../aspose.threed.profiles/zshape/depth) { get; set; } | Ruft die Länge des Webs ab oder legt sie fest. |
| [EdgeRadius](../../aspose.threed.profiles/zshape/edgeradius) { get; set; } | Ruft den Radius der Flanschkante ab oder legt ihn fest. |
| [Excluded](../../aspose.threed/entity/excluded) { get; set; } | Ruft ab oder legt fest, ob diese Entität während des Exports ausgeschlossen werden soll. |
| [FilletRadius](../../aspose.threed.profiles/zshape/filletradius) { get; set; } | Ruft den Rundungsradius zwischen Flansch und Steg ab oder legt ihn fest. |
| [FlangeThickness](../../aspose.threed.profiles/zshape/flangethickness) { get; set; } | Ruft die Dicke des Flansches ab oder legt sie fest. |
| [FlangeWidth](../../aspose.threed.profiles/zshape/flangewidth) { get; set; } | Ruft die Länge des Flansches ab oder legt sie fest. |
| virtual [Name](../../aspose.threed/a3dobject/name) { get; set; } | Ruft den Namen ab oder legt ihn fest. |
| [ParentNode](../../aspose.threed/entity/parentnode) { get; set; } | Ruft den ersten übergeordneten Knoten ab oder legt ihn fest. Wenn der erste übergeordnete Knoten festgelegt wird, wird diese Entität von anderen übergeordneten Knoten getrennt. |
| [ParentNodes](../../aspose.threed/entity/parentnodes) { get; } | Ruft alle übergeordneten Knoten ab, eine Entität kann an mehrere übergeordnete Knoten angehängt werden, um Geometrie zu instanziieren |
| [Properties](../../aspose.threed/a3dobject/properties) { get; } | Ruft die Sammlung aller Eigenschaften ab. |
| [Scene](../../aspose.threed/sceneobject/scene) { get; } | Ruft die Szene ab, zu der dieses Objekt gehört |
| [WebThickness](../../aspose.threed.profiles/zshape/webthickness) { get; set; } | Ruft die Dicke der Wand ab oder legt sie fest. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty)(string) | Findet die Eigenschaft. Es kann eine dynamische Eigenschaft sein (erstellt von CreateDynamicProperty/SetProperty) oder eine native Eigenschaft (identifiziert durch ihren Namen) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox)() | Ruft den Begrenzungsrahmen des aktuellen Objekts in seinem Objektraum-Koordinatensystem ab. |
| override [GetEntityRendererKey](../../aspose.threed.profiles/profile/getentityrendererkey)() | Ruft den Schlüssel des Entity-Renderers ab, der im Renderer registriert ist |
| override [GetExtent](../../aspose.threed.profiles/zshape/getextent)() | Ruft die Ausdehnung in x- und y-Dimension ab. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty)(string) | Holen Sie sich den Wert der angegebenen Eigenschaft |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(Property) | Entfernt eine dynamische Eigenschaft. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(string) | Entfernt die angegebene Eigenschaft identifiziert durch name |
| [SetProperty](../../aspose.threed/a3dobject/setproperty)(string, object) | Legt den Wert der angegebenen Eigenschaft fest |

### Siehe auch

* class [ParameterizedProfile](../parameterizedprofile)
* namensraum [Aspose.ThreeD.Profiles](../../aspose.threed.profiles)
* Montage [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->