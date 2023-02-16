---
title: Aspose.ThreeD.Deformers
second_title: Aspose.3D voor .NET API-referentie
description: Alle deformerklassen zijn gedefinieerd in deze naamruimte
type: docs
weight: 30
url: /nl/net/aspose.threed.deformers/
---
Alle deformer-klassen zijn gedefinieerd in deze naamruimte

## Klassen

| Klas | Beschrijving |
| --- | --- |
| [Bone](./bone/) | Een bone definieert de subset van het sturingspunt van de geometrie en het gedefinieerde menggewicht voor elk sturingspunt. De[`Bone`](../aspose.threed.deformers/bone/) object kan niet direct worden gebruikt, a[`SkinDeformer`](../aspose.threed.deformers/skindeformer/) instantie wordt gebruikt om de geometrie te vervormen, en[`SkinDeformer`](../aspose.threed.deformers/skindeformer/)wordt geleverd met een set botten, waarbij elk bot is gekoppeld aan een knooppunt. OPMERKING: Een controlepunt van een geometrie kan worden begrensd door meer dan één bot. |
| [Deformer](./deformer/) | Basisklasse voor[`SkinDeformer`](../aspose.threed.deformers/skindeformer/) En[`MorphTargetDeformer`](../aspose.threed.deformers/morphtargetdeformer/) |
| [MorphTargetChannel](./morphtargetchannel/) | Een MorphTargetChannel wordt gebruikt door[`MorphTargetDeformer`](../aspose.threed.deformers/morphtargetdeformer/) om de doelgeometrieën te organiseren. Sommige bestandsindelingen zoals FBX ondersteunen meerdere kanalen parallel. |
| [MorphTargetDeformer](./morphtargetdeformer/) | MorphTargetDeformer biedt animatie per hoekpunt. MorphTargetDeformer organiseert alle doelen via[`MorphTargetChannel`](../aspose.threed.deformers/morphtargetchannel/) , kan elk kanaal meerdere doelen organiseren. Een algemeen gebruik van morph target deformer is om gezichtsuitdrukking toe te passen op een personage. Meer details zijn te vinden op https://en.wikipedia.org/wiki/Morph_target_animation |
| [SkinDeformer](./skindeformer/) | Een huidvervormer bevat meerdere botten om te werken, elk bot mengt een deel van de geometrie door de gewichten van controlepunten. |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->