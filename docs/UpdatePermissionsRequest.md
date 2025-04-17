# UpdatePermissionsRequest

Describes the request body of the /updatepermissions API call

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**datasource** | **str** |  | 
**permissions** | [**DocumentPermissionsDefinition**](DocumentPermissionsDefinition.md) |  | 
**object\_type** | **str** | The type of the document (Case, KnowledgeArticle for Salesforce for example). It cannot have spaces or \_ | [optional] 
**id** | **str** | The datasource specific id for the document. This field is case insensitive and should not be more than 200 characters in length. | [optional] 
**view\_url** | **str** | The permalink for viewing the document. **Note: viewURL is a required field if id was not set when uploading the document.**&#39;  | [optional] 
**any string name** | **bool, date, datetime, dict, float, int, list, str, none\_type** | any string name can be used but the value must be the correct type | [optional]

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


