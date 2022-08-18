---
title: Matrix4
second_title: Referencia de API de Aspose.3D para .NET
description: Implementación matriz 4x4.
type: docs
weight: 2560
url: /es/net/aspose.threed.utilities/matrix4/
---
## Matrix4 structure

Implementación matriz 4x4.

```csharp
public struct Matrix4
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Matrix4](matrix4#constructor_3)(double[]) | Inicializa una nueva instancia del[`Matrix4`](../matrix4) estructura. |
| [Matrix4](matrix4#constructor)(FMatrix4) | Construir[`Matrix4`](../matrix4) desde un[`FMatrix4`](../fmatrix4) instancia |
| [Matrix4](matrix4#constructor_1)(Vector4, Vector4, Vector4, Vector4) | Construye matriz a partir de 4 filas. |
| [Matrix4](matrix4#constructor_2)(double, double, double, double, double, double, double, double, double, double, double, double, double, double, double, double) | Inicializa una nueva instancia del[`Matrix4`](../matrix4) estructura. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| static [Identity](../../aspose.threed.utilities/matrix4/identity) { get; } | Obtiene la matriz identidad. |
| [Determinant](../../aspose.threed.utilities/matrix4/determinant) { get; } | Obtiene el determinante de la matriz. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [Rotate](../../aspose.threed.utilities/matrix4/rotate#rotate)(Quaternion) | Crear una matriz de rotación a partir de un quaternion |
| static [Rotate](../../aspose.threed.utilities/matrix4/rotate#rotate_1)(double, Vector3) | Crear una matriz de rotación por ángulo de rotación y eje |
| static [RotateFromEuler](../../aspose.threed.utilities/matrix4/rotatefromeuler#rotatefromeuler)(Vector3) | Crear una matriz de rotación a partir del ángulo de Euler |
| static [RotateFromEuler](../../aspose.threed.utilities/matrix4/rotatefromeuler#rotatefromeuler_1)(double, double, double) | Crear una matriz de rotación a partir del ángulo de Euler |
| static [Scale](../../aspose.threed.utilities/matrix4/scale#scale_1)(double) | Crea una matriz que escala a lo largo del eje x, el eje y y el eje z. |
| static [Scale](../../aspose.threed.utilities/matrix4/scale#scale)(Vector3) | Crea una matriz que escala a lo largo del eje x, el eje y y el eje z. |
| static [Scale](../../aspose.threed.utilities/matrix4/scale#scale_2)(double, double, double) | Crea una matriz que escala a lo largo del eje x, el eje y y el eje z. |
| static [Translate](../../aspose.threed.utilities/matrix4/translate#translate)(Vector3) | Crea una matriz que se traslada a lo largo del eje x, el eje y y el eje z |
| static [Translate](../../aspose.threed.utilities/matrix4/translate#translate_1)(double, double, double) | Crea una matriz que se traslada a lo largo del eje x, el eje y y el eje z |
| [Concatenate](../../aspose.threed.utilities/matrix4/concatenate)(Matrix4) | Concatena las dos matrices |
| [Decompose](../../aspose.threed.utilities/matrix4/decompose)(out Vector3, out Vector3, out Quaternion) |  |
| [Inverse](../../aspose.threed.utilities/matrix4/inverse)() | Invierte esta instancia. |
| [Normalize](../../aspose.threed.utilities/matrix4/normalize)() | Normaliza esta instancia. |
| [SetTRS](../../aspose.threed.utilities/matrix4/settrs)(Vector3, Vector3, Vector3) | Inicializa la matriz con traslación/rotación/escala |
| [ToArray](../../aspose.threed.utilities/matrix4/toarray)() | Convierte matriz en arreglo. |
| override [ToString](../../aspose.threed.utilities/matrix4/tostring)() | Devuelve unStringque representa la corriente[`Matrix4`](../matrix4) . |
| [Transpose](../../aspose.threed.utilities/matrix4/transpose)() | Transpone esta instancia. |
| [operator *](../../aspose.threed.utilities/matrix4/op_multiply#op_multiply) | Multiplica las dos matrices (4 operators) |

## Campos

| Nombre | Descripción |
| --- | --- |
| [m00](../../aspose.threed.utilities/matrix4/m00) | El m00. |
| [m01](../../aspose.threed.utilities/matrix4/m01) | El m01. |
| [m02](../../aspose.threed.utilities/matrix4/m02) | El m02. |
| [m03](../../aspose.threed.utilities/matrix4/m03) | El m03. |
| [m10](../../aspose.threed.utilities/matrix4/m10) | El m10. |
| [m11](../../aspose.threed.utilities/matrix4/m11) | El m11. |
| [m12](../../aspose.threed.utilities/matrix4/m12) | El m12. |
| [m13](../../aspose.threed.utilities/matrix4/m13) | El m13. |
| [m20](../../aspose.threed.utilities/matrix4/m20) | El m20. |
| [m21](../../aspose.threed.utilities/matrix4/m21) | El m21. |
| [m22](../../aspose.threed.utilities/matrix4/m22) | El m22. |
| [m23](../../aspose.threed.utilities/matrix4/m23) | El m23. |
| [m30](../../aspose.threed.utilities/matrix4/m30) | El m30. |
| [m31](../../aspose.threed.utilities/matrix4/m31) | El m31. |
| [m32](../../aspose.threed.utilities/matrix4/m32) | El m32. |
| [m33](../../aspose.threed.utilities/matrix4/m33) | El m33. |

### Ver también

* espacio de nombres [Aspose.ThreeD.Utilities](../../aspose.threed.utilities)
* asamblea [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->