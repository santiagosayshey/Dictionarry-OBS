```JSON
{
  "name": "DTS",
  "includeCustomFormatWhenRenaming": true,
  "specifications": [
    {
      "name": "Basic DTS",
      "implementation": "ReleaseTitleSpecification",
      "negate": false,
      "required": true,
      "fields": {
        "value": "\\bDTS(\\b|\\d)"
      }
    },
    {
      "name": "Not DTS-HD",
      "implementation": "ReleaseTitleSpecification",
      "negate": true,
      "required": true,
      "fields": {
        "value": "dts[ .-]?(ma\\b|hd[ .-]?ma|hd)(?!china|r)"
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
      "name": "Not Basic Dolby Digital",
      "implementation": "ReleaseTitleSpecification",
      "negate": true,
      "required": true,
      "fields": {
        "value": "\\bDD(\\b|\\d)|(?<!e)ac3"
      }
    },
    {
      "name": "Not DTS X",
      "implementation": "ReleaseTitleSpecification",
      "negate": true,
      "required": true,
      "fields": {
        "value": "dts[-. ]?x(?!\\d)"
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