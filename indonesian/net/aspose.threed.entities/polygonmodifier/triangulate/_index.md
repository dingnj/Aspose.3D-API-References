---
title: Triangulate
second_title: Aspose.3D untuk .NET API Referensi
description: Ubah semua mesh berbasis poligon menjadi mesh segitiga penuh
type: docs
weight: 70
url: /id/net/aspose.threed.entities/polygonmodifier/triangulate/
---
## Triangulate(Scene) {#triangulate_5}

Ubah semua mesh berbasis poligon menjadi mesh segitiga penuh

```csharp
public static void Triangulate(Scene scene)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| scene | Scene | Adegan untuk diproses |

### Lihat juga

* class [Scene](../../../aspose.threed/scene/)
* class [PolygonModifier](../)
* ruang nama [Aspose.ThreeD.Entities](../../polygonmodifier/)
* perakitan [Aspose.3D](../../../)

---

## Triangulate(Mesh) {#triangulate}

Mengubah mesh berbasis poligon menjadi mesh segitiga penuh

```csharp
public static Mesh Triangulate(Mesh mesh)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| mesh | Mesh | Jala non-segitiga asli |

### Nilai Pengembalian

Jaring segitiga baru yang dihasilkan

### Lihat juga

* class [Mesh](../../mesh/)
* class [PolygonModifier](../)
* ruang nama [Aspose.ThreeD.Entities](../../polygonmodifier/)
* perakitan [Aspose.3D](../../../)

---

## Triangulate(IList&lt;Vector4&gt;, IList&lt;int[]&gt;, bool, out Vector3[]) {#triangulate_4}

```csharp
public static int[][] Triangulate(IList<Vector4> controlPoints, IList<int[]> polygons, 
    bool generateNormals, out Vector3[] nor_out)
```

### Lihat juga

* struct [Vector4](../../../aspose.threed.utilities/vector4/)
* struct [Vector3](../../../aspose.threed.utilities/vector3/)
* class [PolygonModifier](../)
* ruang nama [Aspose.ThreeD.Entities](../../polygonmodifier/)
* perakitan [Aspose.3D](../../../)

---

## Triangulate(IList&lt;Vector4&gt;, IList&lt;int[]&gt;) {#triangulate_3}

```csharp
public static int[][] Triangulate(IList<Vector4> controlPoints, IList<int[]> polygons)
```

### Lihat juga

* struct [Vector4](../../../aspose.threed.utilities/vector4/)
* class [PolygonModifier](../)
* ruang nama [Aspose.ThreeD.Entities](../../polygonmodifier/)
* perakitan [Aspose.3D](../../../)

---

## Triangulate(IList&lt;Vector4&gt;, int[]) {#triangulate_2}

```csharp
public static int[][] Triangulate(IList<Vector4> controlPoints, int[] polygon)
```

### Lihat juga

* struct [Vector4](../../../aspose.threed.utilities/vector4/)
* class [PolygonModifier](../)
* ruang nama [Aspose.ThreeD.Entities](../../polygonmodifier/)
* perakitan [Aspose.3D](../../../)

---

## Triangulate(IList&lt;Vector4&gt;) {#triangulate_1}

```csharp
public static int[][] Triangulate(IList<Vector4> controlPoints)
```

### Lihat juga

* struct [Vector4](../../../aspose.threed.utilities/vector4/)
* class [PolygonModifier](../)
* ruang nama [Aspose.ThreeD.Entities](../../polygonmodifier/)
* perakitan [Aspose.3D](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->