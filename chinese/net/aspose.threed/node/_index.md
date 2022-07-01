---
title: Node
second_title: Aspose.3D for .NET API 参考
description: 表示场景图中的一个元素 场景图是 Node 对象的树树管理服务是自包含在这个类中的 注意 Aspose.3D SDK 不测试构建的场景图的有效性调用者有责任确保它不会在节点层次结构中生成循环图 除了树管理之外该类还定义了描述场景中对象位置所需的所有属性此信息包括基本的平移旋转和缩放属性以及用于枢轴限制和 IK 关节属性如刚度和阻尼的更高级选项 首次创建时Node对象是空的即它是一个没有任何图形表示只包含位置信息的对象在这种状态下它可以用来表示节点树结构中的父节点但仅此而已这种类型的对象的正常使用是为它们添加一个实体该实体将专门用于节点参见实体 实体本身就是一个对象并连接到节点这也意味着同一个实体可以在多个节点之间共享 CameraLightMesh 等等都是实体它们都派生自基类 Entity
type: docs
weight: 1460
url: /zh/net/aspose.threed/node/
---
## Node class

表示场景图中的一个元素。 场景图是 Node 对象的树。树管理服务是自包含在这个类中的。 注意 Aspose.3D SDK 不测试构建的场景图的有效性。调用者有责任确保它不会在节点层次结构中生成循环图。 除了树管理之外，该类还定义了描述场景中对象位置所需的所有属性。此信息包括基本的平移、旋转和缩放属性，以及用于枢轴、限制和 IK 关节属性（如刚度和阻尼）的更高级选项。 首次创建时，Node对象是“空的”（即:它是一个没有任何图形表示，只包含位置信息的对象）。在这种状态下，它可以用来表示节点树结构中的父节点，但仅此而已。这种类型的对象的正常使用是为它们添加一个实体，该实体将专门用于节点（参见“实体”）。 实体本身就是一个对象，并连接到节点。这也意味着同一个实体可以在多个节点之间共享。 Camera、Light、Mesh 等等……都是实体，它们都派生自基类 Entity。

```csharp
public class Node : SceneObject
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [Node](node#constructor)() | 初始化[`Node`](../node)类的新实例。 |
| [Node](node#constructor_1)(string) | 初始化[`Node`](../node)类的新实例。 |
| [Node](node#constructor_2)(string, Entity) | 初始化[`Node`](../node)类的新实例。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AssetInfo](../../aspose.threed/node/assetinfo) { get; set; } | 每节点资产信息 |
| [ChildNodes](../../aspose.threed/node/childnodes) { get; } | 获取子节点。 |
| [Entities](../../aspose.threed/node/entities) { get; } | 获取所有节点实体。 |
| [Entity](../../aspose.threed/node/entity) { get; set; } | 获取或设置连接到此节点的第一个实体，如果设置，将清除其他实体。 |
| [Excluded](../../aspose.threed/node/excluded) { get; set; } | 获取或设置是否在导出过程中排除该节点和所有子节点/实体。 |
| [GlobalTransform](../../aspose.threed/node/globaltransform) { get; } | 获取全局变换。 |
| [Material](../../aspose.threed/node/material) { get; set; } | 获取或设置与该节点关联的第一个材质，如果设置，将清除其他材质 |
| [Materials](../../aspose.threed/node/materials) { get; } | 获取与该节点关联的材质。 |
| [MetaDatas](../../aspose.threed/node/metadatas) { get; } | 获取此节点中定义的元数据。 |
| virtual [Name](../../aspose.threed/a3dobject/name) { get; set; } | 获取或设置名称。 |
| [ParentNode](../../aspose.threed/node/parentnode) { get; set; } | 获取或设置父节点。 |
| [Properties](../../aspose.threed/a3dobject/properties) { get; } | 获取所有属性的集合。 |
| [Scene](../../aspose.threed/sceneobject/scene) { get; } | 获取该对象所属的场景 |
| [Transform](../../aspose.threed/node/transform) { get; } | 获取本地变换。 |
| [Visible](../../aspose.threed/node/visible) { get; set; } | 获取或设置显示节点 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [Accept](../../aspose.threed/node/accept)(NodeVisitor) | 遍历所有后代节点（包括当前节点）并调用该节点的访问者。 访问者可以通过返回 false |
| [AddChildNode](../../aspose.threed/node/addchildnode)(Node) | 给这个节点添加一个子节点 |
| [AddEntity](../../aspose.threed/node/addentity)(Entity) | 将实体添加到节点。 |
| [CreateChildNode](../../aspose.threed/node/createchildnode#createchildnode)() | 创建子节点 |
| [CreateChildNode](../../aspose.threed/node/createchildnode#createchildnode_1)(Entity) | 创建一个附加给定实体的新子节点 |
| [CreateChildNode](../../aspose.threed/node/createchildnode#createchildnode_2)(string) | 创建一个给定节点名称的新子节点 |
| [CreateChildNode](../../aspose.threed/node/createchildnode#createchildnode_3)(string, Entity) | 创建一个给定节点名称的新子节点 |
| [CreateChildNode](../../aspose.threed/node/createchildnode#createchildnode_4)(string, Entity, Material) | 使用给定的节点名称创建一个新的子节点，并附加指定的实体和材质 |
| [EvaluateGlobalTransform](../../aspose.threed/node/evaluateglobaltransform)(bool) | 评估全局变换，是否包含几何变换。 |
| [FindProperty](../../aspose.threed/a3dobject/findproperty)(string) | 查找属性。 可以是动态属性（由 CreateDynamicProperty/SetProperty 创建） 或本机属性（由其名称标识） |
| [GetBoundingBox](../../aspose.threed/node/getboundingbox)() | 计算节点的边界框 |
| [GetChild](../../aspose.threed/node/getchild#getchild)(int) | 获取指定索引处的子节点。 |
| [GetChild](../../aspose.threed/node/getchild#getchild_1)(string) | 获取指定名称的子节点 |
| [GetEntity&lt;T&gt;](../../aspose.threed/node/getentity)() |  |
| [GetProperty](../../aspose.threed/a3dobject/getproperty)(string) | 获取指定属性的值 |
| [Merge](../../aspose.threed/node/merge)(Node) | 分离节点下的所有内容并将它们附加到当前节点。 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(Property) | 删除动态属性。 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(string) | 删除名称标识的指定属性 |
| [SelectObjects](../../aspose.threed/node/selectobjects)(string) | 使用类似 XPath 的查询语法选择当前节点下的多个对象。 |
| [SelectSingleObject](../../aspose.threed/node/selectsingleobject)(string) | 使用类似 XPath 的查询语法选择当前节点下的单个对象。 |
| [SetProperty](../../aspose.threed/a3dobject/setproperty)(string, object) | 设置指定属性的值 |
| override [ToString](../../aspose.threed/node/tostring)() | 获取此节点的字符串表示形式。 |

### 也可以看看

* class [SceneObject](../sceneobject)
* 命名空间 [Aspose.ThreeD](../../aspose.threed)
* 部件 [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->