<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@google/vision](./vision.md) &gt; [vision\_v1](./vision.vision_v1.md) &gt; [Schema$GoogleCloudVisionV1p3beta1WebDetectionWebPage](./vision.vision_v1.schema_googlecloudvisionv1p3beta1webdetectionwebpage.md)

## vision\_v1.Schema$GoogleCloudVisionV1p3beta1WebDetectionWebPage interface

Metadata for web pages.

<b>Signature:</b>

```typescript
export interface Schema$GoogleCloudVisionV1p3beta1WebDetectionWebPage 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [fullMatchingImages](./vision.vision_v1.schema_googlecloudvisionv1p3beta1webdetectionwebpage.fullmatchingimages.md) | [Schema$GoogleCloudVisionV1p3beta1WebDetectionWebImage](./vision.vision_v1.schema_googlecloudvisionv1p3beta1webdetectionwebimage.md)<!-- -->\[\] | Fully matching images on the page. Can include resized copies of the query image. |
|  [pageTitle](./vision.vision_v1.schema_googlecloudvisionv1p3beta1webdetectionwebpage.pagetitle.md) | string \| null | Title for the web page, may contain HTML markups. |
|  [partialMatchingImages](./vision.vision_v1.schema_googlecloudvisionv1p3beta1webdetectionwebpage.partialmatchingimages.md) | [Schema$GoogleCloudVisionV1p3beta1WebDetectionWebImage](./vision.vision_v1.schema_googlecloudvisionv1p3beta1webdetectionwebimage.md)<!-- -->\[\] | Partial matching images on the page. Those images are similar enough to share some key-point features. For example an original image will likely have partial matching for its crops. |
|  [score](./vision.vision_v1.schema_googlecloudvisionv1p3beta1webdetectionwebpage.score.md) | number \| null | (Deprecated) Overall relevancy score for the web page. |
|  [url](./vision.vision_v1.schema_googlecloudvisionv1p3beta1webdetectionwebpage.url.md) | string \| null | The result web page URL. |
