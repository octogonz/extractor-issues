<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@google/vision](./vision.md) &gt; [vision\_v1p2beta1](./vision.vision_v1p2beta1.md) &gt; [Schema$GoogleCloudVisionV1p2beta1ProductSearchResults](./vision.vision_v1p2beta1.schema_googlecloudvisionv1p2beta1productsearchresults.md)

## vision\_v1p2beta1.Schema$GoogleCloudVisionV1p2beta1ProductSearchResults interface

Results for a product search request.

<b>Signature:</b>

```typescript
export interface Schema$GoogleCloudVisionV1p2beta1ProductSearchResults 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [indexTime](./vision.vision_v1p2beta1.schema_googlecloudvisionv1p2beta1productsearchresults.indextime.md) | string \| null | Timestamp of the index which provided these results. Products added to the product set and products removed from the product set after this time are not reflected in the current results. |
|  [productGroupedResults](./vision.vision_v1p2beta1.schema_googlecloudvisionv1p2beta1productsearchresults.productgroupedresults.md) | [Schema$GoogleCloudVisionV1p2beta1ProductSearchResultsGroupedResult](./vision.vision_v1p2beta1.schema_googlecloudvisionv1p2beta1productsearchresultsgroupedresult.md)<!-- -->\[\] | List of results grouped by products detected in the query image. Each entry corresponds to one bounding polygon in the query image, and contains the matching products specific to that region. There may be duplicate product matches in the union of all the per-product results. |
|  [results](./vision.vision_v1p2beta1.schema_googlecloudvisionv1p2beta1productsearchresults.results.md) | [Schema$GoogleCloudVisionV1p2beta1ProductSearchResultsResult](./vision.vision_v1p2beta1.schema_googlecloudvisionv1p2beta1productsearchresultsresult.md)<!-- -->\[\] | List of results, one for each product match. |

