---
title: IRenderTexture
second_title: Aspose.3D for Java API Reference
description: The interface of render texture
type: docs
weight: 227
url: /java/com.aspose.threed/irendertexture/
---

**All Implemented Interfaces:**
[com.aspose.threed.IRenderTarget](../../com.aspose.threed/irendertarget)
```
public interface IRenderTexture extends IRenderTarget
```

The interface of render texture
## Methods

| Method | Description |
| --- | --- |
| [getTargets()](#getTargets--) | Color output targets. |
| [getDepthTexture()](#getDepthTexture--) | Depth buffer texture |
### getTargets() {#getTargets--}
```
public abstract List<ITextureUnit> getTargets()
```


Color output targets.

**Returns:**
java.util.List<com.aspose.threed.ITextureUnit>
### getDepthTexture() {#getDepthTexture--}
```
public abstract ITextureUnit getDepthTexture()
```


Depth buffer texture

**Returns:**
[ITextureUnit](../../com.aspose.threed/itextureunit)