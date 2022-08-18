---
title: Pyramid
second_title: Referencia de API de Aspose.3D para .NET
description: Pirámide parametrizada.
type: docs
weight: 590
url: /es/net/aspose.threed.entities/pyramid/
---
## Pyramid class

Pirámide parametrizada.

```csharp
public class Pyramid : Primitive
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Pyramid](pyramid#constructor)() | Construya una nueva instancia de pirámide con el área inferior predeterminada (10, 10) y la altura predeterminada (5) |
| [Pyramid](pyramid#constructor_1)(double, double, double) | Construya una nueva instancia de pirámide con el área inferior especificada |
| [Pyramid](pyramid#constructor_2)(double, double, double, double, double) | Construya una nueva instancia de pirámide con el área inferior y superior y la altura especificadas. |
| [Pyramid](pyramid#constructor_3)(string, double, double, double, double, double) | Construya una nueva instancia de pirámide con el área inferior y superior y la altura especificadas. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BottomArea](../../aspose.threed.entities/pyramid/bottomarea) { get; set; } | Área de la tapa inferior |
| [BottomOffset](../../aspose.threed.entities/pyramid/bottomoffset) { get; set; } | Desplazamiento para vértices inferiores |
| [CastShadows](../../aspose.threed.entities/primitive/castshadows) { get; set; } | Obtiene o establece si esta geometría puede proyectar shadow |
| [Excluded](../../aspose.threed/entity/excluded) { get; set; } | Obtiene o establece si se excluye esta entidad durante la exportación. |
| [Height](../../aspose.threed.entities/pyramid/height) { get; set; } | Altura de la pirámide |
| virtual [Name](../../aspose.threed/a3dobject/name) { get; set; } | Obtiene o establece el nombre. |
| [ParentNode](../../aspose.threed/entity/parentnode) { get; set; } | Obtiene o establece el primer nodo principal; si se establece el primer nodo principal, esta entidad se separará de otros nodos principales. |
| [ParentNodes](../../aspose.threed/entity/parentnodes) { get; } | Obtiene todos los nodos principales, una entidad se puede adjuntar a varios nodos principales para crear instancias de geometría |
| [Properties](../../aspose.threed/a3dobject/properties) { get; } | Obtiene la colección de todas las propiedades. |
| [ReceiveShadows](../../aspose.threed.entities/primitive/receiveshadows) { get; set; } | Obtiene o establece si esta geometría puede recibir shadow. |
| [Scene](../../aspose.threed/sceneobject/scene) { get; } | Obtiene la escena a la que pertenece este objeto |
| [TopArea](../../aspose.threed.entities/pyramid/toparea) { get; set; } | Área de la tapa superior |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty)(string) | Encuentra la propiedad. Puede ser una propiedad dinámica (Creada por CreateDynamicProperty/SetProperty) o una propiedad nativa (Identificada por su nombre) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox)() | Obtiene el cuadro delimitador de la entidad actual en su sistema de coordenadas de espacio de objetos. |
| virtual [GetEntityRendererKey](../../aspose.threed/entity/getentityrendererkey)() | Obtiene la clave del renderizador de entidades registrado en el renderizador |
| [GetProperty](../../aspose.threed/a3dobject/getproperty)(string) | Obtener el valor de la propiedad especificada |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(Property) | Elimina una propiedad dinámica. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(string) | Eliminar la propiedad especificada identificada por nombre |
| [SetProperty](../../aspose.threed/a3dobject/setproperty)(string, object) | Establece el valor de la propiedad especificada |
| override [ToMesh](../../aspose.threed.entities/pyramid/tomesh)() | Convertir objeto actual a mesh |

### Ver también

* class [Primitive](../primitive)
* espacio de nombres [Aspose.ThreeD.Entities](../../aspose.threed.entities)
* asamblea [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->