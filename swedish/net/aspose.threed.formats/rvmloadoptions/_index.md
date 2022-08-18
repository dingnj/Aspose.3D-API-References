---
title: RvmLoadOptions
second_title: Aspose.3D för .NET API-referens
description: Ladda alternativ för AVEVA Plant Design Management Systems RVM-fil.
type: docs
weight: 1320
url: /sv/net/aspose.threed.formats/rvmloadoptions/
---
## RvmLoadOptions class

Ladda alternativ för AVEVA Plant Design Management Systems RVM-fil.

```csharp
public class RvmLoadOptions : LoadOptions
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [RvmLoadOptions](rvmloadoptions#constructor)() | Konstruera en[`RvmLoadOptions`](../rvmloadoptions) instans |
| [RvmLoadOptions](rvmloadoptions#constructor_1)(FileContentType) | Konstruera en[`RvmLoadOptions`](../rvmloadoptions) instans |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [AttributePrefix](../../aspose.threed.formats/rvmloadoptions/attributeprefix) { get; set; } | Hämtar eller ställer in prefixet för attributen som definierades i externa attributfiler, Prefixet används för att undvika namnkonflikter, standardvärdet är "rvm:" |
| [CenterScene](../../aspose.threed.formats/rvmloadoptions/centerscene) { get; set; } | Centrera scenen efter att den har laddats. |
| [CylinderRadialSegments](../../aspose.threed.formats/rvmloadoptions/cylinderradialsegments) { get; set; } | Hämtar eller ställer in antalet cylinderns radiella segment, standardvärdet är 16 |
| [DishLatitudeSegments](../../aspose.threed.formats/rvmloadoptions/dishlatitudesegments) { get; set; } | Hämtar eller ställer in antalet skålens latitudsegment, standardvärdet är 8 |
| [DishLongitudeSegments](../../aspose.threed.formats/rvmloadoptions/dishlongitudesegments) { get; set; } | Hämtar eller ställer in antalet skålens longitudsegment, standardvärdet är 12 |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding) { get; set; } | Hämtar eller ställer in standardkodningen för textbaserade filer. Standardvärdet är null vilket betyder att importören/exportören kommer att bestämma vilken kodning som ska användas. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat) { get; } | Hämtar filformatet som anges i det aktuella alternativet Spara/Ladda. |
| [FileName](../../aspose.threed.formats/ioconfig/filename) { get; set; } | Filnamnet på den exporterande/importerande scenen. Detta är valfritt, men användbart när man serialiserar externa tillgångar som OBJ:s material. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem) { get; set; } | Tillåt användaren att hantera hur de externa beroenden ska hanteras under laddning/spara. |
| [GenerateMaterials](../../aspose.threed.formats/rvmloadoptions/generatematerials) { get; set; } | Generera material med slumpmässiga färger för varje objekt i scenen om färgtabellen inte exporteras i RVM-filen. Standardvärdet är true |
| [LookupAttributes](../../aspose.threed.formats/rvmloadoptions/lookupattributes) { get; set; } | Hämtar eller ställer in om attribut ska laddas från extern attributlistfil (.att/.attrib/.txt), standardvärdet är true. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths) { get; set; } | Vissa filer som OBJ beror på extern fil, sökvägarna gör det möjligt för Aspose.3D att leta efter extern fil att ladda. |
| [RectangularTorusSegments](../../aspose.threed.formats/rvmloadoptions/rectangulartorussegments) { get; set; } | Hämtar eller ställer in antalet rektangulära torus radiella segment, standardvärdet är 20 |
| [TorusTubularSegments](../../aspose.threed.formats/rvmloadoptions/torustubularsegments) { get; set; } | Hämtar eller ställer in antalet torus rörformiga segment, standardvärdet är 20 |

### Se även

* class [LoadOptions](../loadoptions)
* namnutrymme [Aspose.ThreeD.Formats](../../aspose.threed.formats)
* hopsättning [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->