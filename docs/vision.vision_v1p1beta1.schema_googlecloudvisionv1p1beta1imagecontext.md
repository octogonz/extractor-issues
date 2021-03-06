<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@google/vision](./vision.md) &gt; [vision\_v1p1beta1](./vision.vision_v1p1beta1.md) &gt; [Schema$GoogleCloudVisionV1p1beta1ImageContext](./vision.vision_v1p1beta1.schema_googlecloudvisionv1p1beta1imagecontext.md)

## vision\_v1p1beta1.Schema$GoogleCloudVisionV1p1beta1ImageContext interface

Image context and/or feature-specific parameters.

<b>Signature:</b>

```typescript
export interface Schema$GoogleCloudVisionV1p1beta1ImageContext 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [cropHintsParams](./vision.vision_v1p1beta1.schema_googlecloudvisionv1p1beta1imagecontext.crophintsparams.md) | [Schema$GoogleCloudVisionV1p1beta1CropHintsParams](./vision.vision_v1p1beta1.schema_googlecloudvisionv1p1beta1crophintsparams.md) | Parameters for crop hints annotation request. |
|  [languageHints](./vision.vision_v1p1beta1.schema_googlecloudvisionv1p1beta1imagecontext.languagehints.md) | string\[\] \| null | List of languages to use for TEXT\_DETECTION. In most cases, an empty value yields the best results since it enables automatic language detection. For languages based on the Latin alphabet, setting <code>language_hints</code> is not needed. In rare cases, when the language of the text in the image is known, setting a hint will help get better results (although it will be a significant hindrance if the hint is wrong). Text detection returns an error if one or more of the specified languages is not one of the \[supported languages\](https://cloud.google.com/vision/docs/languages). |
|  [latLongRect](./vision.vision_v1p1beta1.schema_googlecloudvisionv1p1beta1imagecontext.latlongrect.md) | [Schema$GoogleCloudVisionV1p1beta1LatLongRect](./vision.vision_v1p1beta1.schema_googlecloudvisionv1p1beta1latlongrect.md) | Not used. |
|  [productSearchParams](./vision.vision_v1p1beta1.schema_googlecloudvisionv1p1beta1imagecontext.productsearchparams.md) | [Schema$GoogleCloudVisionV1p1beta1ProductSearchParams](./vision.vision_v1p1beta1.schema_googlecloudvisionv1p1beta1productsearchparams.md) | Parameters for product search. |
|  [webDetectionParams](./vision.vision_v1p1beta1.schema_googlecloudvisionv1p1beta1imagecontext.webdetectionparams.md) | [Schema$GoogleCloudVisionV1p1beta1WebDetectionParams](./vision.vision_v1p1beta1.schema_googlecloudvisionv1p1beta1webdetectionparams.md) | Parameters for web detection. |

