---
title: Aspose.ThreeD
second_title: Aspose.3D for.NETAPIリファレンス
description: Aspose.3D のベース ネームスペース
type: docs
weight: 10
url: /ja/net/aspose.threed/
---
Aspose.3D のベース ネームスペース

## クラス

| クラス | 説明 |
| --- | --- |
| [A3DObject](./a3dobject/) | すべての Aspose.ThreeD オブジェクトの基本クラスであり、すべてのサブ クラスが動的プロパティをサポートします。 |
| [AssetInfo](./assetinfo/) | アセットの情報。 アセット情報は、[`Scene`](../aspose.threed/scene/) . 子[`Scene`](../aspose.threed/scene/)独自のものを持つことができます[`AssetInfo`](../aspose.threed/assetinfo/)親の定義を上書きします. |
| [BonePose](./bonepose/) | [`BonePose`](../aspose.threed/bonepose/)ボーン node の変換マトリックスが含まれています |
| [CustomObject](./customobject/) | 3D ファイルで使用されるメタ データまたはカスタム オブジェクトは、このクラスによって管理されます。 すべてのカスタム プロパティは動的プロパティとして保存されます。 |
| [Entity](./entity/) | すべてのエンティティの基本クラス。 エンティティは、次のようなノードの下にアタッチされた具体的なオブジェクトを表します[`Light`](../aspose.threed.entities/light/)/[`Geometry`](../aspose.threed.entities/geometry/). |
| [ExportException](./exportexception/) | Aspose.3D がシーンを file にエクスポートできなかった場合の例外 |
| [FileFormat](./fileformat/) | ファイルフォーマット定義 |
| [FileFormatType](./fileformattype/) | ファイル形式 type |
| [GlobalTransform](./globaltransform/) | グローバル変換はに似ています[`Transform`](../aspose.threed/transform/)ただし、最終的に評価された変換を表している間は不変です。 |
| [ImageRenderOptions](./imagerenderoptions/) | オプション[`Render`](../aspose.threed/scene/render/)と[`Render`](../aspose.threed/scene/render/) |
| [ImportException](./importexception/) | Aspose.3D が指定された source を開くことができなかった場合の例外 |
| [License](./license/) | コンポーネントのライセンスを取得する方法を提供します。 |
| [Metered](./metered/) | メータリング キーを設定するメソッドを提供します。 |
| [Node](./node/) | シーン グラフの要素を表します。 シーン グラフはノード オブジェクトのツリーです。ツリー管理サービスは、このクラスに含まれています。 Aspose.3D SDK は、構築されたシーン グラフの有効性をテストしないことに注意してください。ノード階層で巡回グラフが生成されないようにするのは呼び出し元の責任です。 ツリー管理に加えて、このクラスはシーン内のオブジェクトの位置を記述するために必要なすべてのプロパティを定義します。この情報には、基本的な Translation、Rotation、および Scaling プロパティと、剛性や減衰などのピボット、制限、および IK ジョイント アトリビュートのより高度なオプションが含まれます。位置情報のみを含むグラフィック表現のないオブジェクト)。この状態では、ノード ツリー構造で親を表すために使用できますが、それ以上のことはできません。このタイプのオブジェクトの通常の使用法は、ノードを特殊化するエンティティを追加することです (「エンティティ」を参照)。 エンティティはそれ自体がオブジェクトであり、ノードに接続されています。これは、同じエンティティを複数のノード間で共有できることも意味します。カメラ、ライト、メッシュなどはすべてエンティティであり、それらはすべて基本クラス Entity. から派生しています。 |
| [NodeVisitor](./nodevisitor/) | ノード階層全体を移動するためのコールバック。 |
| [Pose](./pose/) | ポーズは、ジオメトリがスキニングされるときに変換マトリックスを格納するために使用されます。 ポーズは[`BonePose`](../aspose.threed/bonepose/)、 各[`BonePose`](../aspose.threed/bonepose/)ボーン ノードの具体的な変形情報を保存します。 |
| [Property](./property/) | ユーザー定義のプロパティを保持するクラス。 |
| [PropertyCollection](./propertycollection/) | プロパティのコレクション |
| [Scene](./scene/) | シーンは、ノード、ジオメトリ、マテリアル、テクスチャ、アニメーション、ポーズ、サブシーンなどを含む最上位のオブジェクトです。 シーンはサブシーンを持つことができ、collada/blender などのファイルで複数ドキュメントのサポートとして機能します。 /fbx ノード階層には以下からアクセスできます[`RootNode`](../aspose.threed/scene/rootnode/)[`Library`](../aspose.threed/scene/library/)ライブラリとして使用できるように、シリアル化中にアタッチされていないオブジェクト (メタデータやカスタム オブジェクトなど) の参照を保持するために使用されます。 |
| [SceneObject](./sceneobject/) | シーン内に格納されるオブジェクトのルート クラス。 |
| [Transform](./transform/) | 変換には、オブジェクトの移動/スケール/回転または変換マトリックスへのアクセスを最小コストで許可する情報が含まれています これは、ローカル変換によって使用されます. |
| [TrialException](./trialexception/) | これは、ライセンスが適用されていない場合に Scene.Open/Scene.Save で発生します。 SuppressTrialException を true に設定することで、この例外をオフにできます。 |
## インターフェース

| インターフェース | 説明 |
| --- | --- |
| [INamedObject](./inamedobject/) | という名前のオブジェクト |
## 列挙

| 列挙 | 説明 |
| --- | --- |
| [Axis](./axis/) | 座標軸。 |
| [CoordinatedSystem](./coordinatedsystem/) | 左手または右手の座標系. |
| [FileContentType](./filecontenttype/) | ファイルの内容 type |
| [PoseType](./posetype/) | ポーズタイプ. |
| [PropertyFlags](./propertyflags/) | プロパティの flags |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->