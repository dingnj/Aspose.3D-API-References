---
title: LambertMaterial
second_title: Aspose.3D for .NET API Referansı
description: Lambert gölgeleme malzemesi modeli
type: docs
weight: 2280
url: /tr/net/aspose.threed.shading/lambertmaterial/
---
## LambertMaterial class

Lambert gölgeleme malzemesi modeli

```csharp
public class LambertMaterial : Material
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [LambertMaterial](lambertmaterial#constructor)() | Yeni bir örneğini başlatır[`LambertMaterial`](../lambertmaterial) sınıf. |
| [LambertMaterial](lambertmaterial#constructor_1)(string) | Yeni bir örneğini başlatır[`LambertMaterial`](../lambertmaterial) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [AmbientColor](../../aspose.threed.shading/lambertmaterial/ambientcolor) { get; set; } | Ortam rengini alır veya ayarlar |
| [DiffuseColor](../../aspose.threed.shading/lambertmaterial/diffusecolor) { get; set; } | Yayılan rengi alır veya ayarlar |
| [EmissiveColor](../../aspose.threed.shading/lambertmaterial/emissivecolor) { get; set; } | Yayıcı rengi alır veya ayarlar |
| virtual [Name](../../aspose.threed/a3dobject/name) { get; set; } | Adı alır veya ayarlar. |
| [Properties](../../aspose.threed/a3dobject/properties) { get; } | Tüm özelliklerin koleksiyonunu alır. |
| [Transparency](../../aspose.threed.shading/lambertmaterial/transparency) { get; set; } | Saydamlık faktörünü alır veya ayarlar. Faktör, 0(0%, tamamen opak) ile 1(100%, tamamen şeffaf) arasında olmalıdır. Herhangi bir geçersiz faktör değeri sabitlenecektir. |
| [TransparentColor](../../aspose.threed.shading/lambertmaterial/transparentcolor) { get; set; } | Saydam rengi alır veya ayarlar. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty)(string) | Özelliği bulur. Dinamik bir özellik olabilir (CreateDynamicProperty/SetProperty tarafından oluşturulmuştur) veya yerel özellik (adıyla tanımlanır) |
| [GetEnumerator](../../aspose.threed.shading/material/getenumerator)() | Numaralandırıcının dahili doku yuvalarını numaralandırmasını sağlar. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty)(string) | Belirtilen özelliğin değerini alın |
| [GetTexture](../../aspose.threed.shading/material/gettexture)(string) | Belirtilen yuvadan dokuyu alır, malzemenin özellik adı veya gölgelendiricinin parametre adı olabilir |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(Property) | Dinamik bir özelliği kaldırır. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(string) | name ile tanımlanan belirtilen özelliği kaldırın |
| [SetProperty](../../aspose.threed/a3dobject/setproperty)(string, object) | Belirtilen özelliğin değerini ayarlar |
| [SetTexture](../../aspose.threed.shading/material/settexture)(string, TextureBase) | Dokuyu belirtilen slot olarak ayarlar |
| override [ToString](../../aspose.threed.shading/material/tostring)() | Nesneyi string olarak biçimlendirir |

### Ayrıca bakınız

* class [Material](../material)
* ad alanı [Aspose.ThreeD.Shading](../../aspose.threed.shading)
* toplantı [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->