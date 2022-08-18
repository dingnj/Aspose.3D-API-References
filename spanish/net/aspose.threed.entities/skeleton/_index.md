---
title: Skeleton
second_title: Referencia de API de Aspose.3D para .NET
description: ElSkeleton./skeletones utilizado principalmente por el software CAD para ayudar al diseñador a manipular la transformación de la estructura del esqueleto generalmente es inútil fuera de los softwares CAD. Para hacer que la jerarquía del esqueleto actúe como un objeto en el software CAD es necesario marcar la parte superiorSkeleton./skeleton nodo como el raíz estableciendoType./skeleton/type aSkeleton  y todos los hijos establecidos enBone
type: docs
weight: 650
url: /es/net/aspose.threed.entities/skeleton/
---
## Skeleton class

El[`Skeleton`](../skeleton)es utilizado principalmente por el software CAD para ayudar al diseñador a manipular la transformación de la estructura del esqueleto, generalmente es inútil fuera de los softwares CAD. Para hacer que la jerarquía del esqueleto actúe como un objeto en el software CAD, es necesario marcar la parte superior[`Skeleton`](../skeleton) nodo como el raíz estableciendo[`Type`](./type) aSkeleton , y todos los hijos establecidos enBone

```csharp
public class Skeleton : Entity
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Skeleton](skeleton#constructor)() | Inicializa una nueva instancia del[`Skeleton`](../skeleton) clase. |
| [Skeleton](skeleton#constructor_1)(string) | Inicializa una nueva instancia del[`Skeleton`](../skeleton) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Excluded](../../aspose.threed/entity/excluded) { get; set; } | Obtiene o establece si se excluye esta entidad durante la exportación. |
| virtual [Name](../../aspose.threed/a3dobject/name) { get; set; } | Obtiene o establece el nombre. |
| [ParentNode](../../aspose.threed/entity/parentnode) { get; set; } | Obtiene o establece el primer nodo principal; si se establece el primer nodo principal, esta entidad se separará de otros nodos principales. |
| [ParentNodes](../../aspose.threed/entity/parentnodes) { get; } | Obtiene todos los nodos principales, una entidad se puede adjuntar a varios nodos principales para crear instancias de geometría |
| [Properties](../../aspose.threed/a3dobject/properties) { get; } | Obtiene la colección de todas las propiedades. |
| [Scene](../../aspose.threed/sceneobject/scene) { get; } | Obtiene la escena a la que pertenece este objeto |
| [Size](../../aspose.threed.entities/skeleton/size) { get; set; } | Obtiene o establece el tamaño del nodo de la extremidad que se usa en el software CAD para representar el tamaño del hueso. |
| [Type](../../aspose.threed.entities/skeleton/type) { get; set; } | Obtiene o establece el tipo del esqueleto. |

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

### Ver también

* class [Entity](../../aspose.threed/entity)
* espacio de nombres [Aspose.ThreeD.Entities](../../aspose.threed.entities)
* asamblea [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->