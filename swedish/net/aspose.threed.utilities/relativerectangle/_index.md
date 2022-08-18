---
title: RelativeRectangle
second_title: Aspose.3D för .NET API-referens
description: Relativ rektangel Formeln mellan relativ komponent till absolut värde är Skala  Referensbredd  offset Så om vi vill att det ska representera ett absolut värde lämna alla skalfält noll och använd offsetfält istället.
type: docs
weight: 2600
url: /sv/net/aspose.threed.utilities/relativerectangle/
---
## RelativeRectangle structure

Relativ rektangel Formeln mellan relativ komponent till absolut värde är: Skala * (Referensbredd) + offset Så om vi vill att det ska representera ett absolut värde, lämna alla skalfält noll och använd offsetfält istället.

```csharp
public struct RelativeRectangle
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [OffsetHeight](../../aspose.threed.utilities/relativerectangle/offsetheight) { get; set; } | Hämtar eller ställer in offset för höjd |
| [OffsetWidth](../../aspose.threed.utilities/relativerectangle/offsetwidth) { get; set; } | Hämtar eller ställer in offset för width |
| [OffsetX](../../aspose.threed.utilities/relativerectangle/offsetx) { get; set; } | Hämtar eller ställer in offset för koordinat X |
| [OffsetY](../../aspose.threed.utilities/relativerectangle/offsety) { get; set; } | Hämtar eller ställer in offset för koordinat Y |
| [ScaleHeight](../../aspose.threed.utilities/relativerectangle/scaleheight) { get; set; } | Relativ höjd |
| [ScaleWidth](../../aspose.threed.utilities/relativerectangle/scalewidth) { get; set; } | Relativ bredd |
| [ScaleX](../../aspose.threed.utilities/relativerectangle/scalex) { get; set; } | Relativ koordinat X |
| [ScaleY](../../aspose.threed.utilities/relativerectangle/scaley) { get; set; } | Relativ koordinat Y |

## Metoder

| namn | Beskrivning |
| --- | --- |
| static [FromScale](../../aspose.threed.utilities/relativerectangle/fromscale)(float, float, float, float) | Konstruera en[`RelativeRectangle`](../relativerectangle) med alla offsetfält noll och skalfält från givna parametrar. |
| [ToAbsolute](../../aspose.threed.utilities/relativerectangle/toabsolute#toabsolute)(Rectangle) | Konvertera den relativa rektangeln till absolut rektangel |
| [ToAbsolute](../../aspose.threed.utilities/relativerectangle/toabsolute#toabsolute_1)(Size) | Konvertera den relativa rektangeln till absolut rektangel |
| override [ToString](../../aspose.threed.utilities/relativerectangle/tostring)() | Konverterar värdet av denna instans till aString. |

### Se även

* namnutrymme [Aspose.ThreeD.Utilities](../../aspose.threed.utilities)
* hopsättning [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->