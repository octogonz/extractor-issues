<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@google/vision](./vision.md) &gt; [vision\_v1p1beta1](./vision.vision_v1p1beta1.md) &gt; [Schema$GoogleCloudVisionV1p2beta1CropHint](./vision.vision_v1p1beta1.schema_googlecloudvisionv1p2beta1crophint.md)

## vision\_v1p1beta1.Schema$GoogleCloudVisionV1p2beta1CropHint interface

Single crop hint that is used to generate a new crop when serving an image.

<b>Signature:</b>

```typescript
export interface Schema$GoogleCloudVisionV1p2beta1CropHint 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [boundingPoly](./vision.vision_v1p1beta1.schema_googlecloudvisionv1p2beta1crophint.boundingpoly.md) | [Schema$GoogleCloudVisionV1p2beta1BoundingPoly](./vision.vision_v1p1beta1.schema_googlecloudvisionv1p2beta1boundingpoly.md) | The bounding polygon for the crop region. The coordinates of the bounding box are in the original image's scale. |
|  [confidence](./vision.vision_v1p1beta1.schema_googlecloudvisionv1p2beta1crophint.confidence.md) | number \| null | Confidence of this being a salient region. Range \[0, 1\]. |
|  [importanceFraction](./vision.vision_v1p1beta1.schema_googlecloudvisionv1p2beta1crophint.importancefraction.md) | number \| null | Fraction of importance of this salient region with respect to the original image. |

