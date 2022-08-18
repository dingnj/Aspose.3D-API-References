---
title: Interpolation
second_title: Référence de l'API Aspose.3D pour .NET
description: Le type dinterpolation de limage clé.
type: docs
weight: 80
url: /fr/net/aspose.threed.animation/interpolation/
---
## Interpolation enumeration

Le type d'interpolation de l'image clé.

```csharp
public enum Interpolation
```

### Valeurs

| Nom | Évaluer | La description |
| --- | --- | --- |
| Constant | `0` | La valeur restera constante à la valeur du premier point jusqu'au segment suivant. |
| Linear | `1` | L'interpolation linéaire est une ligne droite entre deux points. |
| Bezier | `2` | Une spline de Bézier ou Hermite. |
| BSpline | `3` | Les splines de base sont définies par une série de points de contrôle, pour lesquels la courbe est garantie de ne passer que par le premier et le dernier point. |
| CardinalSpline | `4` | Une spline cardinale est une spline Hermite cubique dont les tangentes sont définies par les extrémités et un paramètre de tension. |
| TCBSpline | `5` | Aussi appelée spline de Kochanek-Bartels, le comportement de la tangente est défini par tension/biais/continuité |

### Voir également

* espace de noms [Aspose.ThreeD.Animation](../../aspose.threed.animation)
* Assemblée [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->