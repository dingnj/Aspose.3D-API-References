---
title: TransformedCurve
second_title: Aspose.3D für .NET-API-Referenz
description: ATransformedCurve./transformedcurve gibt einer Kurve eine Platzierung durch die Verwendung einer Transformationsmatrix. Dies erlaubt es eine Transformation innerhalb von a durchzuführenTrimmedCurve./trimmedcurve oderCompositeCurve./compositecurve .
type: docs
weight: 720
url: /de/net/aspose.threed.entities/transformedcurve/
---
## TransformedCurve class

A[`TransformedCurve`](../transformedcurve) gibt einer Kurve eine Platzierung durch die Verwendung einer Transformationsmatrix. Dies erlaubt es, eine Transformation innerhalb von a durchzuführen[`TrimmedCurve`](../trimmedcurve) oder[`CompositeCurve`](../compositecurve) .

```csharp
public class TransformedCurve : Curve
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [TransformedCurve](transformedcurve#constructor)() | Der Konstruktor von[`TransformedCurve`](../transformedcurve) |
| [TransformedCurve](transformedcurve#constructor_1)(Curve, Matrix4) | Der Konstruktor von[`TransformedCurve`](../transformedcurve) |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BasisCurve](../../aspose.threed.entities/transformedcurve/basiscurve) { get; set; } | Die Basiskurve. |
| [Color](../../aspose.threed.entities/curve/color) { get; set; } | Liest oder setzt die Farbe der Linie, Standardwert ist weiß(1, 1, 1) |
| [Excluded](../../aspose.threed/entity/excluded) { get; set; } | Ruft ab oder legt fest, ob diese Entität während des Exports ausgeschlossen werden soll. |
| virtual [Name](../../aspose.threed/a3dobject/name) { get; set; } | Ruft den Namen ab oder legt ihn fest. |
| [ParentNode](../../aspose.threed/entity/parentnode) { get; set; } | Ruft den ersten übergeordneten Knoten ab oder legt ihn fest. Wenn der erste übergeordnete Knoten festgelegt wird, wird diese Entität von anderen übergeordneten Knoten getrennt. |
| [ParentNodes](../../aspose.threed/entity/parentnodes) { get; } | Ruft alle übergeordneten Knoten ab, eine Entität kann an mehrere übergeordnete Knoten angehängt werden, um Geometrie zu instanziieren |
| [Properties](../../aspose.threed/a3dobject/properties) { get; } | Ruft die Sammlung aller Eigenschaften ab. |
| [Scene](../../aspose.threed/sceneobject/scene) { get; } | Ruft die Szene ab, zu der dieses Objekt gehört |
| [TransformMatrix](../../aspose.threed.entities/transformedcurve/transformmatrix) { get; set; } | Die Transformationsmatrix. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty)(string) | Findet die Eigenschaft. Es kann eine dynamische Eigenschaft sein (erstellt von CreateDynamicProperty/SetProperty) oder eine native Eigenschaft (identifiziert durch ihren Namen) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox)() | Ruft den Begrenzungsrahmen des aktuellen Objekts in seinem Objektraum-Koordinatensystem ab. |
| override [GetEntityRendererKey](../../aspose.threed.entities/curve/getentityrendererkey)() | Ruft den Schlüssel des Entity-Renderers ab, der im Renderer registriert ist |
| [GetProperty](../../aspose.threed/a3dobject/getproperty)(string) | Holen Sie sich den Wert der angegebenen Eigenschaft |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(Property) | Entfernt eine dynamische Eigenschaft. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(string) | Entfernt die angegebene Eigenschaft identifiziert durch name |
| [SetProperty](../../aspose.threed/a3dobject/setproperty)(string, object) | Legt den Wert der angegebenen Eigenschaft fest |

### Siehe auch

* class [Curve](../curve)
* namensraum [Aspose.ThreeD.Entities](../../aspose.threed.entities)
* Montage [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->