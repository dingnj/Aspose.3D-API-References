---
title: Property
second_title: Aspose.3D untuk .NET API Referensi
description: Kelas untuk menampung properti yang ditentukan pengguna.
type: docs
weight: 1670
url: /id/net/aspose.threed/property/
---
## Property class

Kelas untuk menampung properti yang ditentukan pengguna.

```csharp
public abstract class Property : A3DObject
```

## Properti

| Nama | Keterangan |
| --- | --- |
| override [Name](../../aspose.threed/property/name/) { set; } |  |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Mendapat koleksi semua properti. |
| abstract [Value](../../aspose.threed/property/value/) { get; set; } | Mendapat atau menetapkan nilai. |
| abstract [ValueType](../../aspose.threed/property/valuetype/) { get; } | Mendapatkan jenis nilai properti. |

## Metode

| Nama | Keterangan |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Menemukan properti. Ini bisa berupa properti dinamis (Dibuat oleh CreateDynamicProperty/SetProperty) atau properti asli (Diidentifikasi dengan namanya) |
| [GetBindPoint](../../aspose.threed/property/getbindpoint/)(AnimationNode, bool) | Mendapat titik ikatan properti pada instance animasi yang ditentukan. |
| [GetKeyframeSequence](../../aspose.threed/property/getkeyframesequence/)(AnimationNode, bool) | Mendapat urutan keyframe pada instance animasi yang ditentukan. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Dapatkan nilai properti yang ditentukan |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Menghapus properti dinamis. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Hapus properti yang ditentukan yang diidentifikasi dengan name |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Menetapkan nilai properti yang ditentukan |
| override [ToString](../../aspose.threed/property/tostring/)() | Mengembalikan string yang mewakili arus`Property` . |

### Lihat juga

* class [A3DObject](../a3dobject/)
* ruang nama [Aspose.ThreeD](../../aspose.threed/)
* perakitan [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->