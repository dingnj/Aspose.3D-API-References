---
title: MorphTargetDeformer
second_title: Referencia de API de Aspose.3D para .NET
description: MorphTargetDeformer proporciona animación por vértice. MorphTargetDeformer organiza todos los objetivos medianteMorphTargetChannel./morphtargetchannel  cada canal puede organizar múltiples objetivos. Un uso común del deformador de objetivo de morph es aplicar expresión facial a un personaje. Se pueden encontrar más detalles en https//en.wikipedia.org/wiki/Morph_target_animation
type: docs
weight: 210
url: /es/net/aspose.threed.deformers/morphtargetdeformer/
---
## MorphTargetDeformer class

MorphTargetDeformer proporciona animación por vértice. MorphTargetDeformer organiza todos los objetivos mediante[`MorphTargetChannel`](../morphtargetchannel) , cada canal puede organizar múltiples objetivos. Un uso común del deformador de objetivo de morph es aplicar expresión facial a un personaje. Se pueden encontrar más detalles en https://en.wikipedia.org/wiki/Morph_target_animation

```csharp
public class MorphTargetDeformer : Deformer
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [MorphTargetDeformer](morphtargetdeformer#constructor)() | Inicializa una nueva instancia del[`MorphTargetDeformer`](../morphtargetdeformer) clase. |
| [MorphTargetDeformer](morphtargetdeformer#constructor_1)(string) | Inicializa una nueva instancia del[`MorphTargetDeformer`](../morphtargetdeformer) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Channels](../../aspose.threed.deformers/morphtargetdeformer/channels) { get; } | Obtiene todos los canales contenidos en este deformador |
| [Item](../../aspose.threed.deformers/morphtargetdeformer/item) { get; set; } |  |
| virtual [Name](../../aspose.threed/a3dobject/name) { get; set; } | Obtiene o establece el nombre. |
| [Owner](../../aspose.threed.deformers/deformer/owner) { get; } | Obtiene la geometría propietaria de este deformador |
| [Properties](../../aspose.threed/a3dobject/properties) { get; } | Obtiene la colección de todas las propiedades. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty)(string) | Encuentra la propiedad. Puede ser una propiedad dinámica (Creada por CreateDynamicProperty/SetProperty) o una propiedad nativa (Identificada por su nombre) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty)(string) | Obtener el valor de la propiedad especificada |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(Property) | Elimina una propiedad dinámica. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(string) | Eliminar la propiedad especificada identificada por nombre |
| [SetProperty](../../aspose.threed/a3dobject/setproperty)(string, object) | Establece el valor de la propiedad especificada |

### Ver también

* class [Deformer](../deformer)
* espacio de nombres [Aspose.ThreeD.Deformers](../../aspose.threed.deformers)
* asamblea [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->