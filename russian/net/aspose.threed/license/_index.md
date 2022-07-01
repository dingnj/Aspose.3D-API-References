---
title: License
second_title: Справочник по Aspose.3D для .NET API
description: Предоставляет методы для лицензирования компонента.
type: docs
weight: 1440
url: /ru/net/aspose.threed/license/
---
## License class

Предоставляет методы для лицензирования компонента.

```csharp
public class License
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [License](license)() | Инициализирует новый экземпляр этого класса. |

## Методы

| Имя | Описание |
| --- | --- |
| [SetLicense](../../aspose.threed/license/setlicense#setlicense)(Stream) | Лицензирует компонент. |
| [SetLicense](../../aspose.threed/license/setlicense#setlicense_1)(string) | Лицензирует компонент. |

### Примеры

В этом примере будет предпринята попытка найти файл лицензии с именем MyLicense.lic в папке, содержащей  компонент, в папке, содержащей вызывающую сборку , в папке входной сборки, а затем во встроенных ресурсах вызывающей сборки.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As license = New license
License.SetLicense("MyLicense.lic")
```

jar-файл компонента:

```csharp
License license = new License();
license.setLicense("MyLicense.lic");
```

### Смотрите также

* пространство имен [Aspose.ThreeD](../../aspose.threed)
* сборка [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->