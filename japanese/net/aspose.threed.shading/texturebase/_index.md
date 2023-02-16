---
title: TextureBase
second_title: Aspose.3D for.NETAPIリファレンス
description: すべてのコンクリート テクスチャの基本クラス テクスチャはジオメトリ サーフェスのルック アンド フィールを定義します
type: docs
weight: 2360
url: /ja/net/aspose.threed.shading/texturebase/
---
## TextureBase class

すべてのコンクリート テクスチャの基本クラス。 テクスチャは、ジオメトリ サーフェスのルック アンド フィールを定義します。

```csharp
public class TextureBase : A3DObject
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [TextureBase](texturebase/)(string) | の新しいインスタンスを初期化します`TextureBase`class. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Alpha](../../aspose.threed.shading/texturebase/alpha/) { get; set; } | テクスチャのデフォルトのアルファ値を取得または設定します これは、[`AlphaSource`](./alphasource/)はPixelAlpha デフォルト値は 1.0、有効な値の範囲は 0 ～ 1 です。 |
| [AlphaSource](../../aspose.threed.shading/texturebase/alphasource/) { get; set; } | テクスチャがアルファ チャネルを定義するかどうかを取得または設定します。 デフォルト値はNone |
| [MagFilter](../../aspose.threed.shading/texturebase/magfilter/) { get; set; } | 倍率のフィルターを取得または設定します。 |
| [MinFilter](../../aspose.threed.shading/texturebase/minfilter/) { get; set; } | 縮小用のフィルターを取得または設定します。 |
| [MipFilter](../../aspose.threed.shading/texturebase/mipfilter/) { get; set; } | ミップレベル サンプリングのフィルターを取得または設定します。 |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | 名前を取得または設定します。 |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | すべてのプロパティのコレクションを取得します。 |
| [UVRotation](../../aspose.threed.shading/texturebase/uvrotation/) { get; set; } | texture の回転を取得または設定します |
| [UVScale](../../aspose.threed.shading/texturebase/uvscale/) { get; set; } | UV スケールを取得または設定します。 |
| [UVTranslation](../../aspose.threed.shading/texturebase/uvtranslation/) { get; set; } | UV 変換を取得または設定します。 |
| [WrapModeU](../../aspose.threed.shading/texturebase/wrapmodeu/) { get; set; } | U. でテクスチャ ラップ モードを取得または設定します。 |
| [WrapModeV](../../aspose.threed.shading/texturebase/wrapmodev/) { get; set; } | V. のテクスチャ ラップ モードを取得または設定します。 |
| [WrapModeW](../../aspose.threed.shading/texturebase/wrapmodew/) { get; set; } | W. でテクスチャ ラップ モードを取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | プロパティを検索します。 動的プロパティ (CreateDynamicProperty/SetProperty で作成) またはネイティブ プロパティ (名前で識別) を指定できます。 |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | 指定したプロパティの値を取得 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | 動的プロパティを削除します。 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | name で識別される指定されたプロパティを削除します |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | 指定されたプロパティの値を設定します |
| [SetRotation](../../aspose.threed.shading/texturebase/setrotation/)(double, double) | UV 回転を設定します。 |
| [SetScale](../../aspose.threed.shading/texturebase/setscale/)(double, double) | UV スケールを設定します。 |
| [SetTranslation](../../aspose.threed.shading/texturebase/settranslation/)(double, double) | UV 変換を設定します。 |

### 関連項目

* class [A3DObject](../../aspose.threed/a3dobject/)
* 名前空間 [Aspose.ThreeD.Shading](../../aspose.threed.shading/)
* 組み立て [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->