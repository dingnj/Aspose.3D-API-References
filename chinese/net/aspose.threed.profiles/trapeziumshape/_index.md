---
title: TrapeziumShape
second_title: Aspose.3D for .NET API 参考
description: IFC 兼容梯形由参数定义
type: docs
weight: 1630
url: /zh/net/aspose.threed.profiles/trapeziumshape/
---
## TrapeziumShape class

IFC 兼容梯形由参数定义。

```csharp
public class TrapeziumShape : ParameterizedProfile
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [TrapeziumShape](trapeziumshape)() | [`TrapeziumShape`](../trapeziumshape) |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [BottomXDim](../../aspose.threed.profiles/trapeziumshape/bottomxdim) { get; set; } | 获取或设置底线沿 x 轴测量的范围。 |
| [Excluded](../../aspose.threed/entity/excluded) { get; set; } | 获取或设置是否在导出时排除该实体。 |
| virtual [Name](../../aspose.threed/a3dobject/name) { get; set; } | 获取或设置名称。 |
| [ParentNode](../../aspose.threed/entity/parentnode) { get; set; } | 获取或设置第一个父节点，如果设置了第一个父节点，该实体将与其他父节点分离。 |
| [ParentNodes](../../aspose.threed/entity/parentnodes) { get; } | 获取所有父节点，一个实体可以附加到多个父节点进行几何实例化 |
| [Properties](../../aspose.threed/a3dobject/properties) { get; } | 获取所有属性的集合。 |
| [Scene](../../aspose.threed/sceneobject/scene) { get; } | 获取该对象所属的场景 |
| [TopXDim](../../aspose.threed.profiles/trapeziumshape/topxdim) { get; set; } | 获取或设置顶线沿 x 轴测量的范围。 |
| [TopXOffset](../../aspose.threed.profiles/trapeziumshape/topxoffset) { get; set; } | 获取或设置从顶行开始到底行的偏移量。 |
| [YDim](../../aspose.threed.profiles/trapeziumshape/ydim) { get; set; } | 获取或设置沿 y 轴测量的顶线和底线之间的距离。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty)(string) | 查找属性。 可以是动态属性（由 CreateDynamicProperty/SetProperty 创建） 或本机属性（由其名称标识） |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox)() | 获取当前实体在其对象空间坐标系中的边界框。 |
| override [GetEntityRendererKey](../../aspose.threed.profiles/profile/getentityrendererkey)() | 获取在渲染器中注册的实体渲染器的key |
| override [GetExtent](../../aspose.threed.profiles/trapeziumshape/getextent)() | 获取 x 和 y 维度的范围。 |
| [GetProperty](../../aspose.threed/a3dobject/getproperty)(string) | 获取指定属性的值 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(Property) | 删除动态属性。 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(string) | 删除名称标识的指定属性 |
| [SetProperty](../../aspose.threed/a3dobject/setproperty)(string, object) | 设置指定属性的值 |

### 也可以看看

* class [ParameterizedProfile](../parameterizedprofile)
* 命名空间 [Aspose.ThreeD.Profiles](../../aspose.threed.profiles)
* 部件 [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->