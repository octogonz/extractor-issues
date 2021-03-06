<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@google/vision](./vision.md) &gt; [vision\_v1p2beta1](./vision.vision_v1p2beta1.md) &gt; [Schema$GoogleCloudVisionV1p2beta1BatchAnnotateImagesRequest](./vision.vision_v1p2beta1.schema_googlecloudvisionv1p2beta1batchannotateimagesrequest.md)

## vision\_v1p2beta1.Schema$GoogleCloudVisionV1p2beta1BatchAnnotateImagesRequest interface

Multiple image annotation requests are batched into a single service call.

<b>Signature:</b>

```typescript
export interface Schema$GoogleCloudVisionV1p2beta1BatchAnnotateImagesRequest 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [parent](./vision.vision_v1p2beta1.schema_googlecloudvisionv1p2beta1batchannotateimagesrequest.parent.md) | string \| null | Optional. Target project and location to make a call.<!-- -->Format: <code>projects/{project-id\}/locations/{location-id\}</code>.<!-- -->If no parent is specified, a region will be chosen automatically.<!-- -->Supported location-ids: <code>us</code>: USA country only, <code>asia</code>: East asia areas, like Japan, Taiwan, <code>eu</code>: The European Union.<!-- -->Example: <code>projects/project-A/locations/eu</code>. |
|  [requests](./vision.vision_v1p2beta1.schema_googlecloudvisionv1p2beta1batchannotateimagesrequest.requests.md) | [Schema$GoogleCloudVisionV1p2beta1AnnotateImageRequest](./vision.vision_v1p2beta1.schema_googlecloudvisionv1p2beta1annotateimagerequest.md)<!-- -->\[\] | Required. Individual image annotation requests for this batch. |

