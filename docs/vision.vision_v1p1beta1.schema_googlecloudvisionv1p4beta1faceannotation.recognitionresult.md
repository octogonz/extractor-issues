<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@google/vision](./vision.md) &gt; [vision\_v1p1beta1](./vision.vision_v1p1beta1.md) &gt; [Schema$GoogleCloudVisionV1p4beta1FaceAnnotation](./vision.vision_v1p1beta1.schema_googlecloudvisionv1p4beta1faceannotation.md) &gt; [recognitionResult](./vision.vision_v1p1beta1.schema_googlecloudvisionv1p4beta1faceannotation.recognitionresult.md)

## vision\_v1p1beta1.Schema$GoogleCloudVisionV1p4beta1FaceAnnotation.recognitionResult property

Additional recognition information. Only computed if image\_context.face\_recognition\_params is provided, \*\*and\*\* a match is found to a Celebrity in the input CelebritySet. This field is sorted in order of decreasing confidence values.

<b>Signature:</b>

```typescript
recognitionResult?: Schema$GoogleCloudVisionV1p4beta1FaceRecognitionResult[];
```
