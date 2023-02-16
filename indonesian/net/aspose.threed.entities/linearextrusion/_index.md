---
title: LinearExtrusion
second_title: Aspose.3D untuk .NET API Referensi
description: Linear ekstrusi mengambil bentuk 2D sebagai input dan memperluas bentuk dalam dimensi ke3.
type: docs
weight: 430
url: /id/net/aspose.threed.entities/linearextrusion/
---
## LinearExtrusion class

Linear ekstrusi mengambil bentuk 2D sebagai input dan memperluas bentuk dalam dimensi ke-3.

```csharp
public class LinearExtrusion : Entity, IMeshConvertible
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [LinearExtrusion](linearextrusion/#constructor)() | Pembuat instance`LinearExtrusion` . |
| [LinearExtrusion](linearextrusion/#constructor_1)(Profile, double) | Pembuat instance`LinearExtrusion` . |

## Properti

| Nama | Keterangan |
| --- | --- |
| [Center](../../aspose.threed.entities/linearextrusion/center/) { get; set; } | Jika nilai ini salah, rentang Z ekstrusi linier adalah dari 0 hingga tinggi, jika tidak, rentangnya adalah dari -tinggi/2 hingga tinggi/2. |
| [Direction](../../aspose.threed.entities/linearextrusion/direction/) { get; set; } | Arah ekstrusi, nilai default adalah (0, 0, 1) |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Mendapat atau menyetel apakah akan mengecualikan entitas ini selama mengekspor. |
| [Height](../../aspose.threed.entities/linearextrusion/height/) { get; set; } | Tinggi geometri yang diekstrusi, nilai standarnya adalah 1,0 |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Mendapat atau menetapkan nama. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Mendapat atau menyetel simpul induk pertama, jika menyetel simpul induk pertama, entitas ini akan terlepas dari simpul induk lainnya. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Mendapat semua simpul induk, entitas dapat dilampirkan ke beberapa simpul induk untuk pembuatan geometri |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Mendapat koleksi semua properti. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Mendapat adegan tempat objek ini berada |
| [Shape](../../aspose.threed.entities/linearextrusion/shape/) { get; set; } | Bentuk dasar yang akan diekstrusi. |
| [Slices](../../aspose.threed.entities/linearextrusion/slices/) { get; set; } | Irisan geometri ekstrusi bengkok, nilai standarnya adalah 1. |
| [Twist](../../aspose.threed.entities/linearextrusion/twist/) { get; set; } | Jumlah derajat di mana bentuk diekstrusi. |
| [TwistOffset](../../aspose.threed.entities/linearextrusion/twistoffset/) { get; set; } | Offset yang digunakan untuk memutar, nilai defaultnya adalah (0, 0, 0). |

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
| [ToMesh](../../aspose.threed.entities/linearextrusion/tomesh/)() | Ubah ekstrusi menjadi mesh. |

### Lihat juga

* class [Entity](../../aspose.threed/entity/)
* interface [IMeshConvertible](../imeshconvertible/)
* ruang nama [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* perakitan [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->