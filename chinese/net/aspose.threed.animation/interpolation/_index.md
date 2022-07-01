---
title: Interpolation
second_title: Aspose.3D for .NET API 参考
description: 关键帧的插值类型
type: docs
weight: 80
url: /zh/net/aspose.threed.animation/interpolation/
---
## Interpolation enumeration

关键帧的插值类型。

```csharp
public enum Interpolation
```

### 价值观

| 姓名 | 价值 | 描述 |
| --- | --- | --- |
| Constant | `0` | 该值将保持为第一个点的值，直到下一段。 |
| Linear | `1` | 线性插值是两点之间的直线。 |
| Bezier | `2` | 贝塞尔或 Hermite 样条。 |
| BSpline | `3` | 基本样条由一系列控制点定义，保证曲线只经过第一个和最后一个点。 |
| CardinalSpline | `4` | 基数样条是三次 Hermite 样条，其切线由端点和张力参数定义。 |
| TCBSpline | `5` | 也称为 Kochanek-Bartels 样条，切线的行为由张力/偏差/连续性定义 |

### 也可以看看

* 命名空间 [Aspose.ThreeD.Animation](../../aspose.threed.animation)
* 部件 [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->