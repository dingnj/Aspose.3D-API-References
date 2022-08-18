---
title: RenderFactory
second_title: Aspose.3D for .NET API Referansı
description: RenderFactory işleme hattında temsil edilen tüm kaynakları oluşturur.
type: docs
weight: 2040
url: /tr/net/aspose.threed.render/renderfactory/
---
## RenderFactory class

RenderFactory, işleme hattında temsil edilen tüm kaynakları oluşturur.

```csharp
public abstract class RenderFactory
```

## yöntemler

| İsim | Tanım |
| --- | --- |
| abstract [CreateCubeRenderTexture](../../aspose.threed.render/renderfactory/createcuberendertexture)(RenderParameters, int, int) | 1 küp doku içeren bir oluşturma hedefi oluşturun |
| abstract [CreateDescriptorSet](../../aspose.threed.render/renderfactory/createdescriptorset)(ShaderProgram) | Belirtilen gölgelendirici programı için tanımlayıcı kümesi oluşturun. |
| abstract [CreateIndexBuffer](../../aspose.threed.render/renderfactory/createindexbuffer)() | [`IIndexBuffer`](../iindexbuffer) çokgenin yüz bilgilerini saklamak için örnek. |
| abstract [CreatePipeline](../../aspose.threed.render/renderfactory/createpipeline)(ShaderProgram, RenderState, VertexDeclaration, DrawOperation) | Önceden yapılandırılmış gölgelendirici/oluşturma durumu/köşe bildirimi ve çizim işlemleriyle önceden yapılandırılmış bir grafik ardışık düzeni oluşturun. |
| abstract [CreateRenderTexture](../../aspose.threed.render/renderfactory/createrendertexture#createrendertexture)(RenderParameters, int, int) | Oluşturma hedefi oluşturun, texture 'yi oluşturan 1 hedef içerir |
| abstract [CreateRenderTexture](../../aspose.threed.render/renderfactory/createrendertexture#createrendertexture_1)(RenderParameters, int, int, int) | texture 'yi oluşturan bir işleme hedefi oluşturun |
| abstract [CreateRenderWindow](../../aspose.threed.render/renderfactory/createrenderwindow)(RenderParameters, WindowHandle) | Yerel pencereye işleyen bir oluşturma hedefi oluşturun. |
| abstract [CreateShaderProgram](../../aspose.threed.render/renderfactory/createshaderprogram)(ShaderSource) | [`ShaderProgram`](../shaderprogram) nesne |
| [CreateTextureUnit](../../aspose.threed.render/renderfactory/createtextureunit#createtextureunit)() | Gölgelendirici tarafından erişilebilen bir 2B doku birimi oluşturun. |
| abstract [CreateTextureUnit](../../aspose.threed.render/renderfactory/createtextureunit#createtextureunit_1)(TextureType) | Gölgelendirici tarafından erişilebilen bir doku birimi oluşturun. |
| abstract [CreateUniformBuffer](../../aspose.threed.render/renderfactory/createuniformbuffer)(int) | Önceden ayrılmış boyutla GPU tarafında yeni bir tek biçimli arabellek oluşturun. |
| abstract [CreateVertexBuffer](../../aspose.threed.render/renderfactory/createvertexbuffer)(VertexDeclaration) | [`IVertexBuffer`](../ivertexbuffer) çokgenin köşe bilgilerini depolamak için örnek. |

### Ayrıca bakınız

* ad alanı [Aspose.ThreeD.Render](../../aspose.threed.render)
* toplantı [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->