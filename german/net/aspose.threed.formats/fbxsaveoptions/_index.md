---
title: FbxSaveOptions
second_title: Aspose.3D für .NET-API-Referenz
description: Speicheroptionen für Fbx-Datei.
type: docs
weight: 1120
url: /de/net/aspose.threed.formats/fbxsaveoptions/
---
## FbxSaveOptions class

Speicheroptionen für Fbx-Datei.

```csharp
public class FbxSaveOptions : SaveOptions
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [FbxSaveOptions](fbxsaveoptions#constructor)(FileContentType) | Initialisieren a[`FbxSaveOptions`](../fbxsaveoptions) mit der neuesten unterstützten Version. |
| [FbxSaveOptions](fbxsaveoptions#constructor_1)(FileFormat) | Initialisiert a[`FbxSaveOptions`](../fbxsaveoptions) |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [EmbedTextures](../../aspose.threed.formats/fbxsaveoptions/embedtextures) { get; set; } | Ruft ab oder legt fest, ob die Textur in die endgültige Ausgabedatei eingebettet werden soll. FBX Exporter versucht, die Rohdaten der Textur zu finden[`FileSystem`](../ioconfig/filesystem) , und betten Sie die Datei in die endgültige FBX-Datei ein. Der Standardwert ist false. |
| [EnableCompression](../../aspose.threed.formats/fbxsaveoptions/enablecompression) { get; set; } | Komprimierung großer Binärdaten in der FBX-Datei (z. B. Animationsdaten, Kontrollpunkte, Vertexelementdaten, Indizes), Standardwert ist wahr. |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding) { get; set; } | Ruft die Standardcodierung für textbasierte Dateien ab oder legt sie fest. Der Standardwert ist null, was bedeutet, dass der Importer/Exporter entscheidet, welche Codierung verwendet wird. |
| [ExportLegacyMaterialProperties](../../aspose.threed.formats/fbxsaveoptions/exportlegacymaterialproperties) { get; set; } | Ruft ab oder legt fest, ob ältere Materialeigenschaften exportiert werden, die für die Abwärtskompatibilität verwendet werden. Diese Option ist standardmäßig aktiviert. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat) { get; } | Ruft das Dateiformat ab, das in der aktuellen Option Speichern/Laden angegeben ist. |
| [FileName](../../aspose.threed.formats/ioconfig/filename) { get; set; } | Der Dateiname der Export-/Importszene. Dies ist optional, aber nützlich, wenn externe Assets wie OBJ-Material serialisiert werden. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem) { get; set; } | Dem Benutzer erlauben, die externen Abhängigkeiten während des Ladens/Speicherns zu verwalten. |
| [FoldRepeatedCurveData](../../aspose.threed.formats/fbxsaveoptions/foldrepeatedcurvedata) { get; set; } | Ruft ab oder legt fest, ob wiederholte Kurvendaten wiederverwendet werden, indem der Referenzzähler der letzten Daten erhöht wird |
| [GenerateVertexElementMaterial](../../aspose.threed.formats/fbxsaveoptions/generatevertexelementmaterial) { get; set; } | Ruft ab oder legt fest, ob immer a generiert wird[`VertexElementMaterial`](../../aspose.threed.entities/vertexelementmaterial) für Geometrien, wenn der angehängte Knoten Materialien enthält. Dies ist standardmäßig deaktiviert. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths) { get; set; } | Einige Dateien wie OBJ hängen von einer externen Datei ab, die Suchpfade ermöglichen es Aspose.3D, nach externen Dateien zum Laden zu suchen. |
| [ReusePrimitiveMesh](../../aspose.threed.formats/fbxsaveoptions/reuseprimitivemesh) { get; set; } | Verwenden Sie das Netz für die Primitiven mit denselben Parametern erneut. Dadurch wird die Größe der FBX-Ausgabe erheblich reduziert, deren Szene aus einer großen Menge primitiver Formen (wie aus CAD-Dateien importiert) erstellt wurde. Der Standardwert ist false |
| [VideoForTexture](../../aspose.threed.formats/fbxsaveoptions/videofortexture) { get; set; } | Ruft ab oder legt fest, ob eine Videoinstanz generiert wird für[`Texture`](../../aspose.threed.shading/texture) beim Export als FBX. |

### Siehe auch

* class [SaveOptions](../saveoptions)
* namensraum [Aspose.ThreeD.Formats](../../aspose.threed.formats)
* Montage [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->