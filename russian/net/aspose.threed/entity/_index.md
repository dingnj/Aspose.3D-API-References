---
title: Entity
second_title: Справочник по Aspose.3D для .NET API
description: Базовый класс всех сущностей. Entity представляет собой конкретный объект прикрепленный под узлом напримерLight../aspose.threed.entities/light/Geometry../aspose.threed.entities/geometry.
type: docs
weight: 970
url: /ru/net/aspose.threed/entity/
---
## Entity class

Базовый класс всех сущностей. Entity представляет собой конкретный объект, прикрепленный под узлом, например[`Light`](../../aspose.threed.entities/light)/[`Geometry`](../../aspose.threed.entities/geometry).

```csharp
public abstract class Entity : SceneObject
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Entity](entity)(string) | Инициализирует новый экземпляр класса[`Entity`](../entity). |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Excluded](../../aspose.threed/entity/excluded) { get; set; } | Получает или задает, следует ли исключить этот объект при экспорте. |
| virtual [Name](../../aspose.threed/a3dobject/name) { get; set; } | Получает или задает имя. |
| [ParentNode](../../aspose.threed/entity/parentnode) { get; set; } | Получает или устанавливает первый родительский узел, если установлен первый родительский узел, этот объект будет отсоединен от других родительских узлов. |
| [ParentNodes](../../aspose.threed/entity/parentnodes) { get; } | Получает все родительские узлы, сущность может быть присоединена к нескольким родительским узлам для создания экземпляров геометрии |
| [Properties](../../aspose.threed/a3dobject/properties) { get; } | Получает коллекцию всех свойств. |
| [Scene](../../aspose.threed/sceneobject/scene) { get; } | Получает сцену, которой принадлежит этот объект |

## Методы

| Имя | Описание |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty)(string) | Находит свойство. Это может быть динамическое свойство (созданное CreateDynamicProperty/SetProperty) или родное свойство (идентифицированное по имени) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox)() | Получает ограничивающую рамку текущего объекта в его системе координат объектного пространства. |
| virtual [GetEntityRendererKey](../../aspose.threed/entity/getentityrendererkey)() | Получает ключ рендерера сущности, зарегистрированного в рендерере |
| [GetProperty](../../aspose.threed/a3dobject/getproperty)(string) | Получить значение указанного свойства |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(Property) | Удаляет динамическое свойство. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(string) | Удалить указанное свойство, идентифицированное по имени |
| [SetProperty](../../aspose.threed/a3dobject/setproperty)(string, object) | Устанавливает значение указанного свойства |

### Смотрите также

* class [SceneObject](../sceneobject)
* пространство имен [Aspose.ThreeD](../../aspose.threed)
* сборка [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->