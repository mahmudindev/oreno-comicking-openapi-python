# Language


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**created_at** | **datetime** |  | 
**updated_at** | **datetime** |  | [optional] 
**lang** | **str** |  | 
**name** | **str** |  | 

## Example

```python
from comicking_openapi.models.language import Language

# TODO update the JSON string below
json = "{}"
# create an instance of Language from a JSON string
language_instance = Language.from_json(json)
# print the JSON string representation of the object
print(Language.to_json())

# convert the object into a dict
language_dict = language_instance.to_dict()
# create an instance of Language from a dict
language_form_dict = language.from_dict(language_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


