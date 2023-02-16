---
title: RevolvedAreaSolid
second_title: Aspose.3D untuk .NET API Referensi
description: Kelas ini mewakili model solid dengan memutar penampang yang disediakan oleh profil tentang sumbu.
type: docs
weight: 620
url: /id/net/aspose.threed.entities/revolvedareasolid/
---
## RevolvedAreaSolid class

Kelas ini mewakili model solid dengan memutar penampang yang disediakan oleh profil tentang sumbu.

```csharp
public class RevolvedAreaSolid : Entity, IMeshConvertible
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [RevolvedAreaSolid](revolvedareasolid/)() | Konstruktor default. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [AngleEnd](../../aspose.threed.entities/revolvedareasolid/angleend/) { get; set; } | Mendapatkan atau mengatur sudut akhir dari prosedur bergulir, diukur dalam radian, nilai defaultnya adalah pi. |
| [AngleStart](../../aspose.threed.entities/revolvedareasolid/anglestart/) { get; set; } | Mendapat atau mengatur sudut awal dari prosedur bergulir, diukur dalam radian, nilai default adalah 0. |
| [Axis](../../aspose.threed.entities/revolvedareasolid/axis/) { get; set; } | Mendapat atau mengatur arah sumbu, nilai default adalah (0, 1, 0). |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Mendapat atau menyetel apakah akan mengecualikan entitas ini selama mengekspor. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Mendapat atau menetapkan nama. |
| [Origin](../../aspose.threed.entities/revolvedareasolid/origin/) { get; set; } | Mendapat atau mengatur titik asal putaran, nilai default adalah (0, 0, 0). |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Mendapat atau menyetel simpul induk pertama, jika menyetel simpul induk pertama, entitas ini akan terlepas dari simpul induk lainnya. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Mendapat semua simpul induk, entitas dapat dilampirkan ke beberapa simpul induk untuk pembuatan geometri |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Mendapat koleksi semua properti. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Mendapat adegan tempat objek ini berada |
| [Shape](../../aspose.threed.entities/revolvedareasolid/shape/) { get; set; } | Mendapat atau menyetel profil dasar yang digunakan untuk berputar. |

## Metode

| Nama | Keterangan |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Menemukan properti. Ini bisa berupa properti dinamis (Dibuat oleh CreateDynamicProperty/SetProperty) atau properti asli (Diidentifikasi dengan namanya) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Mendapat kotak pembatas entitas saat ini dalam sistem koordinat ruang objeknya. |
| virtual [GetEntityRendererKey](../../aspose.threed/entity/getentityrendererkey/)() | Mendapat kunci dari perender entitas yang terdaftar di perender |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Dapatkan nilai properti yang ditentukan |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Menghapus properti dinamis. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Hapus properti yang ditentukan yang diidentifikasi dengan name |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Menetapkan nilai properti yang ditentukan |
| [ToMesh](../../aspose.threed.entities/revolvedareasolid/tomesh/)() | Konversikan`RevolvedAreaSolid` menjadi jaring. |

### Lihat juga

* class [Entity](../../aspose.threed/entity/)
* interface [IMeshConvertible](../imeshconvertible/)
* ruang nama [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* perakitan [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->