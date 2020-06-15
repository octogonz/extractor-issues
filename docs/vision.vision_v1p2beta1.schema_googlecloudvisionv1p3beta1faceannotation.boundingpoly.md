<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@google/vision](./vision.md) &gt; [vision\_v1p2beta1](./vision.vision_v1p2beta1.md) &gt; [Schema$GoogleCloudVisionV1p3beta1FaceAnnotation](./vision.vision_v1p2beta1.schema_googlecloudvisionv1p3beta1faceannotation.md) &gt; [boundingPoly](./vision.vision_v1p2beta1.schema_googlecloudvisionv1p3beta1faceannotation.boundingpoly.md)

## vision\_v1p2beta1.Schema$GoogleCloudVisionV1p3beta1FaceAnnotation.boundingPoly property

The bounding polygon around the face. The coordinates of the bounding box are in the original image's scale. The bounding box is computed to "frame" the face in accordance with human expectations. It is based on the landmarker results. Note that one or more x and/or y coordinates may not be generated in the `BoundingPoly` (the polygon will be unbounded) if only a partial face appears in the image to be annotated.

<b>Signature:</b>

```typescript
boundingPoly?: Schema$GoogleCloudVisionV1p3beta1BoundingPoly;
```