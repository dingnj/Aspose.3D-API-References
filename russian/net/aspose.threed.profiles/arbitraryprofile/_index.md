---
title: ArbitraryProfile
second_title: Справочник по Aspose.3D для .NET API
description: Этот класс позволяет построить 2D-профиль непосредственно из произвольной кривой.
type: docs
weight: 1500
url: /ru/net/aspose.threed.profiles/arbitraryprofile/
---
## ArbitraryProfile class

Этот класс позволяет построить 2D-профиль непосредственно из произвольной кривой.

```csharp
public class ArbitraryProfile : Profile
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ArbitraryProfile](arbitraryprofile#constructor)() | Конструктор[`ArbitraryProfile`](../arbitraryprofile) |
| [ArbitraryProfile](arbitraryprofile#constructor_1)(Curve) | Конструктор[`ArbitraryProfile`](../arbitraryprofile)с начальной кривой. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Curve](../../aspose.threed.profiles/arbitraryprofile/curve) { get; set; } | Кривая, используемая для построения профиля |
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
| override [GetEntityRendererKey](../../aspose.threed.profiles/profile/getentityrendererkey)() | Получает ключ рендерера сущности, зарегистрированного в рендерере |
| [GetProperty](../../aspose.threed/a3dobject/getproperty)(string) | Получить значение указанного свойства |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(Property) | Удаляет динамическое свойство. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(string) | Удалить указанное свойство, идентифицированное по имени |
| [SetProperty](../../aspose.threed/a3dobject/setproperty)(string, object) | Устанавливает значение указанного свойства |

### Смотрите также

* class [Profile](../profile)
* пространство имен [Aspose.ThreeD.Profiles](../../aspose.threed.profiles)
* сборка [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->