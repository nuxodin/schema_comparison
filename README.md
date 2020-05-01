# Schema comparison
Comparison of different Standards describing data



| JSON-Schema        | HTML-Input           | SQL  |
| ------------- | ------------- | ----- |
| type          | type          | Type |
| subtype       | format          | - |
| multipleOf    | steps         | decimal(12,`2`) |
| maxLength     | maxlength     | length |
| min     | min     | - |
| max     | max     | - |
| required     | required     | NOT NULL |
| pattern     | pattern     | - |


# Subtype values


| JSON-Schema   | HTML-Input (type-attr)  | HTML-Input (autocomplete-attr) | SQL  |
| ------------- | ----------------------- | ------------------------------ | -------- |
| date-time     | date-time               | -                              | datetime | 
| date          | date                    | -                              | date     |
