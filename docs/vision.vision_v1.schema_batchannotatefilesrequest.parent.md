<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@google/vision](./vision.md) &gt; [vision\_v1](./vision.vision_v1.md) &gt; [Schema$BatchAnnotateFilesRequest](./vision.vision_v1.schema_batchannotatefilesrequest.md) &gt; [parent](./vision.vision_v1.schema_batchannotatefilesrequest.parent.md)

## vision\_v1.Schema$BatchAnnotateFilesRequest.parent property

Optional. Target project and location to make a call.

Format: `projects/{project-id\}/locations/{location-id\}`<!-- -->.

If no parent is specified, a region will be chosen automatically.

Supported location-ids: `us`<!-- -->: USA country only, `asia`<!-- -->: East asia areas, like Japan, Taiwan, `eu`<!-- -->: The European Union.

Example: `projects/project-A/locations/eu`<!-- -->.

<b>Signature:</b>

```typescript
parent?: string | null;
```
