<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@google/vision](./vision.md) &gt; [vision\_v1](./vision.vision_v1.md) &gt; [Schema$GoogleCloudVisionV1p3beta1ColorInfo](./vision.vision_v1.schema_googlecloudvisionv1p3beta1colorinfo.md)

## vision\_v1.Schema$GoogleCloudVisionV1p3beta1ColorInfo interface

Color information consists of RGB channels, score, and the fraction of the image that the color occupies in the image.

<b>Signature:</b>

```typescript
export interface Schema$GoogleCloudVisionV1p3beta1ColorInfo 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [color](./vision.vision_v1.schema_googlecloudvisionv1p3beta1colorinfo.color.md) | [Schema$Color](./vision.vision_v1.schema_color.md) | RGB components of the color. |
|  [pixelFraction](./vision.vision_v1.schema_googlecloudvisionv1p3beta1colorinfo.pixelfraction.md) | number \| null | The fraction of pixels the color occupies in the image. Value in range \[0, 1\]. |
|  [score](./vision.vision_v1.schema_googlecloudvisionv1p3beta1colorinfo.score.md) | number \| null | Image-specific score for this color. Value in range \[0, 1\]. |

