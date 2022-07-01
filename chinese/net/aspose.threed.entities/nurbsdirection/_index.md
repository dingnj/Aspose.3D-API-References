---
title: NurbsDirection
second_title: Aspose.3D for .NET API 参考
description: 3DNurbsSurface./nurbssurface有两个方向U和V./nurbssurface/vNurbsDirection./nurbsdirection定义数据每个方向 一个方向实际上是一条 NURBS 曲线这意味着它也由它的Order./nurbsdirection/order定义一个KnotVectors./nurbsdirection/knotvectors和一组加权控制点在NurbsSurface./nurbssurface中定义
type: docs
weight: 470
url: /zh/net/aspose.threed.entities/nurbsdirection/
---
## NurbsDirection class

3D[`NurbsSurface`](../nurbssurface)有两个方向，U和[`V`](../nurbssurface/v)，[`NurbsDirection`](../nurbsdirection)定义数据每个方向。 一个方向实际上是一条 NURBS 曲线，这意味着它也由它的[`Order`](./order)定义，一个[`KnotVectors`](./knotvectors)和一组加权控制点（在[`NurbsSurface`](../nurbssurface)中定义）。

```csharp
public class NurbsDirection
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [NurbsDirection](nurbsdirection)() | 默认构造函数。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Count](../../aspose.threed.entities/nurbsdirection/count) { get; set; } | 获取或设置当前方向的控制点数。 |
| [Divisions](../../aspose.threed.entities/nurbsdirection/divisions) { get; set; } | 获取或设置当前方向相邻控制点之间的分割数。 |
| [KnotVectors](../../aspose.threed.entities/nurbsdirection/knotvectors) { get; } | 获取节点向量，它是一个参数值序列，用于确定控制点在何处以及如何影响 NURBS 曲线。 |
| [Multiplicity](../../aspose.threed.entities/nurbsdirection/multiplicity) { get; } | 获取多重性。 |
| [Order](../../aspose.threed.entities/nurbsdirection/order) { get; set; } | 获取或设置 NURBS 曲线的顺序，它定义了影响曲线上任何给定点的附近控制点的数量。 |
| [Type](../../aspose.threed.entities/nurbsdirection/type) { get; set; } | 获取或设置当前方向的类型。 |

### 也可以看看

* 命名空间 [Aspose.ThreeD.Entities](../../aspose.threed.entities)
* 部件 [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->