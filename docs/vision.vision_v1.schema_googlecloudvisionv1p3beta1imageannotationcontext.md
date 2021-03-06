<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@google/vision](./vision.md) &gt; [vision\_v1](./vision.vision_v1.md) &gt; [Schema$GoogleCloudVisionV1p3beta1ImageAnnotationContext](./vision.vision_v1.schema_googlecloudvisionv1p3beta1imageannotationcontext.md)

## vision\_v1.Schema$GoogleCloudVisionV1p3beta1ImageAnnotationContext interface

If an image was produced from a file (e.g. a PDF), this message gives information about the source of that image.

<b>Signature:</b>

```typescript
export interface Schema$GoogleCloudVisionV1p3beta1ImageAnnotationContext 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [pageNumber](./vision.vision_v1.schema_googlecloudvisionv1p3beta1imageannotationcontext.pagenumber.md) | number \| null | If the file was a PDF or TIFF, this field gives the page number within the file used to produce the image. |
|  [uri](./vision.vision_v1.schema_googlecloudvisionv1p3beta1imageannotationcontext.uri.md) | string \| null | The URI of the file used to produce the image. |

