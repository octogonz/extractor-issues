<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@google/vision](./vision.md) &gt; [vision\_v1p1beta1](./vision.vision_v1p1beta1.md) &gt; [Schema$AnnotateImageResponse](./vision.vision_v1p1beta1.schema_annotateimageresponse.md)

## vision\_v1p1beta1.Schema$AnnotateImageResponse interface

Response to an image annotation request.

<b>Signature:</b>

```typescript
export interface Schema$AnnotateImageResponse 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [context](./vision.vision_v1p1beta1.schema_annotateimageresponse.context.md) | [Schema$ImageAnnotationContext](./vision.vision_v1p1beta1.schema_imageannotationcontext.md) | If present, contextual information is needed to understand where this image comes from. |
|  [cropHintsAnnotation](./vision.vision_v1p1beta1.schema_annotateimageresponse.crophintsannotation.md) | [Schema$CropHintsAnnotation](./vision.vision_v1p1beta1.schema_crophintsannotation.md) | If present, crop hints have completed successfully. |
|  [error](./vision.vision_v1p1beta1.schema_annotateimageresponse.error.md) | [Schema$Status](./vision.vision_v1p1beta1.schema_status.md) | If set, represents the error message for the operation. Note that filled-in image annotations are guaranteed to be correct, even when <code>error</code> is set. |
|  [faceAnnotations](./vision.vision_v1p1beta1.schema_annotateimageresponse.faceannotations.md) | [Schema$FaceAnnotation](./vision.vision_v1p1beta1.schema_faceannotation.md)<!-- -->\[\] | If present, face detection has completed successfully. |
|  [fullTextAnnotation](./vision.vision_v1p1beta1.schema_annotateimageresponse.fulltextannotation.md) | [Schema$TextAnnotation](./vision.vision_v1p1beta1.schema_textannotation.md) | If present, text (OCR) detection or document (OCR) text detection has completed successfully. This annotation provides the structural hierarchy for the OCR detected text. |
|  [imagePropertiesAnnotation](./vision.vision_v1p1beta1.schema_annotateimageresponse.imagepropertiesannotation.md) | [Schema$ImageProperties](./vision.vision_v1p1beta1.schema_imageproperties.md) | If present, image properties were extracted successfully. |
|  [labelAnnotations](./vision.vision_v1p1beta1.schema_annotateimageresponse.labelannotations.md) | [Schema$EntityAnnotation](./vision.vision_v1p1beta1.schema_entityannotation.md)<!-- -->\[\] | If present, label detection has completed successfully. |
|  [landmarkAnnotations](./vision.vision_v1p1beta1.schema_annotateimageresponse.landmarkannotations.md) | [Schema$EntityAnnotation](./vision.vision_v1p1beta1.schema_entityannotation.md)<!-- -->\[\] | If present, landmark detection has completed successfully. |
|  [localizedObjectAnnotations](./vision.vision_v1p1beta1.schema_annotateimageresponse.localizedobjectannotations.md) | [Schema$LocalizedObjectAnnotation](./vision.vision_v1p1beta1.schema_localizedobjectannotation.md)<!-- -->\[\] | If present, localized object detection has completed successfully. This will be sorted descending by confidence score. |
|  [logoAnnotations](./vision.vision_v1p1beta1.schema_annotateimageresponse.logoannotations.md) | [Schema$EntityAnnotation](./vision.vision_v1p1beta1.schema_entityannotation.md)<!-- -->\[\] | If present, logo detection has completed successfully. |
|  [productSearchResults](./vision.vision_v1p1beta1.schema_annotateimageresponse.productsearchresults.md) | [Schema$ProductSearchResults](./vision.vision_v1p1beta1.schema_productsearchresults.md) | If present, product search has completed successfully. |
|  [safeSearchAnnotation](./vision.vision_v1p1beta1.schema_annotateimageresponse.safesearchannotation.md) | [Schema$SafeSearchAnnotation](./vision.vision_v1p1beta1.schema_safesearchannotation.md) | If present, safe-search annotation has completed successfully. |
|  [textAnnotations](./vision.vision_v1p1beta1.schema_annotateimageresponse.textannotations.md) | [Schema$EntityAnnotation](./vision.vision_v1p1beta1.schema_entityannotation.md)<!-- -->\[\] | If present, text (OCR) detection has completed successfully. |
|  [webDetection](./vision.vision_v1p1beta1.schema_annotateimageresponse.webdetection.md) | [Schema$WebDetection](./vision.vision_v1p1beta1.schema_webdetection.md) | If present, web detection has completed successfully. |

