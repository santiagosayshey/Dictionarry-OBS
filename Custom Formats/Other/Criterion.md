```JSON
{
  "name": "Criterion Collection",
  "includeCustomFormatWhenRenaming": true,
  "specifications": [
    {
      "name": "Criterion",
      "implementation": "ReleaseTitleSpecification",
      "negate": false,
      "required": false,
      "fields": {
        "value": "criterion"
      }
    },
    {
      "name": "CC",
      "implementation": "ReleaseTitleSpecification",
      "negate": false,
      "required": false,
      "fields": {
        "value": "\\bCC|C.C.\\b"
      }
    }
  ]
}
```