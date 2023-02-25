```JSON
{
  "name": "DV + HDR10+",
  "includeCustomFormatWhenRenaming": true,
  "specifications": [
    {
      "name": "BLURAY",
      "implementation": "SourceSpecification",
      "negate": false,
      "required": false,
      "fields": {
        "value": 9
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
      "negate": false,
      "required": false,
      "fields": {
        "value": "\\b(HULU)\\b"
      }
    },
    {
      "name": "HDR10+",
      "implementation": "ReleaseTitleSpecification",
      "negate": false,
      "required": true,
      "fields": {
        "value": "\\bHDR10Plus|HDR10(\\b\\+)"
      }
    }
  ]
}
```