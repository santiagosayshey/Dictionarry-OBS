```JSON
{
  "name": "Dolby Digital",
  "includeCustomFormatWhenRenaming": true,
  "specifications": [
    {
      "name": "Basic Dolby Digital",
      "implementation": "ReleaseTitleSpecification",
      "negate": false,
      "required": true,
      "fields": {
        "value": "\\bDD[^a-z+]|(?<!e)ac3"
      }
    },
    {
      "name": "Not Dolby Digital Plus",
      "implementation": "ReleaseTitleSpecification",
      "negate": true,
      "required": true,
      "fields": {
        "value": "[^-]dd[p+]|eac3"
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
      "name": "Not DTS",
      "implementation": "ReleaseTitleSpecification",
      "negate": true,
      "required": true,
      "fields": {
        "value": "\\bDTS(\\b|\\d)"
      }
    },
    {
      "name": "Not FLAC",
      "implementation": "ReleaseTitleSpecification",
      "negate": true,
      "required": true,
      "fields": {
        "value": "\\bFLAC(\\b|\\d)"
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
      "name": "Not PCM",
      "implementation": "ReleaseTitleSpecification",
      "negate": true,
      "required": true,
      "fields": {
        "value": "\\b(l?)PCM(\\b|\\d)"
      }
    }
  ]
}
```