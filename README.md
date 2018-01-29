# clearbridge-form-builder
form builder for mozilla react-jsonschema-form

A [live playground](https://clearbridgesoft.github.io/clearbridge-form-builder/) is hosted on gh-pages.

# clearbridge-form-builder
form builder for mozilla react-jsonschema-form

A [live playground](https://clearbridgesoft.github.io/clearbridge-form-builder/) is hosted on gh-pages.

## How to use it?
----
1. To Add New Fields:
   * Right click on root or any field names.
   * Select basic field.
   * Select field that you would like to create. For example: Textbox
   * A new field will be created. If you select from the root, it will add this field to the bottom of the form. If you select a particular field. The new field will be created below that field. 
   
2. View and Edit Properties:
   * Click any field you would like to edit. 
   * The properties will be appeared on the right screen. 
   * The properties will have:
     * Name: a field name, this field can't contain any space
     * title: This field is used to modify the title of this field on the form-builder. 
     * description: This field is used to describe more for the field. It will be also appeared on the form builder with smaller amount(you can adjust the css to change the font).
     * classNames: You can identify the class name of CSS and then apply it to the field. This is useful when you have repeated fields with similar design.
     * Help Text: This fields is used as a hint of the field's purpose. It will be displayed under the field with grey and smaller font.
     * Placeholder: This field to create place holder in the field

3. Moving fields
     * To move the fields, you can easily drag and drop the field from the tree view.  

4. Delete field
    * There is a (x) button to delete the field from the tree view

5. View the schema
    * You can view two schemas, form schema and ui schema. Please refer to https://github.com/mozilla-services/react-jsonschema-form#the-uischema-object. These schemas are available on the buttom of the page. Click "Schema & Ui Schema" to open the accordion.
    
6. View the data
     * When you enter the data on the fields, the data-schema will be populated and this schema is used to submit your form

7. View the config
   * The config can be opened via properties's field. Click 'Json' in order to open a form-schema and ui-schema for only this particular field

8. Undo
   * You can also undo your action (`before save`). The button is available on the top left.




   
