---
title: PolygonBuilder
second_title: Aspose.3D for .NET API Referansı
description: Çokgen oluşturmak için bir yardımcı sınıfMesh./mesh
type: docs
weight: 550
url: /tr/net/aspose.threed.entities/polygonbuilder/
---
## PolygonBuilder class

Çokgen oluşturmak için bir yardımcı sınıf[`Mesh`](../mesh)

```csharp
public sealed class PolygonBuilder
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [PolygonBuilder](polygonbuilder)(Mesh) | Yeni bir örneğini başlatır[`PolygonBuilder`](../polygonbuilder) sınıf. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [AddVertex](../../aspose.threed.entities/polygonbuilder/addvertex)(int) | Çokgen öğesine bir tepe noktası dizini ekler |
| [Begin](../../aspose.threed.entities/polygonbuilder/begin)() | Yeni bir çokgen eklemeye başlar |
| [End](../../aspose.threed.entities/polygonbuilder/end)() | Çokgen oluşturmayı tamamlar |

### Örnekler

Şuna eşittir: Tüm indeksler kullanıma hazırsa,[`CreatePolygon`](../mesh/createpolygon) tercih edilir, aksi halde[`PolygonBuilder`](../polygonbuilder) daha iyi bir seçim olur.

```csharp
PolygonBuilder builder = new PolygonBuilder(mesh);
builder.Begin();
builder.AddVertex(0);
builder.AddVertex(1);
builder.AddVertex(2);
Builder.End();
```

```csharp
int[] indices = new int[] {0, 1, 2};
mesh.CreatePolygon(indices);
```

### Ayrıca bakınız

* ad alanı [Aspose.ThreeD.Entities](../../aspose.threed.entities)
* toplantı [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->