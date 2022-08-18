---
title: PbrSpecularMaterial
second_title: Aspose.3D لمرجع .NET API
description: مادة للتصيير المادي بناءً على الألوان المنتشرة / المرآوية / اللمعان
type: docs
weight: 2310
url: /ar/net/aspose.threed.shading/pbrspecularmaterial/
---
## PbrSpecularMaterial class

مادة للتصيير المادي بناءً على الألوان المنتشرة / المرآوية / اللمعان

```csharp
public class PbrSpecularMaterial : Material
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [PbrSpecularMaterial](pbrspecularmaterial)() | مُنشئ ملف[`PbrSpecularMaterial`](../pbrspecularmaterial) |

## الخصائص

| اسم | وصف |
| --- | --- |
| [Diffuse](../../aspose.threed.shading/pbrspecularmaterial/diffuse) { get; set; } | الحصول على اللون المنتشر للمادة أو تعيينه ، القيمة الافتراضية هي (1 ، 1 ، 1) |
| [DiffuseTexture](../../aspose.threed.shading/pbrspecularmaterial/diffusetexture) { get; set; } | الحصول على نسيج أو تعيينه للنشر |
| [EmissiveColor](../../aspose.threed.shading/pbrspecularmaterial/emissivecolor) { get; set; } | الحصول على اللون المنبعث أو تعيينه ، القيمة الافتراضية هي (0 ، 0 ، 0) |
| [EmissiveTexture](../../aspose.threed.shading/pbrspecularmaterial/emissivetexture) { get; set; } | الحصول على نسيج لل emissive أو تعيينه |
| [GlossinessFactor](../../aspose.threed.shading/pbrspecularmaterial/glossinessfactor) { get; set; } | الحصول على لمعان (نعومة) المادة أو ضبطه ، 1 يعني سلس تمامًا و 0 يعني تقريبيًا تمامًا ، القيمة الافتراضية هي 1 ، النطاق [0 ، 1] |
| virtual [Name](../../aspose.threed/a3dobject/name) { get; set; } | الحصول على الاسم أو تعيينه . |
| [NormalTexture](../../aspose.threed.shading/pbrspecularmaterial/normaltexture) { get; set; } | الحصول على نسيج التعيين العادي أو تعيينه |
| [Properties](../../aspose.threed/a3dobject/properties) { get; } | الحصول على مجموعة من كافة الخصائص . |
| [Specular](../../aspose.threed.shading/pbrspecularmaterial/specular) { get; set; } | الحصول على اللون المميز للمادة أو تعيينه ، القيمة الافتراضية هي (1 ، 1 ، 1) . |
| [SpecularGlossinessTexture](../../aspose.threed.shading/pbrspecularmaterial/specularglossinesstexture) { get; set; } | الحصول على نسيج للون براق أو ضبطه ، وتخزن قناة RGB اللون المرآوي والقناة A تخزن اللمعان. |
| [Transparency](../../aspose.threed.shading/pbrspecularmaterial/transparency) { get; set; } | الحصول على عامل الشفافية أو تعيينه . يجب أن يتراوح العامل بين 0 (0٪ ، معتم تمامًا) و 1 (100٪ ، شفاف تمامًا) سيتم تثبيت أي قيمة غير صالحة للعامل . |

## طُرق

| اسم | وصف |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty)(string) | البحث عن الخاصية. يمكن أن تكون خاصية ديناميكية (تم إنشاؤها بواسطة CreateDynamicProperty / SetProperty) أو خاصية أصلية (محددة باسمها) |
| [GetEnumerator](../../aspose.threed.shading/material/getenumerator)() | الحصول على العداد لتعداد فتحات النسيج الداخلي. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty)(string) | الحصول على قيمة الخاصية المحددة |
| [GetTexture](../../aspose.threed.shading/material/gettexture)(string) | الحصول على النسيج من الفتحة المحددة ، يمكن أن يكون اسم خاصية المادة أو اسم معلمة shader |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(Property) | يزيل خاصية ديناميكية . |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(string) | إزالة الخاصية المحددة المحددة بالاسم |
| [SetProperty](../../aspose.threed/a3dobject/setproperty)(string, object) | يحدد قيمة الخاصية المحددة |
| [SetTexture](../../aspose.threed.shading/material/settexture)(string, TextureBase) | يضبط النسيج على slot |
| override [ToString](../../aspose.threed.shading/material/tostring)() | كائن تنسيقات إلى string |

## مجالات

| اسم | وصف |
| --- | --- |
| const [MapSpecularGlossiness](../../aspose.threed.shading/pbrspecularmaterial/mapspecularglossiness) | خريطة النسيج لمعان مرآى |

### أنظر أيضا

* class [Material](../material)
* مساحة الاسم [Aspose.ThreeD.Shading](../../aspose.threed.shading)
* المجسم [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->