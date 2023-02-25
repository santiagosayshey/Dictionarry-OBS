```JSON
{
  "name": "DV ",
  "includeCustomFormatWhenRenaming": true,
  "specifications": [
    {
      "name": "WEB",
      "implementation": "SourceSpecification",
      "negate": false,
      "required": true,
      "fields": {
        "value": 7
      }
    },
    {
      "name": "DV",
      "implementation": "ReleaseTitleSpecification",
      "negate": false,
      "required": true,
      "fields": {
        "value": "\\b(DV|DoVi)\\b"
      }
    },
    {
      "name": "HULU",
      "implementation": "ReleaseTitleSpecification",
      "negate": true,
      "required": false,
      "fields": {
        "value": "\\b(HULU)\\b"
      }
    },
    {
      "name": "BLURAY",
      "implementation": "SourceSpecification",
      "negate": true,
      "required": false,
      "fields": {
        "value": 9
      }
    }
  ]
}
```