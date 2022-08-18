---
title: PolygonBuilder
second_title: Référence de l'API Aspose.3D pour .NET
description: Une classe dassistance pour construire un polygone pourMesh./mesh
type: docs
weight: 550
url: /fr/net/aspose.threed.entities/polygonbuilder/
---
## PolygonBuilder class

Une classe d'assistance pour construire un polygone pour[`Mesh`](../mesh)

```csharp
public sealed class PolygonBuilder
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [PolygonBuilder](polygonbuilder)(Mesh) | Initialise une nouvelle instance du[`PolygonBuilder`](../polygonbuilder) classe. |

## Méthodes

| Nom | La description |
| --- | --- |
| [AddVertex](../../aspose.threed.entities/polygonbuilder/addvertex)(int) | Ajoute un index de sommet au polygone |
| [Begin](../../aspose.threed.entities/polygonbuilder/begin)() | Commence à ajouter un nouveau polygone |
| [End](../../aspose.threed.entities/polygonbuilder/end)() | Termine la création du polygone |

### Exemples

Égal à : Si tous les index sont prêts à être utilisés,[`CreatePolygon`](../mesh/createpolygon) est préférable, sinon[`PolygonBuilder`](../polygonbuilder) serait un meilleur choix.

```csharp
PolygonBuilder builder = new PolygonBuilder(mesh);
builder.Begin();
builder.AddVertex(0);
builder.AddVertex(1);
builder.AddVertex(2);
Builder.End();
```

```csharp
int[] indices = new int[] {0, 1, 2};
mesh.CreatePolygon(indices);
```

### Voir également

* espace de noms [Aspose.ThreeD.Entities](../../aspose.threed.entities)
* Assemblée [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->