---
title: Discreet3dsLoadOptions
second_title: Riferimento API Aspose.3D per .NET
description: Carica opzioni per file 3DS.
type: docs
weight: 1060
url: /it/net/aspose.threed.formats/discreet3dsloadoptions/
---
## Discreet3dsLoadOptions class

Carica opzioni per file 3DS.

```csharp
public class Discreet3dsLoadOptions : LoadOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Discreet3dsLoadOptions](discreet3dsloadoptions)() | Costruttore di[`Discreet3dsLoadOptions`](../discreet3dsloadoptions) |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [ApplyAnimationTransform](../../aspose.threed.formats/discreet3dsloadoptions/applyanimationtransform) { get; set; } | Ottiene o imposta se utilizzare la trasformazione definita nel primo fotogramma della traccia di animazione. |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding) { get; set; } | Ottiene o imposta la codifica predefinita per i file di testo. Il valore predefinito è null, il che significa che l'importatore/esportatore deciderà quale codifica utilizzare. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat) { get; } | Ottiene il formato file specificato nell'opzione Salva/Carica corrente. |
| [FileName](../../aspose.threed.formats/ioconfig/filename) { get; set; } | Il nome del file della scena di esportazione/importazione. Questo è facoltativo, ma utile quando si serializzano risorse esterne come il materiale di OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem) { get; set; } | Consenti all'utente di gestire come gestire le dipendenze esterne durante il caricamento/salvataggio. |
| [FlipCoordinateSystem](../../aspose.threed.formats/discreet3dsloadoptions/flipcoordinatesystem) { get; set; } | Ottiene o imposta il sistema di coordinate di inversione dei punti di controllo/normali durante l'importazione/esportazione. |
| [GammaCorrectedColor](../../aspose.threed.formats/discreet3dsloadoptions/gammacorrectedcolor) { get; set; } | Un file 3ds può contenere il colore originale e il colore corretto per la gamma per lo stesso attributo, Impostandolo su true utilizzerà il colore corretto per la gamma, se possibile, altrimenti Aspose.3D proverà a utilizzare il colore originale. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths) { get; set; } | Alcuni file come OBJ dipendono da un file esterno, i percorsi di ricerca consentiranno ad Aspose.3D di cercare il file esterno da caricare. |

### Guarda anche

* class [LoadOptions](../loadoptions)
* spazio dei nomi [Aspose.ThreeD.Formats](../../aspose.threed.formats)
* assemblea [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->