```JSON
{
  "name": "UHD",
  "includeCustomFormatWhenRenaming": false,
  "specifications": [
    {
      "name": "Blu-Ray",
      "implementation": "SourceSpecification",
      "negate": false,
      "required": true,
      "fields": {
        "value": 9
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
    },
    {
      "name": "1080p",
      "implementation": "ReleaseTitleSpecification",
      "negate": true,
      "required": true,
      "fields": {
        "value": "1080|BD50|BD66"
      }
    }
  ]
}
```

