---
title: RevolvedAreaSolid
second_title: Справочник по Aspose.3D для .NET API
description: Этот класс представляет твердотельную модель путем вращения поперечного сечения профиля вокруг оси.
type: docs
weight: 620
url: /ru/net/aspose.threed.entities/revolvedareasolid/
---
## RevolvedAreaSolid class

Этот класс представляет твердотельную модель путем вращения поперечного сечения профиля вокруг оси.

```csharp
public class RevolvedAreaSolid : Entity, IMeshConvertible
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [RevolvedAreaSolid](revolvedareasolid)() | Конструктор по умолчанию. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [AngleEnd](../../aspose.threed.entities/revolvedareasolid/angleend) { get; set; } | Получает или задает конечный угол процедуры вращения, измеренный в радианах, значение по умолчанию — пи. |
| [AngleStart](../../aspose.threed.entities/revolvedareasolid/anglestart) { get; set; } | Получает или задает начальный угол процедуры вращения, измеренный в радианах, значение по умолчанию равно 0. |
| [Axis](../../aspose.threed.entities/revolvedareasolid/axis) { get; set; } | Получает или задает направление оси, значение по умолчанию (0, 1, 0). |
| [Excluded](../../aspose.threed/entity/excluded) { get; set; } | Получает или задает, следует ли исключить этот объект при экспорте. |
| virtual [Name](../../aspose.threed/a3dobject/name) { get; set; } | Получает или задает имя. |
| [Origin](../../aspose.threed.entities/revolvedareasolid/origin) { get; set; } | Получает или задает исходную точку вращения, значение по умолчанию (0, 0, 0). |
| [ParentNode](../../aspose.threed/entity/parentnode) { get; set; } | Получает или устанавливает первый родительский узел, если установлен первый родительский узел, этот объект будет отсоединен от других родительских узлов. |
| [ParentNodes](../../aspose.threed/entity/parentnodes) { get; } | Получает все родительские узлы, сущность может быть присоединена к нескольким родительским узлам для создания экземпляров геометрии |
| [Properties](../../aspose.threed/a3dobject/properties) { get; } | Получает коллекцию всех свойств. |
| [Scene](../../aspose.threed/sceneobject/scene) { get; } | Получает сцену, которой принадлежит этот объект |
| [Shape](../../aspose.threed.entities/revolvedareasolid/shape) { get; set; } | Получает или задает базовый профиль, используемый для вращения. |

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
| [ToMesh](../../aspose.threed.entities/revolvedareasolid/tomesh)() | Преобразуйте[`RevolvedAreaSolid`](../revolvedareasolid)в сетку. |

### Смотрите также

* class [Entity](../../aspose.threed/entity)
* interface [IMeshConvertible](../imeshconvertible)
* пространство имен [Aspose.ThreeD.Entities](../../aspose.threed.entities)
* сборка [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->