---
title: GltfSaveOptions
second_title: .NET API संदर्भ के लिए Aspose.3D
description: जएलटएफ प्ररूप के लए वकल्प सहेजें
type: docs
weight: 1160
url: /hi/net/aspose.threed.formats/gltfsaveoptions/
---
## GltfSaveOptions class

जीएलटीएफ प्रारूप के लिए विकल्प सहेजें।

```csharp
public class GltfSaveOptions : SaveOptions
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [GltfSaveOptions](gltfsaveoptions/#constructor)(FileContentType) | का निर्माता`GltfSaveOptions` |
| [GltfSaveOptions](gltfsaveoptions/#constructor_1)(FileFormat) | का निर्माता`GltfSaveOptions` |

## गुण

| नाम | विवरण |
| --- | --- |
| [BufferFile](../../aspose.threed.formats/gltfsaveoptions/bufferfile/) { get; set; } | बाइनरी डेटा स्टोर करने के लिए उपयोग की जाने वाली बाहरी बफर फ़ाइल का फ़ाइल नाम। |
| [DracoCompression](../../aspose.threed.formats/gltfsaveoptions/dracocompression/) { get; set; } | ड्रैको संपीड़न सक्षम करने के लिए प्राप्त करता है या सेट करता है |
| [EmbedAssets](../../aspose.threed.formats/gltfsaveoptions/embedassets/) { get; set; } | एएससीआईआई मोड में एकल फ़ाइल में सभी बाहरी संपत्तियों को बेस64 के रूप में एम्बेड करें, डिफ़ॉल्ट मान गलत है। |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | टेक्स्ट-आधारित फ़ाइलों के लिए डिफ़ॉल्ट एन्कोडिंग प्राप्त या सेट करता है। |
| [ExternalDracoEncoder](../../aspose.threed.formats/gltfsaveoptions/externaldracoencoder/) { get; set; } | ड्रेको संपीड़न गति को तेज करने के लिए बाहरी ड्रेको एनकोडर का उपयोग करें। |
| [FallbackNormal](../../aspose.threed.formats/gltfsaveoptions/fallbacknormal/) { get; set; } | जब GLTF2 निर्यातक ने एक अमान्य सामान्य का पता लगाया, तो सत्यापन को बायपास करने के लिए इसके मूल मान के बजाय इसका उपयोग किया जाएगा। डिफ़ॉल्ट मान (0, 1, 0) है |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | वर्तमान सहेजें/लोड विकल्प में निर्दिष्ट फ़ाइल स्वरूप प्राप्त करता है। |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | निर्यात/आयात करने वाले दृश्य का फ़ाइल नाम। यह वैकल्पिक है, लेकिन बाहरी संपत्ति जैसे ओबीजे की सामग्री को क्रमबद्ध करते समय उपयोगी है। |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | लोड/सेव के दौरान बाहरी निर्भरताओं को प्रबंधित करने के तरीके को संभालने के लिए उपयोगकर्ता को अनुमति दें. |
| [FlipTexCoordV](../../aspose.threed.formats/gltfsaveoptions/fliptexcoordv/) { get; set; } | फ़्लिप बनावट निर्देशांक v(t) घटक, डिफ़ॉल्ट मान सत्य है। |
| [ImageFormat](../../aspose.threed.formats/gltfsaveoptions/imageformat/) { get; set; } | मानक जीएलटीएफ अपने बनावट प्रारूप के रूप में केवल पीएनजी/जेपीजी का समर्थन करता है, यह विकल्प मार्गदर्शन करेगा कि कैसे Aspose.3D निर्यात के दौरान गैर-मानक छवियों को समर्थित प्रारूप में परिवर्तित करें। डिफ़ॉल्ट मान हैPng |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | ओबीजे जैसी कुछ फाइलें बाहरी फाइल पर निर्भर करती हैं, लुकअप पथ Aspose.3D को लोड करने के लिए बाहरी फाइल देखने की अनुमति देगा। |
| [MaterialConverter](../../aspose.threed.formats/gltfsaveoptions/materialconverter/) { get; set; } | ज्यामिति की सामग्री को PBR सामग्री में बदलने के लिए कस्टम कन्वर्टर यदि यह असाइन नहीं किया गया है, तो glTF 2.0 निर्यातक स्वचालित रूप से मानक सामग्री को PBR सामग्री में बदल देगा। डिफ़ॉल्ट मान है null इस गुण का उपयोग किसी दृश्य को glTF 2.0 फ़ाइल में निर्यात करते समय किया जाता है। |
| [PrettyPrint](../../aspose.threed.formats/gltfsaveoptions/prettyprint/) { get; set; } | GLTF फ़ाइल की JSON सामग्री मानव पढ़ने के लिए इंडेंट है, डिफ़ॉल्ट मान false है |
| [SaveExtras](../../aspose.threed.formats/gltfsaveoptions/saveextras/) { get; set; } | जनरेट की गई glTF फ़ाइल में 'अतिरिक्त' फ़ील्ड में दृश्य वस्तु के गतिशील गुणों को सहेजें। यह एप्लिकेशन-विशिष्ट डेटा प्रदान करने के लिए उपयोगी है। डिफ़ॉल्ट मान गलत है। |
| [UseCommonMaterials](../../aspose.threed.formats/gltfsaveoptions/usecommonmaterials/) { get; set; } | केएचआर सामान्य सामग्री एक्सटेंशन का उपयोग करके सामग्री को क्रमबद्ध करें, डिफ़ॉल्ट मान गलत है। इसे गलत पर सेट करें क्योंकि Aspose.3D निर्यात वर्टेक्स/फ्रैगमेंट शेडर का एक सेट होगा यदिExportShaders |

### यह सभी देखें

* class [SaveOptions](../saveoptions/)
* नाम स्थान [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* सभा [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->