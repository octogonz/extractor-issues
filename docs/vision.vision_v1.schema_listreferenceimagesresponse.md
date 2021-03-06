<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@google/vision](./vision.md) &gt; [vision\_v1](./vision.vision_v1.md) &gt; [Schema$ListReferenceImagesResponse](./vision.vision_v1.schema_listreferenceimagesresponse.md)

## vision\_v1.Schema$ListReferenceImagesResponse interface

Response message for the `ListReferenceImages` method.

<b>Signature:</b>

```typescript
export interface Schema$ListReferenceImagesResponse 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [nextPageToken](./vision.vision_v1.schema_listreferenceimagesresponse.nextpagetoken.md) | string \| null | The next\_page\_token returned from a previous List request, if any. |
|  [pageSize](./vision.vision_v1.schema_listreferenceimagesresponse.pagesize.md) | number \| null | The maximum number of items to return. Default 10, maximum 100. |
|  [referenceImages](./vision.vision_v1.schema_listreferenceimagesresponse.referenceimages.md) | [Schema$ReferenceImage](./vision.vision_v1.schema_referenceimage.md)<!-- -->\[\] | The list of reference images. |

