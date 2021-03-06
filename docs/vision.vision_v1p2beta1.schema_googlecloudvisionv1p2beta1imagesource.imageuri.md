<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@google/vision](./vision.md) &gt; [vision\_v1p2beta1](./vision.vision_v1p2beta1.md) &gt; [Schema$GoogleCloudVisionV1p2beta1ImageSource](./vision.vision_v1p2beta1.schema_googlecloudvisionv1p2beta1imagesource.md) &gt; [imageUri](./vision.vision_v1p2beta1.schema_googlecloudvisionv1p2beta1imagesource.imageuri.md)

## vision\_v1p2beta1.Schema$GoogleCloudVisionV1p2beta1ImageSource.imageUri property

The URI of the source image. Can be either:

1. A Google Cloud Storage URI of the form `gs://bucket_name/object_name`<!-- -->. Object versioning is not supported. See \[Google Cloud Storage Request URIs\](https://cloud.google.com/storage/docs/reference-uris) for more info.

2. A publicly-accessible image HTTP/HTTPS URL. When fetching images from HTTP/HTTPS URLs, Google cannot guarantee that the request will be completed. Your request may fail if the specified host denies the request (e.g. due to request throttling or DOS prevention), or if Google throttles requests to the site for abuse prevention. You should not depend on externally-hosted images for production applications.

When both `gcs_image_uri` and `image_uri` are specified, `image_uri` takes precedence.

<b>Signature:</b>

```typescript
imageUri?: string | null;
```
