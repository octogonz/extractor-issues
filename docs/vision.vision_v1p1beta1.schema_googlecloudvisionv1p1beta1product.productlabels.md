<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@google/vision](./vision.md) &gt; [vision\_v1p1beta1](./vision.vision_v1p1beta1.md) &gt; [Schema$GoogleCloudVisionV1p1beta1Product](./vision.vision_v1p1beta1.schema_googlecloudvisionv1p1beta1product.md) &gt; [productLabels](./vision.vision_v1p1beta1.schema_googlecloudvisionv1p1beta1product.productlabels.md)

## vision\_v1p1beta1.Schema$GoogleCloudVisionV1p1beta1Product.productLabels property

Key-value pairs that can be attached to a product. At query time, constraints can be specified based on the product\_labels.

Note that integer values can be provided as strings, e.g. "1199". Only strings with integer values can match a range-based restriction which is to be supported soon.

Multiple values can be assigned to the same key. One product may have up to 500 product\_labels.

Notice that the total number of distinct product\_labels over all products in one ProductSet cannot exceed 1M, otherwise the product search pipeline will refuse to work for that ProductSet.

<b>Signature:</b>

```typescript
productLabels?: Schema$GoogleCloudVisionV1p1beta1ProductKeyValue[];
```
