# aliases_mapping
Using aliases to update custom module fields while preserving field values on website

###
[YouTube video](https://youtu.be/f8BbvdIjbaw) demoing this feature
###
[Developer Documentation](https://developers.hubspot.com/docs/cms/marketplace-guidelines/module-requirements#aliases)

There are two json files.  V0 includes the fields prior to being grouped and moved.  v1 includes the `aliasses_mapping` in action

The important thing to remember is the location of the new field name in the alias mapping.

```aliases_mapping": {
          "property_aliases_paths": {
            "button_text_color_new": <--New field is on this line
              [ 
              "button_text_color" <-- Old field is on this line
              ]
            }
          
      

 
