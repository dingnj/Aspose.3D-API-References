---
title: PhongMaterial
second_title: Referencia de API de Aspose.3D para .NET
description: Material para modelo de sombreado blinn-phong.
type: docs
weight: 2320
url: /es/net/aspose.threed.shading/phongmaterial/
---
## PhongMaterial class

Material para modelo de sombreado blinn-phong.

```csharp
public class PhongMaterial : LambertMaterial
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PhongMaterial](phongmaterial#constructor)() | Inicializa una nueva instancia del[`PhongMaterial`](../phongmaterial) clase. |
| [PhongMaterial](phongmaterial#constructor_1)(string) | Inicializa una nueva instancia del[`PhongMaterial`](../phongmaterial) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AmbientColor](../../aspose.threed.shading/lambertmaterial/ambientcolor) { get; set; } | Obtiene o establece el color ambiental |
| [DiffuseColor](../../aspose.threed.shading/lambertmaterial/diffusecolor) { get; set; } | Obtiene o establece el color difuso |
| [EmissiveColor](../../aspose.threed.shading/lambertmaterial/emissivecolor) { get; set; } | Obtiene o establece el color emisivo |
| virtual [Name](../../aspose.threed/a3dobject/name) { get; set; } | Obtiene o establece el nombre. |
| [Properties](../../aspose.threed/a3dobject/properties) { get; } | Obtiene la colección de todas las propiedades. |
| [ReflectionColor](../../aspose.threed.shading/phongmaterial/reflectioncolor) { get; set; } | Obtiene o establece el color del reflejo. |
| [ReflectionFactor](../../aspose.threed.shading/phongmaterial/reflectionfactor) { get; set; } | Obtiene o establece la atenuación del color de reflexión. |
| [Shininess](../../aspose.threed.shading/phongmaterial/shininess) { get; set; } | Obtiene o establece el brillo, esto controla el tamaño del resaltado especular. La fórmula de especular: SpecularColor * SpecularFactor * (N punto H) ^ Shininess |
| [SpecularColor](../../aspose.threed.shading/phongmaterial/specularcolor) { get; set; } | Obtiene o establece el color especular. |
| [SpecularFactor](../../aspose.threed.shading/phongmaterial/specularfactor) { get; set; } | Obtiene o establece el factor especular. La fórmula de especular: SpecularColor * SpecularFactor * (N punto H) ^ Shininess |
| [Transparency](../../aspose.threed.shading/lambertmaterial/transparency) { get; set; } | Obtiene o establece el factor de transparencia. El factor debe oscilar entre 0 (0 %, completamente opaco) y 1 (100 %, completamente transparente) Se restringirá cualquier valor de factor no válido. |
| [TransparentColor](../../aspose.threed.shading/lambertmaterial/transparentcolor) { get; set; } | Obtiene o establece el color transparente. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty)(string) | Encuentra la propiedad. Puede ser una propiedad dinámica (Creada por CreateDynamicProperty/SetProperty) o una propiedad nativa (Identificada por su nombre) |
| [GetEnumerator](../../aspose.threed.shading/material/getenumerator)() | Obtiene el enumerador para enumerar ranuras de texturas internas. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty)(string) | Obtener el valor de la propiedad especificada |
| [GetTexture](../../aspose.threed.shading/material/gettexture)(string) | Obtiene la textura de la ranura especificada, puede ser el nombre de la propiedad del material o el nombre del parámetro del shader |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(Property) | Elimina una propiedad dinámica. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(string) | Eliminar la propiedad especificada identificada por nombre |
| [SetProperty](../../aspose.threed/a3dobject/setproperty)(string, object) | Establece el valor de la propiedad especificada |
| [SetTexture](../../aspose.threed.shading/material/settexture)(string, TextureBase) | Establece la textura en la ranura especificada |
| override [ToString](../../aspose.threed.shading/material/tostring)() | Da formato al objeto a string |

### Ver también

* class [LambertMaterial](../lambertmaterial)
* espacio de nombres [Aspose.ThreeD.Shading](../../aspose.threed.shading)
* asamblea [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->