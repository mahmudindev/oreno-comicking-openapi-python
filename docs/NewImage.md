# NewImage


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**alternative_text** | **str** |  | [optional] 
**link_website_host** | **str** |  | 
**link_relative_reference** | **str** |  | [optional] 

## Example

```python
from comicking_openapi.models.new_image import NewImage

# TODO update the JSON string below
json = "{}"
# create an instance of NewImage from a JSON string
new_image_instance = NewImage.from_json(json)
# print the JSON string representation of the object
print(NewImage.to_json())

# convert the object into a dict
new_image_dict = new_image_instance.to_dict()
# create an instance of NewImage from a dict
new_image_form_dict = new_image.from_dict(new_image_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


