---
title: CompositeCurve
second_title: Aspose.3D for.NETAPIリファレンス
description: ACompositeCurve./compositecurve/複数の曲線セグメントで構成されています.
type: docs
weight: 270
url: /ja/net/aspose.threed.entities/compositecurve/
---
## CompositeCurve class

A`CompositeCurve`複数の曲線セグメントで構成されています.

```csharp
public class CompositeCurve : Curve
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [CompositeCurve](compositecurve/)() | のコンストラクター`CompositeCurve` |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Color](../../aspose.threed.entities/curve/color/) { get; set; } | 線の色を取得または設定します。デフォルト値は白です(1, 1, 1) |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | エクスポート中にこのエンティティを除外するかどうかを取得または設定します。 |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | 名前を取得または設定します。 |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | 最初の親ノードを取得または設定します。最初の親ノードを設定すると、このエンティティは他の親ノードから切り離されます。 |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | すべての親ノードを取得します。ジオメトリのインスタンス化のためにエンティティを複数の親ノードにアタッチできます |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | すべてのプロパティのコレクションを取得します。 |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | このオブジェクトが属するシーンを取得します |
| [Segments](../../aspose.threed.entities/compositecurve/segments/) { get; } | 曲線のセグメント。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddSegment](../../aspose.threed.entities/compositecurve/addsegment/)(Curve, bool) |  |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | プロパティを検索します。 動的プロパティ (CreateDynamicProperty/SetProperty で作成) またはネイティブ プロパティ (名前で識別) を指定できます。 |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | オブジェクト空間座標系で現在のエンティティの境界ボックスを取得します. |
| override [GetEntityRendererKey](../../aspose.threed.entities/curve/getentityrendererkey/)() | レンダラーに登録されているエンティティ レンダラーのキーを取得します |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | 指定したプロパティの値を取得 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | 動的プロパティを削除します。 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | name で識別される指定されたプロパティを削除します |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | 指定されたプロパティの値を設定します |

## その他のメンバー

| 名前 | 説明 |
| --- | --- |
| class [Segment](compositecurve.segment/) |  |

### 関連項目

* class [Curve](../curve/)
* 名前空間 [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* 組み立て [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->