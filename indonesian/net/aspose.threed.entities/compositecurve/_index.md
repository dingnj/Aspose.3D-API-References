---
title: CompositeCurve
second_title: Aspose.3D untuk .NET API Referensi
description: ACompositeCurve./compositecurve/ terdiri dari beberapa segmen kurva.
type: docs
weight: 270
url: /id/net/aspose.threed.entities/compositecurve/
---
## CompositeCurve class

A`CompositeCurve` terdiri dari beberapa segmen kurva.

```csharp
public class CompositeCurve : Curve
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [CompositeCurve](compositecurve/)() | Pembuat dari`CompositeCurve` |

## Properti

| Nama | Keterangan |
| --- | --- |
| [Color](../../aspose.threed.entities/curve/color/) { get; set; } | Mendapat atau mengatur warna garis, nilai default adalah putih(1, 1, 1) |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Mendapat atau menyetel apakah akan mengecualikan entitas ini selama mengekspor. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Mendapat atau menetapkan nama. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Mendapat atau menyetel simpul induk pertama, jika menyetel simpul induk pertama, entitas ini akan terlepas dari simpul induk lainnya. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Mendapat semua simpul induk, entitas dapat dilampirkan ke beberapa simpul induk untuk pembuatan geometri |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Mendapat koleksi semua properti. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Mendapat adegan tempat objek ini berada |
| [Segments](../../aspose.threed.entities/compositecurve/segments/) { get; } | Segmen kurva. |

## Metode

| Nama | Keterangan |
| --- | --- |
| [AddSegment](../../aspose.threed.entities/compositecurve/addsegment/)(Curve, bool) |  |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Menemukan properti. Ini bisa berupa properti dinamis (Dibuat oleh CreateDynamicProperty/SetProperty) atau properti asli (Diidentifikasi dengan namanya) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Mendapat kotak pembatas entitas saat ini dalam sistem koordinat ruang objeknya. |
| override [GetEntityRendererKey](../../aspose.threed.entities/curve/getentityrendererkey/)() | Mendapat kunci dari perender entitas yang terdaftar di perender |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Dapatkan nilai properti yang ditentukan |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Menghapus properti dinamis. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Hapus properti yang ditentukan yang diidentifikasi dengan name |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Menetapkan nilai properti yang ditentukan |

## Anggota lainnya

| Nama | Keterangan |
| --- | --- |
| class [Segment](compositecurve.segment/) |  |

### Lihat juga

* class [Curve](../curve/)
* ruang nama [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* perakitan [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->