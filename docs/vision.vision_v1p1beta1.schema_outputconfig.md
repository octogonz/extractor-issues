<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@google/vision](./vision.md) &gt; [vision\_v1p1beta1](./vision.vision_v1p1beta1.md) &gt; [Schema$OutputConfig](./vision.vision_v1p1beta1.schema_outputconfig.md)

## vision\_v1p1beta1.Schema$OutputConfig interface

The desired output location and metadata.

<b>Signature:</b>

```typescript
export interface Schema$OutputConfig 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [batchSize](./vision.vision_v1p1beta1.schema_outputconfig.batchsize.md) | number \| null | The max number of response protos to put into each output JSON file on Google Cloud Storage. The valid range is \[1, 100\]. If not specified, the default value is 20.<!-- -->For example, for one pdf file with 100 pages, 100 response protos will be generated. If <code>batch_size</code> = 20, then 5 json files each containing 20 response protos will be written under the prefix <code>gcs_destination</code>.<code>uri</code>.<!-- -->Currently, batch\_size only applies to GcsDestination, with potential future support for other output configurations. |
|  [gcsDestination](./vision.vision_v1p1beta1.schema_outputconfig.gcsdestination.md) | [Schema$GcsDestination](./vision.vision_v1p1beta1.schema_gcsdestination.md) | The Google Cloud Storage location to write the output(s) to. |

