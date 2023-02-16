---
title: CreatePolygon
second_title: Aspose.3D for.NETAPIリファレンス
description: で定義されたすべての頂点を持つ新しいポリゴンを作成しますindices. 頂点ごとにポリゴン頂点を作成するには使用してくださいPolygonBuilderaspose.threed.entities/polygonbuilder/.
type: docs
weight: 50
url: /ja/net/aspose.threed.entities/mesh/createpolygon/
---
## CreatePolygon(int[], int, int) {#createpolygon_3}

で定義されたすべての頂点を持つ新しいポリゴンを作成します*indices*. 頂点ごとにポリゴン頂点を作成するには、使用してください[`PolygonBuilder`](../../polygonbuilder/).

```csharp
public void CreatePolygon(int[] indices, int offset, int length)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| indices | Int32[] | ポリゴン インデックスの配列。各インデックスは、ポリゴンを形成するコントロール ポイントを指します。 |
| offset | Int32 | 最初のポリゴン インデックスのオフセット |
| length | Int32 | インデックスの長さ |

### 例

```csharp
int[] indices = new int[] {0, 1, 2};
mesh.CreatePolygon(indices);
```

### 関連項目

* class [Mesh](../)
* 名前空間 [Aspose.ThreeD.Entities](../../mesh/)
* 組み立て [Aspose.3D](../../../)

---

## CreatePolygon(int[]) {#createpolygon_2}

で定義されたすべての頂点を持つ新しいポリゴンを作成します*indices*. 頂点ごとにポリゴン頂点を作成するには、使用してください[`PolygonBuilder`](../../polygonbuilder/).

```csharp
public void CreatePolygon(int[] indices)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| indices | Int32[] | ポリゴン インデックスの配列。各インデックスは、ポリゴンを形成するコントロール ポイントを指します。 |

### 例

```csharp
int[] indices = new int[] {0, 1, 2};
mesh.CreatePolygon(indices);
```

### 関連項目

* class [Mesh](../)
* 名前空間 [Aspose.ThreeD.Entities](../../mesh/)
* 組み立て [Aspose.3D](../../../)

---

## CreatePolygon(int, int, int, int) {#createpolygon_1}

頂点が 4 つあるポリゴンを作成します (quad)

```csharp
public void CreatePolygon(int v1, int v2, int v3, int v4)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| v1 | Int32 | 最初の頂点のインデックス |
| v2 | Int32 | 番目の頂点のインデックス |
| v3 | Int32 | 番目の頂点のインデックス |
| v4 | Int32 | 番目の頂点のインデックス |

### 関連項目

* class [Mesh](../)
* 名前空間 [Aspose.ThreeD.Entities](../../mesh/)
* 組み立て [Aspose.3D](../../../)

---

## CreatePolygon(int, int, int) {#createpolygon}

3頂点のポリゴン(三角形)を作成

```csharp
public void CreatePolygon(int v1, int v2, int v3)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| v1 | Int32 | 最初の頂点のインデックス |
| v2 | Int32 | 番目の頂点のインデックス |
| v3 | Int32 | 番目の頂点のインデックス |

### 関連項目

* class [Mesh](../)
* 名前空間 [Aspose.ThreeD.Entities](../../mesh/)
* 組み立て [Aspose.3D](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->