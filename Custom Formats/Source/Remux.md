```JSON
{
  "name": "REMUX",
  "includeCustomFormatWhenRenaming": false,
  "specifications": [
    {
      "name": "WEBDL",
      "implementation": "SourceSpecification",
      "negate": true,
      "required": false,
      "fields": {
        "value": 7
      }
    },
    {
      "name": "WEBRIP",
      "implementation": "SourceSpecification",
      "negate": true,
      "required": false,
      "fields": {
        "value": 8
      }
    },
    {
      "name": "REMUX",
      "implementation": "ReleaseTitleSpecification",
      "negate": false,
      "required": true,
      "fields": {
        "value": "REMUX"
      }
    }
  ]
}
```