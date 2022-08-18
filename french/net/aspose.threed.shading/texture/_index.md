---
title: Texture
second_title: Référence de l'API Aspose.3D pour .NET
description: Cette classe définit la texture à partir dun fichier externe.
type: docs
weight: 2350
url: /fr/net/aspose.threed.shading/texture/
---
## Texture class

Cette classe définit la texture à partir d'un fichier externe.

```csharp
public class Texture : TextureBase
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [Texture](texture#constructor)() | Initialise une nouvelle instance du[`Texture`](../texture) classe. |
| [Texture](texture#constructor_1)(string) | Initialise une nouvelle instance du[`Texture`](../texture) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [Alpha](../../aspose.threed.shading/texturebase/alpha) { get; set; } | Obtient ou définit la valeur alpha par défaut de la texture Ceci est valide lorsque le[`AlphaSource`](../texturebase/alphasource) estPixelAlpha La valeur par défaut est 1,0, la plage de valeurs valides est comprise entre 0 et 1 |
| [AlphaSource](../../aspose.threed.shading/texturebase/alphasource) { get; set; } | Obtient ou définit si la texture définit le canal alpha. La valeur par défaut estNone |
| [Content](../../aspose.threed.shading/texture/content) { get; set; } | Obtient ou définit le contenu binaire de la texture. Le contenu de la texture intégrée est facultatif, l'utilisateur doit charger la texture à partir d'un fichier externe s'il manque. |
| [EnableMipMap](../../aspose.threed.shading/texture/enablemipmap) { get; set; } | Obtient ou définit si le mipmap est activé pour cette texture |
| [FileName](../../aspose.threed.shading/texture/filename) { get; set; } | Obtient ou définit le fichier de texture associé. |
| [MagFilter](../../aspose.threed.shading/texturebase/magfilter) { get; set; } | Obtient ou définit le filtre de grossissement. |
| [MinFilter](../../aspose.threed.shading/texturebase/minfilter) { get; set; } | Obtient ou définit le filtre de minification. |
| [MipFilter](../../aspose.threed.shading/texturebase/mipfilter) { get; set; } | Obtient ou définit le filtre pour l'échantillonnage au niveau mip. |
| virtual [Name](../../aspose.threed/a3dobject/name) { get; set; } | Obtient ou définit le nom. |
| [Properties](../../aspose.threed/a3dobject/properties) { get; } | Obtient la collection de toutes les propriétés. |
| [UVRotation](../../aspose.threed.shading/texturebase/uvrotation) { get; set; } | Obtient ou définit la rotation de la texture |
| [UVScale](../../aspose.threed.shading/texturebase/uvscale) { get; set; } | Obtient ou définit l'échelle UV. |
| [UVTranslation](../../aspose.threed.shading/texturebase/uvtranslation) { get; set; } | Obtient ou définit la traduction UV. |
| [WrapModeU](../../aspose.threed.shading/texturebase/wrapmodeu) { get; set; } | Obtient ou définit les modes d'habillage de texture dans U. |
| [WrapModeV](../../aspose.threed.shading/texturebase/wrapmodev) { get; set; } | Obtient ou définit les modes d'habillage de texture dans V. |
| [WrapModeW](../../aspose.threed.shading/texturebase/wrapmodew) { get; set; } | Obtient ou définit les modes d'habillage de texture dans W. |

## Méthodes

| Nom | La description |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty)(string) | Trouve la propriété. Il peut s'agir d'une propriété dynamique (créée par CreateDynamicProperty/SetProperty) ou d'une propriété native (identifiée par son nom) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty)(string) | Obtenir la valeur de la propriété spécifiée |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(Property) | Supprime une propriété dynamique. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(string) | Supprimer la propriété spécifiée identifiée par name |
| [SetProperty](../../aspose.threed/a3dobject/setproperty)(string, object) | Définit la valeur de la propriété spécifiée |
| [SetRotation](../../aspose.threed.shading/texturebase/setrotation)(double, double) | Définit la rotation UV. |
| [SetScale](../../aspose.threed.shading/texturebase/setscale)(double, double) | Définit l'échelle UV. |
| [SetTranslation](../../aspose.threed.shading/texturebase/settranslation)(double, double) | Définit la translation UV. |

### Voir également

* class [TextureBase](../texturebase)
* espace de noms [Aspose.ThreeD.Shading](../../aspose.threed.shading)
* Assemblée [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->