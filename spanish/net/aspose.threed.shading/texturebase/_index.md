---
title: TextureBase
second_title: Referencia de API de Aspose.3D para .NET
description: Clase base para todas las texturas de hormigón. La textura define la apariencia de una superficie geométrica.
type: docs
weight: 2360
url: /es/net/aspose.threed.shading/texturebase/
---
## TextureBase class

Clase base para todas las texturas de hormigón. La textura define la apariencia de una superficie geométrica.

```csharp
public class TextureBase : A3DObject
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [TextureBase](texturebase)(string) | Inicializa una nueva instancia del[`TextureBase`](../texturebase) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Alpha](../../aspose.threed.shading/texturebase/alpha) { get; set; } | Obtiene o establece el valor alfa predeterminado de la textura Esto es válido cuando el[`AlphaSource`](./alphasource) esPixelAlpha El valor predeterminado es 1.0, el rango de valores válido es entre 0 y 1 |
| [AlphaSource](../../aspose.threed.shading/texturebase/alphasource) { get; set; } | Obtiene o establece si la textura define el canal alfa. El valor predeterminado esNone |
| [MagFilter](../../aspose.threed.shading/texturebase/magfilter) { get; set; } | Obtiene o establece el filtro de ampliación. |
| [MinFilter](../../aspose.threed.shading/texturebase/minfilter) { get; set; } | Obtiene o establece el filtro para minificación. |
| [MipFilter](../../aspose.threed.shading/texturebase/mipfilter) { get; set; } | Obtiene o establece el filtro para el muestreo de nivel mip. |
| virtual [Name](../../aspose.threed/a3dobject/name) { get; set; } | Obtiene o establece el nombre. |
| [Properties](../../aspose.threed/a3dobject/properties) { get; } | Obtiene la colección de todas las propiedades. |
| [UVRotation](../../aspose.threed.shading/texturebase/uvrotation) { get; set; } | Obtiene o establece la rotación de la textura |
| [UVScale](../../aspose.threed.shading/texturebase/uvscale) { get; set; } | Obtiene o establece la escala UV. |
| [UVTranslation](../../aspose.threed.shading/texturebase/uvtranslation) { get; set; } | Obtiene o establece la traducción UV. |
| [WrapModeU](../../aspose.threed.shading/texturebase/wrapmodeu) { get; set; } | Obtiene o establece los modos de ajuste de textura en U. |
| [WrapModeV](../../aspose.threed.shading/texturebase/wrapmodev) { get; set; } | Obtiene o establece los modos de ajuste de textura en V. |
| [WrapModeW](../../aspose.threed.shading/texturebase/wrapmodew) { get; set; } | Obtiene o establece los modos de ajuste de textura en W. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty)(string) | Encuentra la propiedad. Puede ser una propiedad dinámica (Creada por CreateDynamicProperty/SetProperty) o una propiedad nativa (Identificada por su nombre) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty)(string) | Obtener el valor de la propiedad especificada |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(Property) | Elimina una propiedad dinámica. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(string) | Eliminar la propiedad especificada identificada por nombre |
| [SetProperty](../../aspose.threed/a3dobject/setproperty)(string, object) | Establece el valor de la propiedad especificada |
| [SetRotation](../../aspose.threed.shading/texturebase/setrotation)(double, double) | Establece la rotación UV. |
| [SetScale](../../aspose.threed.shading/texturebase/setscale)(double, double) | Establece la escala UV. |
| [SetTranslation](../../aspose.threed.shading/texturebase/settranslation)(double, double) | Establece la traducción UV. |

### Ver también

* class [A3DObject](../../aspose.threed/a3dobject)
* espacio de nombres [Aspose.ThreeD.Shading](../../aspose.threed.shading)
* asamblea [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->