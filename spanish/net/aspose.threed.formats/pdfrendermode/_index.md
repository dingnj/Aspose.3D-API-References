---
title: PdfRenderMode
second_title: Referencia de API de Aspose.3D para .NET
description: El modo de renderizado especifica el estilo en el que se renderiza la ilustración 3D.
type: docs
weight: 1260
url: /es/net/aspose.threed.formats/pdfrendermode/
---
## PdfRenderMode enumeration

El modo de renderizado especifica el estilo en el que se renderiza la ilustración 3D.

```csharp
public enum PdfRenderMode
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Solid | `0` | Muestra formas geométricas texturizadas e iluminadas. |
| SolidWireframe | `1` | Muestra formas geométricas texturizadas e iluminadas (triángulos) con bordes de un solo color encima. |
| Transparent | `2` | Muestra formas geométricas texturizadas e iluminadas (triángulos) con un nivel adicional de transparencia. |
| TransparentWireframe | `3` | Muestra formas geométricas texturizadas e iluminadas (triángulos) con un nivel adicional de transparencia, con bordes opacos de un solo color encima. |
| BoundingBox | `4` | Muestra los bordes del cuadro delimitador de cada nodo, alineados con los ejes del espacio de coordenadas local para ese nodo. |
| TransparentBoundingBox | `5` | Muestra las caras de los cuadros delimitadores de cada nodo, alineados con los ejes del espacio de coordenadas local para ese nodo, con un nivel adicional de transparencia. |
| TransparentBoundingBoxOutline | `6` | Muestra los bordes y las caras de los cuadros delimitadores de cada nodo, alineados con los ejes del espacio de coordenadas local para ese nodo, con un nivel adicional de transparencia. |
| Wireframe | `7` | Muestra solo los bordes en un solo color. |
| ShadedWireframe | `8` | Muestra solo los bordes, aunque interpola su color entre sus dos vértices y aplica iluminación. |
| HiddenWireframe | `9` | Muestra los bordes en un solo color, aunque elimina los bordes reversos y oscurecidos. |
| Vertices | `10` | Muestra solo los vértices en un solo color. |
| ShadedVertices | `11` | Muestra solo los vértices, aunque usa su color de vértice y aplica iluminación. |
| Illustration | `12` | Muestra bordes de silueta con superficies, elimina líneas ocultas. |
| SolidOutline | `13` | Muestra los bordes de la silueta con superficies iluminadas y texturizadas, elimina las líneas oscurecidas. |
| ShadedIllustration | `14` | Muestra los bordes de la silueta con superficies iluminadas y texturizadas y un término emisivo adicional para eliminar las áreas mal iluminadas de la ilustración. |

### Ver también

* espacio de nombres [Aspose.ThreeD.Formats](../../aspose.threed.formats)
* asamblea [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->