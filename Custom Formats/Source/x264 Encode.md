```JSON
{
  "name": "x264 Encode",
  "includeCustomFormatWhenRenaming": false,
  "specifications": [
    {
      "name": "REMUX",
      "implementation": "ReleaseTitleSpecification",
      "negate": true,
      "required": true,
      "fields": {
        "value": "REMUX"
      }
    },
    {
      "name": "WEBDL",
      "implementation": "SourceSpecification",
      "negate": true,
      "required": true,
      "fields": {
        "value": 7
      }
    },
    {
      "name": "WEBRIP",
      "implementation": "SourceSpecification",
      "negate": true,
      "required": true,
      "fields": {
        "value": 8
      }
    },
    {
      "name": "x264",
      "implementation": "ReleaseTitleSpecification",
      "negate": false,
      "required": true,
      "fields": {
        "value": "x264|x.264"
      }
    }
  ]
}
```