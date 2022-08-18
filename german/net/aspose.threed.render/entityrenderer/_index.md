---
title: EntityRenderer
second_title: Aspose.3D für .NET-API-Referenz
description: Unterklassifizieren Sie dies um das Rendering für verschiedene Arten von Entitäten zu implementieren.
type: docs
weight: 1780
url: /de/net/aspose.threed.render/entityrenderer/
---
## EntityRenderer class

Unterklassifizieren Sie dies, um das Rendering für verschiedene Arten von Entitäten zu implementieren.

```csharp
public class EntityRenderer
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [EntityRenderer](entityrenderer#constructor)(string) | Konstrukteur von[`EntityRenderer`](../entityrenderer) |
| [EntityRenderer](entityrenderer#constructor_1)(string, EntityRendererFeatures) | Konstrukteur von[`EntityRenderer`](../entityrenderer) |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [Dispose](../../aspose.threed.render/entityrenderer/dispose)() | Der Entity-Renderer wird verworfen, freigegebene Ressourcen freigeben. |
| virtual [FrameBegin](../../aspose.threed.render/entityrenderer/framebegin)(Renderer, IRenderQueue) | Mit dem Rendern eines Frames beginnen |
| virtual [FrameEnd](../../aspose.threed.render/entityrenderer/frameend)(Renderer, IRenderQueue) | Beendet das Rendern eines Frames |
| virtual [Initialize](../../aspose.threed.render/entityrenderer/initialize)(Renderer) | Initialisieren Sie die Entität renderer |
| virtual [PrepareRenderQueue](../../aspose.threed.render/entityrenderer/preparerenderqueue)(Renderer, IRenderQueue, Node, Entity) | Bereiten Sie Rendering-Befehle für das angegebene Knoten-/Entitätspaar vor. |
| virtual [RenderEntity](../../aspose.threed.render/entityrenderer/renderentity)(Renderer, ICommandList, Node, object, int) | Jeder Render-Task wurde an die geschoben[`IRenderQueue`](../irenderqueue) wird einen entsprechenden RenderEntity-Aufruf haben, um den konkreten Rendering-Job auszuführen. |
| virtual [ResetSceneCache](../../aspose.threed.render/entityrenderer/resetscenecache)() | Die Szene wurde geändert oder entfernt, Sie müssen Renderressourcen auf Szenenebene in this freigeben |

### Siehe auch

* namensraum [Aspose.ThreeD.Render](../../aspose.threed.render)
* Montage [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->