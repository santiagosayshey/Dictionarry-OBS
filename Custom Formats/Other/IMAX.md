```JSON
{
  "name": "IMAX",
  "includeCustomFormatWhenRenaming": true,
  "specifications": [
    {
      "name": "IMAX",
      "implementation": "ReleaseTitleSpecification",
      "negate": false,
      "required": true,
      "fields": {
        "value": "\\bIMAX\\b"
      }
    },
    {
      "name": "WEB",
      "implementation": "SourceSpecification",
      "negate": false,
      "required": true,
      "fields": {
        "value": 7
      }
    }
  ]
}
```