<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@google/vision](./vision.md) &gt; [vision\_v1](./vision.vision_v1.md) &gt; [Resource$Projects$Locations$Productsets](./vision.vision_v1.resource_projects_locations_productsets.md) &gt; [create](./vision.vision_v1.resource_projects_locations_productsets.create.md)

## vision\_v1.Resource$Projects$Locations$Productsets.create() method

Creates and returns a new ProductSet resource.

Possible errors:

\* Returns INVALID\_ARGUMENT if display\_name is missing, or is longer than 4096 characters.

<b>Signature:</b>

```typescript
create(params: Params$Resource$Projects$Locations$Productsets$Create, options: StreamMethodOptions): GaxiosPromise<Readable>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  params | [Params$Resource$Projects$Locations$Productsets$Create](./vision.vision_v1.params_resource_projects_locations_productsets_create.md) | Parameters for request |
|  options | StreamMethodOptions | Optionally override request options, such as <code>url</code>, <code>method</code>, and <code>encoding</code>. |

<b>Returns:</b>

GaxiosPromise&lt;Readable&gt;

A promise if used with async/await, or void if used with a callback.

## Example


```js
// Before running the sample:
// - Enable the API at:
//   https://console.developers.google.com/apis/api/vision.googleapis.com
// - Login into gcloud by running:
//   `$ gcloud auth application-default login`
// - Install the npm module by running:
//   `$ npm install googleapis`

const {google} = require('googleapis');
const vision = google.vision('v1');

async function main() {
  const auth = new google.auth.GoogleAuth({
    // Scopes can be specified either as an array or as a single, space-delimited string.
    scopes: [
      'https://www.googleapis.com/auth/cloud-platform',
      'https://www.googleapis.com/auth/cloud-vision',
    ],
  });

  // Acquire an auth client, and bind it to all future calls
  const authClient = await auth.getClient();
  google.options('auth', authClient);

  // Do the magic
  const res = await vision.projects.locations.productSets.create({
    // Required. The project in which the ProductSet should be created.
    //
    // Format is `projects/PROJECT_ID/locations/LOC_ID`.
    parent: 'projects/my-project/locations/my-location',
    // A user-supplied resource id for this ProductSet. If set, the server will
    // attempt to use this value as the resource id. If it is already in use, an
    // error is returned with code ALREADY_EXISTS. Must be at most 128 characters
    // long. It cannot contain the character `/`.
    productSetId: 'placeholder-value',

    // Request body metadata
    requestBody: {
      // request body parameters
      // {
      //   "displayName": "my_displayName",
      //   "indexError": {},
      //   "indexTime": "my_indexTime",
      //   "name": "my_name"
      // }
    },
  });
  console.log(res.data);

  // Example response
  // {
  //   "displayName": "my_displayName",
  //   "indexError": {},
  //   "indexTime": "my_indexTime",
  //   "name": "my_name"
  // }
}

main().catch(e => {
  console.error(e);
  throw e;
});


```
