---
title: Add
second_title: Справочник по Aspose.3D для .NET API
description: Добавить задачу рендеринга в очередь рендеринга.
type: docs
weight: 10
url: /ru/net/aspose.threed.render/irenderqueue/add/
---
## IRenderQueue.Add method

Добавить задачу рендеринга в очередь рендеринга.

```csharp
public void Add(RenderQueueGroupId groupId, IPipeline pipeline, object renderableResource, 
    int subEntity)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| groupId | RenderQueueGroupId | В какой группе очереди будет задача рендеринга |
| pipeline | IPipeline | Экземпляр конвейера, используемый для этой задачи рендеринга |
| renderableResource | Object | Пользовательский объект, который будет отправлен[`RenderEntity`](../../entityrenderer/renderentity) |
| subEntity | Int32 | Индекс подсущностей, полезен, когда сущность состоит из более чем одного вспомогательного визуализируемого компонента. |

### Смотрите также

* enum [RenderQueueGroupId](../../renderqueuegroupid)
* interface [IPipeline](../../ipipeline)
* interface [IRenderQueue](../../irenderqueue)
* пространство имен [Aspose.ThreeD.Render](../../irenderqueue)
* сборка [Aspose.3D](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->