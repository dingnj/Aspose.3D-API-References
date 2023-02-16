---
title: PbrSpecularMaterial
second_title: Aspose.3D for.NETAPIリファレンス
description: 拡散色/鏡面反射光/光沢に基づく物理ベースのレンダリング用マテリアル
type: docs
weight: 2310
url: /ja/net/aspose.threed.shading/pbrspecularmaterial/
---
## PbrSpecularMaterial class

拡散色/鏡面反射光/光沢に基づく物理ベースのレンダリング用マテリアル

```csharp
public class PbrSpecularMaterial : Material
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [PbrSpecularMaterial](pbrspecularmaterial/)() | のコンストラクター`PbrSpecularMaterial` |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Diffuse](../../aspose.threed.shading/pbrspecularmaterial/diffuse/) { get; set; } | マテリアルの拡散色を取得または設定します。デフォルト値は (1, 1, 1) です。 |
| [DiffuseTexture](../../aspose.threed.shading/pbrspecularmaterial/diffusetexture/) { get; set; } | ディフューズ のテクスチャを取得または設定します |
| [EmissiveColor](../../aspose.threed.shading/pbrspecularmaterial/emissivecolor/) { get; set; } | エミッシブ カラーを取得または設定します。デフォルト値は (0, 0, 0) です。 |
| [EmissiveTexture](../../aspose.threed.shading/pbrspecularmaterial/emissivetexture/) { get; set; } | emissive のテクスチャを取得または設定します |
| [GlossinessFactor](../../aspose.threed.shading/pbrspecularmaterial/glossinessfactor/) { get; set; } | マテリアルの光沢 (滑らかさ) を取得または設定します。1 は完全に滑らかであることを意味し、0 は完全に粗いことを意味します。デフォルト値は 1、範囲は [0, 1] |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | 名前を取得または設定します。 |
| [NormalTexture](../../aspose.threed.shading/pbrspecularmaterial/normaltexture/) { get; set; } | 法線マッピングのテクスチャを取得または設定します |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | すべてのプロパティのコレクションを取得します。 |
| [Specular](../../aspose.threed.shading/pbrspecularmaterial/specular/) { get; set; } | マテリアルの反射色を取得または設定します。デフォルト値は (1, 1, 1). |
| [SpecularGlossinessTexture](../../aspose.threed.shading/pbrspecularmaterial/specularglossinesstexture/) { get; set; } | スペキュラ カラーのテクスチャを取得または設定します。チャネル RGB はスペキュラ カラーを格納し、チャネル A は光沢を格納します。 |
| [Transparency](../../aspose.threed.shading/pbrspecularmaterial/transparency/) { get; set; } | 透明度係数を取得または設定します。 係数は 0 (0%、完全に不透明) から 1 (100%、完全に透明) の範囲である必要があります。 無効な係数値はクランプされます。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | プロパティを検索します。 動的プロパティ (CreateDynamicProperty/SetProperty で作成) またはネイティブ プロパティ (名前で識別) を指定できます。 |
| [GetEnumerator](../../aspose.threed.shading/material/getenumerator/)() | 内部テクスチャ スロットを列挙する列挙子を取得します。 |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | 指定したプロパティの値を取得 |
| [GetTexture](../../aspose.threed.shading/material/gettexture/)(string) | 指定されたスロットからテクスチャを取得します。マテリアルのプロパティ名またはシェーダのパラメータ名にすることができます |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | 動的プロパティを削除します。 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | name で識別される指定されたプロパティを削除します |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | 指定されたプロパティの値を設定します |
| [SetTexture](../../aspose.threed.shading/material/settexture/)(string, TextureBase) | 指定されたスロットにテクスチャを設定します |
| override [ToString](../../aspose.threed.shading/material/tostring/)() | オブジェクトを string にフォーマットします |

## 田畑

| 名前 | 説明 |
| --- | --- |
| const [MapSpecularGlossiness](../../aspose.threed.shading/pbrspecularmaterial/mapspecularglossiness/) | 鏡面光沢のテクスチャ マップ |

### 関連項目

* class [Material](../material/)
* 名前空間 [Aspose.ThreeD.Shading](../../aspose.threed.shading/)
* 組み立て [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->