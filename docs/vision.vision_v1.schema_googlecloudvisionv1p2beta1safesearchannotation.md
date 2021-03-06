<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@google/vision](./vision.md) &gt; [vision\_v1](./vision.vision_v1.md) &gt; [Schema$GoogleCloudVisionV1p2beta1SafeSearchAnnotation](./vision.vision_v1.schema_googlecloudvisionv1p2beta1safesearchannotation.md)

## vision\_v1.Schema$GoogleCloudVisionV1p2beta1SafeSearchAnnotation interface

Set of features pertaining to the image, computed by computer vision methods over safe-search verticals (for example, adult, spoof, medical, violence).

<b>Signature:</b>

```typescript
export interface Schema$GoogleCloudVisionV1p2beta1SafeSearchAnnotation 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [adult](./vision.vision_v1.schema_googlecloudvisionv1p2beta1safesearchannotation.adult.md) | string \| null | Represents the adult content likelihood for the image. Adult content may contain elements such as nudity, pornographic images or cartoons, or sexual activities. |
|  [medical](./vision.vision_v1.schema_googlecloudvisionv1p2beta1safesearchannotation.medical.md) | string \| null | Likelihood that this is a medical image. |
|  [racy](./vision.vision_v1.schema_googlecloudvisionv1p2beta1safesearchannotation.racy.md) | string \| null | Likelihood that the request image contains racy content. Racy content may include (but is not limited to) skimpy or sheer clothing, strategically covered nudity, lewd or provocative poses, or close-ups of sensitive body areas. |
|  [spoof](./vision.vision_v1.schema_googlecloudvisionv1p2beta1safesearchannotation.spoof.md) | string \| null | Spoof likelihood. The likelihood that an modification was made to the image's canonical version to make it appear funny or offensive. |
|  [violence](./vision.vision_v1.schema_googlecloudvisionv1p2beta1safesearchannotation.violence.md) | string \| null | Likelihood that this image contains violent content. |

