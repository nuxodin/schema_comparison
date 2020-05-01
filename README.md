# Schema comparison
Comparison of different Standards describing data


## Properties

| JSON-Schema   | HTML-Input    | SQL             |
| ------------- | ------------- | --------------- |
| type          | type          | Type            |
| format        | type          | -               |
| multipleOf    | steps         | decimal(12,`2`) |
| minLength     | minlength     | -               |
| maxLength     | maxlength     | length          |
| min           | min           | -               |
| max           | max           | -               |
| required      | required      | NOT NULL        |
| pattern       | pattern       | -               |
| enum          | <select>      | ENUM            |


## Subtype values


| JSON-Schema   | HTML-Input (type-attr)  | HTML-Input (autocomplete-attr) | SQL      |
| ------------- | ----------------------- | ------------------------------ | -------- |
| date-time     | date-time               | -                              | DATETIME | 
| date          | date                    | -                              | DATE     |
| time          | time                    | -                              | TIME     |
| url           | url                     | url (photo,impp)               | -        |
| -             | tel                     | tel                            | -        |

