```JSON
{
  "name": "FLAC",
  "includeCustomFormatWhenRenaming": true,
  "specifications": [
    {
      "name": "FLAC",
      "implementation": "ReleaseTitleSpecification",
      "negate": false,
      "required": true,
      "fields": {
        "value": "\\bFLAC(\\b|\\d)"
      }
    },
    {
      "name": "Not PCM",
      "implementation": "ReleaseTitleSpecification",
      "negate": true,
      "required": true,
      "fields": {
        "value": "\\b(l?)PCM(\\b|\\d)"
      }
    },
    {
      "name": "Not AAC",
      "implementation": "ReleaseTitleSpecification",
      "negate": true,
      "required": true,
      "fields": {
        "value": "\\bAAC(\\b|\\d)"
      }
    },
    {
      "name": "Not DTS",
      "implementation": "ReleaseTitleSpecification",
      "negate": true,
      "required": true,
      "fields": {
        "value": "\\bDTS(\\b|\\d)"
      }
    },
    {
      "name": "Not TrueHD/ATMOS",
      "implementation": "ReleaseTitleSpecification",
      "negate": true,
      "required": true,
      "fields": {
        "value": "TrueHD|\\bATMOS(\\b|\\d)"
      }
    },
    {
      "name": "Not Basic Dolby Digital",
      "implementation": "ReleaseTitleSpecification",
      "negate": true,
      "required": true,
      "fields": {
        "value": "(?<!e)ac3"
      }
    },
    {
      "name": "Not Dolby Digital Plus ",
      "implementation": "ReleaseTitleSpecification",
      "negate": true,
      "required": true,
      "fields": {
        "value": "[^-]dd[p+]|eac3"
      }
    }
  ]
}
```