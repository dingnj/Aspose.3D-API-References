---
title: Discreet3dsSaveOptions
second_title: Referencia de API de Aspose.3D para .NET
description: Opciones de guardado para archivo 3DS.
type: docs
weight: 1070
url: /es/net/aspose.threed.formats/discreet3dssaveoptions/
---
## Discreet3dsSaveOptions class

Opciones de guardado para archivo 3DS.

```csharp
public class Discreet3dsSaveOptions : SaveOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Discreet3dsSaveOptions](discreet3dssaveoptions)() | Constructor de[`Discreet3dsSaveOptions`](../discreet3dssaveoptions) |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [DuplicatedNameCounterBase](../../aspose.threed.formats/discreet3dssaveoptions/duplicatednamecounterbase) { get; set; } | El contador utilizado al generar un nuevo nombre para nombres duplicados, el valor predeterminado es 2. |
| [DuplicatedNameCounterFormat](../../aspose.threed.formats/discreet3dssaveoptions/duplicatednamecounterformat) { get; set; } | El formato del contador duplicado, el valor predeterminado es una cadena vacía. |
| [DuplicatedNameSeparator](../../aspose.threed.formats/discreet3dssaveoptions/duplicatednameseparator) { get; set; } | El separador entre el nombre del objeto y el contador duplicado, el valor predeterminado es "_". Cuando la escena contiene objetos que usan el mismo nombre, el exportador 3DS de Aspose.3D generará un nombre diferente para el objeto. Por ejemplo, hay dos nodos llamado "Box", el primer nodo tendrá un nombre "Box", y el segundo nodo obtendrá un nuevo nombre "Box_2" utilizando la configuración predeterminada. |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding) { get; set; } | Obtiene o establece la codificación predeterminada para archivos basados en texto. El valor predeterminado es nulo, lo que significa que el importador/exportador decidirá qué codificación usar. |
| [ExportCamera](../../aspose.threed.formats/discreet3dssaveoptions/exportcamera) { get; set; } | Obtiene o establece si exportar todas las cámaras de la escena. |
| [ExportLight](../../aspose.threed.formats/discreet3dssaveoptions/exportlight) { get; set; } | Obtiene o establece si exportar todas las luces de la escena. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat) { get; } | Obtiene el formato de archivo especificado en la opción Guardar/Cargar actual. |
| [FileName](../../aspose.threed.formats/ioconfig/filename) { get; set; } | El nombre de archivo de la escena de exportación/importación. Esto es opcional, pero útil cuando se serializan activos externos como el material de OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem) { get; set; } | Permitir que el usuario maneje cómo administrar las dependencias externas durante cargar/guardar. |
| [FlipCoordinateSystem](../../aspose.threed.formats/discreet3dssaveoptions/flipcoordinatesystem) { get; set; } | Obtiene o establece el sistema de coordenadas de volteo de puntos de control/normales durante la importación/exportación. |
| [GammaCorrectedColor](../../aspose.threed.formats/discreet3dssaveoptions/gammacorrectedcolor) { get; set; } | Un archivo 3ds puede contener el color original y el color con corrección de gamma para el mismo atributo, Si se establece en verdadero, se usará el color con corrección de gamma si es posible, de lo contrario, Aspose.3D intentará usar el color original. |
| [HighPreciseColor](../../aspose.threed.formats/discreet3dssaveoptions/highprecisecolor) { get; set; } | Si esto es cierto, el archivo 3ds generado usará un color de alta precisión, lo que significa que cada canal rojo/verde/azul está en 32 bits flotantes. De lo contrario, el archivo generado usará un color de 24 bits, cada canal usará un byte de 8 bits. El valor predeterminado es falso, porque no todas las aplicaciones admiten el color de alta precisión. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths) { get; set; } | Algunos archivos como OBJ dependen de un archivo externo, las rutas de búsqueda permitirán que Aspose.3D busque un archivo externo para cargar. |
| [MasterScale](../../aspose.threed.formats/discreet3dssaveoptions/masterscale) { get; set; } | Obtiene o establece la escala maestra utilizada en la exportación. |

### Ver también

* class [SaveOptions](../saveoptions)
* espacio de nombres [Aspose.ThreeD.Formats](../../aspose.threed.formats)
* asamblea [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->