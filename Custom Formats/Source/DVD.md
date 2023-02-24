```JSON
{
  "name": "DVD",
  "includeCustomFormatWhenRenaming": false,
  "specifications": [
    {
      "name": "DVD",
      "implementation": "SourceSpecification",
      "negate": false,
      "required": true,
      "fields": {
        "value": 5
      }
    },
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
      "name": "Encode",
      "implementation": "ReleaseTitleSpecification",
      "negate": true,
      "required": true,
      "fields": {
        "value": "x265|x.265|x.264|x264"
      }
    }
  ]
}
```

