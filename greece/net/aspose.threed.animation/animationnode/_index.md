---
title: AnimationNode
second_title: Aspose.3D για Αναφορά API .NET
description: Το Το Aspose.3D υποστηρίζει την ιεραρχία κινούμενων εικόνων κάθε κινούμενη εικόνα μπορεί να συντεθεί από πολλά κινούμενα σχέδια και τον ορισμό του βασικού καρέ του κινούμενου σχεδίου. AnimationNode./animationnode/ ορίζει τον μετασχηματισμό μιας τιμής ιδιότητας με την πάροδο του χρόνου για παράδειγμα ο κόμβος κίνησης μπορεί να χρησιμοποιηθεί για τον έλεγχο του μετασχηματισμού ενός κόμβου ή άλλουA3DObject../aspose.threed/a3dobject/ αριθμητικές ιδιότητες αντικειμένου.
type: docs
weight: 40
url: /el/net/aspose.threed.animation/animationnode/
---
## AnimationNode class

Το Το Aspose.3D υποστηρίζει την ιεραρχία κινούμενων εικόνων, κάθε κινούμενη εικόνα μπορεί να συντεθεί από πολλά κινούμενα σχέδια και τον ορισμό του βασικού καρέ του κινούμενου σχεδίου. `AnimationNode` ορίζει τον μετασχηματισμό μιας τιμής ιδιότητας με την πάροδο του χρόνου, για παράδειγμα, ο κόμβος κίνησης μπορεί να χρησιμοποιηθεί για τον έλεγχο του μετασχηματισμού ενός κόμβου ή άλλου[`A3DObject`](../../aspose.threed/a3dobject/) αριθμητικές ιδιότητες αντικειμένου.

```csharp
public class AnimationNode : A3DObject
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [AnimationNode](animationnode/#constructor)() | Αρχικοποιεί μια νέα παρουσία του`AnimationNode` τάξη. |
| [AnimationNode](animationnode/#constructor_1)(string) | Αρχικοποιεί μια νέα παρουσία του`AnimationNode` τάξη. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [BindPoints](../../aspose.threed.animation/animationnode/bindpoints/) { get; } | Λαμβάνει την τρέχουσα ιδιότητα bind points |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Παίρνει ή ορίζει το όνομα. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Λαμβάνει τη συλλογή όλων των ιδιοτήτων. |
| [SubAnimations](../../aspose.threed.animation/animationnode/subanimations/) { get; } | Λαμβάνει τους κόμβους υποκινούμενων εικόνων στα τρέχοντα animations |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| [CreateBindPoint](../../aspose.threed.animation/animationnode/createbindpoint/)(A3DObject, string) | Δημιουργεί ένα BindPoint με βάση τον τύπο δεδομένων ιδιότητας. |
| [FindBindPoint](../../aspose.threed.animation/animationnode/findbindpoint/)(string) | Βρίσκει το σημείο σύνδεσης με το όνομα. |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Βρίσκει την ιδιότητα. Μπορεί να είναι μια δυναμική ιδιότητα (Δημιουργήθηκε από CreateDynamicProperty/SetProperty) ή εγγενής ιδιότητα (Αναγνωρίζεται από το όνομά της) |
| [GetBindPoint](../../aspose.threed.animation/animationnode/getbindpoint/)(A3DObject, string, bool) | Λαμβάνει το σημείο σύνδεσης κινούμενων εικόνων σε δεδομένη ιδιότητα. |
| [GetKeyframeSequence](../../aspose.threed.animation/animationnode/getkeyframesequence/#getkeyframesequence)(A3DObject, string, bool) | Λαμβάνει την ακολουθία βασικών καρέ σε δεδομένη ιδιότητα. |
| [GetKeyframeSequence](../../aspose.threed.animation/animationnode/getkeyframesequence/#getkeyframesequence_1)(A3DObject, string, string, bool) | Λαμβάνει την ακολουθία βασικών καρέ σε δεδομένη ιδιότητα και κανάλι. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Λάβετε την τιμή της καθορισμένης ιδιότητας |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Καταργεί μια δυναμική ιδιότητα. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Καταργήστε την καθορισμένη ιδιότητα που προσδιορίζεται με όνομα |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Ορίζει την τιμή της καθορισμένης ιδιότητας |

### Δείτε επίσης

* class [A3DObject](../../aspose.threed/a3dobject/)
* χώρος ονομάτων [Aspose.ThreeD.Animation](../../aspose.threed.animation/)
* συνέλευση [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->